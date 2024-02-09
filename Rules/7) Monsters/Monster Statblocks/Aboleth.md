---
statblock: inline
name: Aboleth
obsidianUIMode: preview
tags:
  - monster
aliases:
  -
source: Core
---
```statblock
image: [[aboleth.png]]
name: Aboleth
description: Enormous, antediluvian catfish covered in slime and tentacles. They hate all intelligent beings.
alignment: C
level: 8
ac: 16
hp: 39
hit_dice: 8d8+3
mv: near (swim)
stats: [4,-1,3,4,2,2]
modifier: -1
traits:
  - name: "Curse"
    desc: DC 15 CON or target gains a magical curse, turning into a [[deep one]] over 11 (2d10) days
  - name: "Enslave"
    desc: "In place of attacks, one creature within far DC 15 WIS or aboleth controls for 2 (1d4) rounds"
  - name: "Telepathic"
    desc: "Read the thoughts of all creatures within far"
"actions":
  - "name": "Multiattack"
    "desc": "2 bites or 1 poison web"
  - "name": "Bite"
    "desc": "close, Attack: +2 to hit, 3 (1d6) damage"
  - "name": "Poison Web"
    "desc": "near, Attack: +2 to hit, 3 (1d6) damage"
source: Core
```

