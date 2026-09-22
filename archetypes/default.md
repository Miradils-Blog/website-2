---
title: "{{ replace .File.ContentBaseName "-" " " | title }}"
date: {{ .Date }}
draft: true
weight: 1
# Files under static/ (leading slash), page-bundle resources, or absolute URLs.
slideshow:
  - "/content/{{ .File.Section }}/{{ .File.ContentBaseName }}/01.jpg"
---
