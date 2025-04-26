{{- $l := site.Data.lang | len }}

{{- T "gltotal" $l }}

{{- if gt $l 0 }}
{{- range $k, $v := site.Data.lang }}
{{- /*
, by {{ if $v.author.homepage }}[{{ $v.author.name }}]({{ $v.author.homepage }}){{ else }}{{ $v.author.name }}{{ end }}
*/}}
- {{ $k }} ({{ $v.name }}), [Download {{ $v.name }}](https://github.com/gamemgh/langs/releases/download/lang/{{ $k }}.zip) last updated on {{ ($v.lastmod | default "never") }}
{{- end }}
{{- end }}