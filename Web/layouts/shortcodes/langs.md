{{- $l := site.Data.langs | len }}

{{- T "gltotal" $l }}

{{- if gt $l 0 }}
{{- range $k, $v := site.Data.langs }}
- {{ $k }} ({{ $v.name }}), by {{ if $v.author.homepage }}[{{ $v.author.name }}]({{ $v.author.homepage }}){{ else }}{{ $v.author.name }}{{ end }}, [Download {{ $v.name }}](https://github.com/gamemgh/langs/releases/download/lang/{{ $k }}.zip)
{{- end }}
{{- end }}