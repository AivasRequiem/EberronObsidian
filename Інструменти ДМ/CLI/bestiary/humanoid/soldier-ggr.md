---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- Soldier
---
# [Soldier](Інструменти ДМ\CLI\bestiary\humanoid/soldier-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 226*  

Soldiers are found in many of Ravnica's guilds. The soldier stat block represents a typical member of the rank and file, though weaponry and armor can vary.

```statblock
"name": "Soldier (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "[chain mail](Інструменти%20ДМ/CLI/items/chain-mail-xphb.md), [shield](І\
  нструменти%20ДМ/CLI/items/shield-xphb.md)"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"modifier": !!int "1"
"stats":
  - !!int "13"
  - !!int "12"
  - !!int "12"
  - !!int "10"
  - !!int "11"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Athletics](Інструменти%20ДМ/CLI/rules/skills.md#Athletics)"
    "desc": "+3"
"senses": "passive Perception 12"
"languages": "any one language (usually Common)"
"cr": "1/2"
"traits":
  - "desc": "The soldier has advantage on saving throws against being [charmed](Ін\
      струменти%20ДМ/CLI/rules/conditions.md#Charmed), [frightened](Інструменти%20Д\
      М/CLI/rules/conditions.md#Frightened), [grappled](Інструменти%20ДМ/CLI/rules/conditions.md#Grappled),\
      \ or [restrained](Інструменти%20ДМ/CLI/rules/conditions.md#Restrained) while\
      \ it is within 5 feet of at least one ally."
    "name": "Formation Tactics"
"actions":
  - "desc": "The soldier makes two melee attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 6\
      \ (1d8 + 2) slashing damage, or 7 (1d10 + 2) slashing damage if used with\
      \ two hands."
    "name": "Longsword"
"source":
  - "GGR"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/soldier-ggr.webp"
```
^statblock