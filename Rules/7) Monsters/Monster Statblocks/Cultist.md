---
statblock: inline
name:  Cultist
obsidianUIMode: preview
tags:
  - monster
aliases:
  -
source: Core
---

```statblock
image: [[cultist.png]]
name: Cultist
description: A cloaked, wild-eyed zealot chanting the guttural prayers of a dark god.
alignment: C
level: 2
cr: 2
ac: 14 (chainmail + shield)
hp: 9
hit_dice: 2d8
mv: near
stats: [1,-1,0,-1,2,0]
modifier: -1
languages: Common
traits:
  - name: Fearless
    desc: Immune to morale checks
  - name: Deathtouch (WIS Spell)
    desc: DC12. 2d4 damage to one creature within close.
"actions":
  - "name": 1 longsword +1
    "desc": Hit 11 (1d20+1), Damage 4 (1d8)
  - "name": Deathtouch +2
    "desc": Hit 12 (1d20+2) vs DC12, Damage 5 (2d4)
source: Core
```

