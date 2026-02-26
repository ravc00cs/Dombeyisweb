---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
params:
  license: "copyright"
  rights: "© {{ now.Year }} Ricardo Vivanco C. Todos los derechos reservados."
---
