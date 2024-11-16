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
- eastleigh-tc
- ebc
- mp
params:
    username: '{{ replace (.File.ContentBaseName | title) `-` `` }}'
    # ebc: ''
    # parliament: ''
    # bluesky: 'https://bsky.app/profile/'
    # facebook: 'https://www.facebook.com/'
    # instagram: ''
    # mastodon: ''
    # threads: ''
    # twitter: ''
    # youtube: ''
    # wcivf: 'https://whocanivotefor.co.uk/'
---
