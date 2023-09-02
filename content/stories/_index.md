{{ range .Site.RegularPages.ByDate.Reverse }}
  {{ if eq .Section "stories" }}
    <h2>{{ .Title }}</h2>
  {{ end }}
{{ end }}
