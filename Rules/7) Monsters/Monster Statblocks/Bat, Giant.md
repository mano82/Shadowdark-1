---
statblock: inline
name:  Bat, Giant
obsidianUIMode: preview
tags:
  - monster
aliases:
  - Pipistrello Gigante
source: Core
---

```statblock
image: [[bat.png]]
name: "Bat, Giant"
description: "Leathery, eagle-sized mammal with a taste for flesh."
alignment: N
level: 2
cr: 2
ac: 12
hp: 9
stats: [-1,2,0,-3,1,-3]
hit_dice: 2d8
mv: near (fly)
modifier: 2
%%languages: string%%
%% traits:
  - name: 
    desc: %% 
%%spells:
  - <description>
  - <spell level>: <spell-list>%%
"actions":
  - "name": 1 bite 
    "desc": Hit 12 (1d20+2), damage 3 (1d6)
%%reactions:
  - name: <reaction-name>
    desc: <reaction-description>
  - ...%%
```