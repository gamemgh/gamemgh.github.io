{{- $data := slice -}}
{{- with resources.Get "rfc_voices.json" -}}
	{{- with . | transform.Unmarshal -}}
		{{- $data = . -}}
	{{- end -}}
{{- else -}}
	{{- errorf "Failed to retrieve RFC voice data" -}}
{{- end -}}

{{- range $data -}}
	{{- $name := .name -}}
	{{- $author := .author -}}
	{{- $url := .author_url -}}

{{- if and $url $author (ne $name $author) }}
- {{ $name }}: by [{{ $author }}]({{ $url }})
{{- else if $url }}
- [{{ $name }}]({{ $url }})
{{- else if $author }}
- {{ $name }}: by {{ $author }}
{{- else }}
- {{ $name }}
{{- end }}
{{- end -}}
