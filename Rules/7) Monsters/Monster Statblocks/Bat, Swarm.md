---
statblock: inline
name:  Bat, Swarm
obsidianUIMode: preview
tags:
  - monster
aliases:
  -
source: Core
---

```statblock
image: [[bat.png]]
name: Bat, Swarm
description: A whirling cloud of screeching, bloodthirsty bats.
alignment: N
level: 4
cr: 4
ac: 12
hp: 18
hit_dice: 4d8+0
mv: near (fly)
stats: [-3,2,0,-3,1,-3]
modifier: 2
%%languages: string%%
%% traits:
  - name: 
    desc:  %%
%%spells:
  - <description>
  - <spell level>: <spell-list>%%
"actions":
  - "name": 3 bite +2
    "desc": Hit 12 (1d20+2), Damage 3 (1d6)
%%reactions:
  - name: <reaction-name>
    desc: <reaction-description>
  - ...%%
```