---
statblock: inline
name: Basilisk
obsidianUIMode: preview
tags:
  - monster
aliases:
  - Basilisco
---

```statblock
image: [[basilisk.png]]
name: Basilisk
description: Massive, muscled lizards with  six legs and gray, tough hide.
alignment: N
level: 5
cr: 5
ac: 14
hp: 25
hit_dice: 5d8+3
mv: near
stats: [3,1,3,-3,1,-3]
modifier: 1
%%languages: string%%
traits:
  - name: "Petrify"
    desc: "Any creature that touches  the basilisk or meets its gaze, DC 15 CON or petrified."
%%spells:
  - <description>
  - <spell level>: <spell-list>%%
actions:
  - "name": "2 bite +4"
    "desc": "To hit 14 (1d20+4), damage 7 (2d6) + petrify"
%%reactions:
  - name: <reaction-name>
    desc: <reaction-description>
  - ...%%
source: Core
```
