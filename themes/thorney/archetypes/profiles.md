---
date: '{{ .Date }}'
draft: true
title: '{{ replace .File.ContentBaseName `-` ` ` | title }}'
outputs:
- actor
- html
- webfinger
params:
    username: '{{ replace (.File.ContentBaseName | title) `-` `` }}'
    wcivf: https://whocanivotefor.co.uk/
---
