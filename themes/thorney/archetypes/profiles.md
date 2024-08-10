---
date: '{{ .Date }}'
draft: true
title: '{{ replace .File.ContentBaseName `-` ` ` | title }}'
parties:
- conservative
- green
- independent
- labour
- libdem
- reformuk
platforms:
- bluesky
- facebook
- instagram
- mastodon
- threads
- youtube
roles:
- ebc
- mp
params:
    username: '{{ replace (.File.ContentBaseName | title) `-` `` }}'
    # ebc: ''
    # parliament: ''
    # bluesky: ''
    # facebook: ''
    # instagram: ''
    # mastodon: ''
    # threads: ''
    # youtube: ''
    # wcivf: 'https://whocanivotefor.co.uk/'
---
