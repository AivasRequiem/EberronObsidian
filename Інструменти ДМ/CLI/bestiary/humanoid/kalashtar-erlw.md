---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/erlw
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/kalashtar
statblock: inline
statblock-link: "#^statblock"
aliases:
- Kalashtar
---
# [Kalashtar](Інструменти ДМ\CLI\bestiary\humanoid/kalashtar-erlw.md)
*Source: Eberron: Rising from the Last War p. 317*  

The kalashtar have bonded with good-aligned quori spirits, which communicate with their hosts through dreams and visions. Descended from monks who offered their bodies as sanctuaries to those quori escaping the evil of Dal Quor, the kalashtar now fight to herald in a new age of light and balance.

```statblock
"name": "Kalashtar (ERLW)"
"size": "Medium"
"type": "humanoid"
"subtype": "kalashtar"
"alignment": "Any alignment"
"ac": !!int "12"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"modifier": !!int "2"
"stats":
  - !!int "12"
  - !!int "14"
  - !!int "12"
  - !!int "13"
  - !!int "15"
  - !!int "15"
"speed": "30 ft."
"skillsaves":
  - "name": "[Acrobatics](Інструменти%20ДМ/CLI/rules/skills.md#Acrobatics)"
    "desc": "+4"
  - "name": "[Insight](Інструменти%20ДМ/CLI/rules/skills.md#Insight)"
    "desc": "+4"
  - "name": "[Persuasion](Інструменти%20ДМ/CLI/rules/skills.md#Persuasion)"
    "desc": "+6"
"damage_resistances": "psychic"
"senses": "passive Perception 12"
"languages": "Common, telepathy 20 ft."
"cr": "1/4"
"traits":
  - "desc": "The kalashtar has advantage on Wisdom saving throws."
    "name": "Dual Mind"
"actions":
  - "desc": "Melee  or Ranged Weapon Attack: dice:1d20+4|noform|noparens|text(+4)\
      \ to hit, reach 5 ft. or range 20/60 ft., one target. Hit: dice:1d4+2|noform|noparens|avg|text(4)\
      \ (1d4 + 2) piercing damage."
    "name": "Dagger"
  - "desc": "The kalashtar targets a creature it can see within 30 feet of it. The\
      \ target must succeed on a DC 12 Wisdom saving throw or take dice:2d10|noform|noparens|avg|text(11)\
      \ (2d10) psychic damage."
    "name": "Mind Thrust"
"source":
  - "ERLW"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/kalashtar-erlw.webp"
```
^statblock