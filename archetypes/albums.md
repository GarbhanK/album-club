+++
title = "{{ replace .Name "-" " " | title }}"
date = "{{ .Date }}"
draft = true
week = 0
chosenby = ""
genre = ""
origin = ""
release = 0
cover = ""
tags = [{{ range $plural, $terms := .Site.Taxonomies }}{{ range $term, $val := $terms }}"{{ printf "%s" $term }}",{{ end }}{{ end }}]
+++

This is a page about »{{ replace .Name "-" " " | title }}«.

