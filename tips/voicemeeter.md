---
author:
  - name: Marc Proux
    email: marc@proux.onl
order: 0
title: Voicemeeter
---

## Description

...

## Hack

### Infinite trial
`voicemeeterpotatoinfinitetrial.reg`

```
Windows Registry Editor Version 5.00

[HKEY_CURRENT_USER\VB-Audio\VoiceMeeter]
"code"=dword:7fffffff
```

`voicemeeterpotatoresettrialtimer.reg`
```
Windows Registry Editor Version 5.00

[HKEY_CURRENT_USER\VB-Audio\VoiceMeeter]
"code"=-
```

Source: [https://gist.github.com/programminghoch10/b6021e40cc1905d2b01a1571c6c96f17](https://gist.github.com/programminghoch10/b6021e40cc1905d2b01a1571c6c96f17)

## Protocol
VBAN ([forum](https://forum.vb-audio.com/viewforum.php?f=9))

## Téléchargements
[!file VBAN Protocol Specs](../static/tips/vbanprotocol_specifications.pdf)