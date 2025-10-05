---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/lmop
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- Sildar Hallwinter
---
# [Sildar Hallwinter](Інструменти ДМ\CLI\bestiary\npc/sildar-hallwinter-lmop.md)
*Source: Lost Mine of Phandelver p. 61*  

Sildar Hallwinter is a retired soldier and sellsword who hails from the city of Neverwinter. He is a loyal member of the Lords' Alliance, a political organization that unites the various free cities and towns of the North.

```statblock
"name": "Sildar Hallwinter (LMoP)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Good"
"ac": !!int "16"
"ac_class": "[chain mail](Інструменти%20ДМ/CLI/items/chain-mail-xphb.md)"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"modifier": !!int "0"
"stats":
  - !!int "13"
  - !!int "10"
  - !!int "12"
  - !!int "10"
  - !!int "11"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "strength": !!int "3"
  - "constitution": !!int "3"
"skillsaves":
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+2"
"senses": "passive Perception 12"
"languages": "Common"
"cr": "1"
"actions":
  - "desc": "Sildar makes two melee attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: dice:1d20+3|noform|noparens|text(+3) to hit,\
      \ reach 5 ft., one target. Hit: dice:1d8+1|noform|noparens|avg|text(5) (1d8\
      \ + 1) slashing damage."
    "name": "Longsword"
  - "desc": "Ranged Weapon Attack: dice:1d20+2|noform|noparens|text(+2) to hit,\
      \ range 100/400 ft., one target. Hit: dice:1d10|noform|noparens|avg|text(5)\
      \ (d10) piercing damage."
    "name": "Heavy Crossbow"
"reactions":
  - "desc": "When an attacker hits Sildar with a melee attack and Sildar can see the\
      \ attacker, he can roll dice:1d6|noform|noparens|avg (d6) and add the number\
      \ rolled to his AC against the triggering attack, provided that he's wielding\
      \ a melee weapon."
    "name": "Parry"
"source":
  - "LMoP"
"image": "Інструменти%20ДМ/CLI/bestiary/npc/token/sildar-hallwinter-lmop.webp"
```
^statblock