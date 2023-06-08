

{{ range ( .Resources.ByType "image" ) }}
  {{ .RelPermaLink }}
{{ end }}