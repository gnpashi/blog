{{ range where .Site.RegularPages "Section" "stories" }}
  {{ .Title }} <!-- Display the title of each story -->
  <!-- Add more template code to display other information about the story -->
{{ end }}
