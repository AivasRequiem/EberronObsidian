---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Indentured Spirit
---
# [Indentured Spirit](Інструменти ДМ\CLI\bestiary\undead/indentured-spirit-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 206*  

Those who die with unpaid debts to the Orzhov Syndicate don't get a reprieve. Instead, their spirits serve the syndicate until they have worked off their obligation. Sometimes that means existing as an indentured spirit for years or even millennia.

An indentured spirit is an incorporeal being draped in ghostly black robes and a hood that hides whatever face it might have. Chains are hung around its chest and arms as a perpetual marker of its servitude.

```statblock
"name": "Indentured Spirit (GGR)"
"size": "Medium"
"type": "undead"
"alignment": "Any alignment"
"ac": !!int "11"
"hp": !!int "13"
"hit_dice": "3d8"
"modifier": !!int "1"
"stats":
  - !!int "7"
  - !!int "13"
  - !!int "10"
  - !!int "10"
  - !!int "12"
  - !!int "11"
"speed": "0 ft., fly 40 ft. (hover)"
"damage_resistances": "acid; fire; lightning; thunder; bludgeoning, piercing, slashing\
  \ from nonmagical attacks"
"damage_immunities": "cold, necrotic, poison"
"condition_immunities": "[charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed),\
  \ [exhaustion](Інструменти%20ДМ/CLI/rules/conditions.md#Exhaustion), [frightened](І\
  нструменти%20ДМ/CLI/rules/conditions.md#Frightened), [grappled](Інструменти%20ДМ\
  /CLI/rules/conditions.md#Grappled), [paralyzed](Інструменти%20ДМ/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](Інструменти%20ДМ/CLI/rules/conditions.md#Petrified), [poisoned](Ін\
  струменти%20ДМ/CLI/rules/conditions.md#Poisoned), [prone](Інструменти%20ДМ/CLI/rules/conditions.md#Prone),\
  \ [restrained](Інструменти%20ДМ/CLI/rules/conditions.md#Restrained)"
"senses": "passive Perception 11"
"languages": "the languages it knew in life"
"cr": "1"
"traits":
  - "desc": "The spirit can move through other creatures and objects as if they were\
      \ difficult terrain. It takes dice:1d10|noform|noparens|avg|text(5) (d10)\
      \ force damage if it ends its turn inside an object."
    "name": "Incorporeal Movement"
"actions":
  - "desc": "Melee Weapon Attack: dice:1d20+3|noform|noparens|text(+3) to hit,\
      \ reach 5 ft., one target. Hit: dice:3d6|noform|noparens|avg|text(10) (3d6)\
      \ necrotic damage."
    "name": "Withering Touch"
"source":
  - "GGR"
"image": "Інструменти%20ДМ/CLI/bestiary/undead/token/indentured-spirit-ggr.webp"
```
^statblock