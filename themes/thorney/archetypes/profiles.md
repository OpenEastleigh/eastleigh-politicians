---
date: '{{ .Date }}'
draft: true
title: '{{ replace .File.ContentBaseName `-` ` ` | title }}'
parties:
- unknown
roles:
- unknown
params:
    username: '{{ replace (.File.ContentBaseName | title) `-` `` }}'
    wcivf: https://whocanivotefor.co.uk/
---
