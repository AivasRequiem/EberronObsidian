---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Gloamwing
---
# [Gloamwing](Інструменти ДМ\CLI\bestiary\undead/gloamwing-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 215*  

A gloamwing's head is almost ratlike, with prominent teeth, and its leathery skin is stretched tight over its skull, where its eyes are empty sockets. Its body is mottled with bony plates, and great wings stretch from its shoulders.

```statblock
"name": "Gloamwing (GGR)"
"size": "Large"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "16d10 + 48"
"modifier": !!int "3"
"stats":
  - !!int "20"
  - !!int "16"
  - !!int "17"
  - !!int "2"
  - !!int "11"
  - !!int "6"
"speed": "30 ft., fly 60 ft."
"saves":
  - "strength": "+8"
  - "dexterity": "+6"
"skillsaves":
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](Інструменти%20ДМ/CLI/rules/skills.md#Stealth)"
    "desc": "+6"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed),\
  \ [exhaustion](Інструменти%20ДМ/CLI/rules/conditions.md#Exhaustion), [frightened](І\
  нструменти%20ДМ/CLI/rules/conditions.md#Frightened), [poisoned](Інструменти%20ДМ\
  /CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": "understands Common"
"cr": "8"
"traits":
  - "desc": "If its specter rider is reduced to 0 hit points, the gloamwing is destroyed."
    "name": "Death Link"
  - "desc": "The gloamwing doesn't provoke an opportunity attack when it flies out\
      \ of an enemy's reach."
    "name": "Flyby"
  - "desc": "While in sunlight, the gloamwing has disadvantage on attack rolls, as\
      \ well as on Wisdom ([Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception))\
      \ checks that rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "The gloamwing makes two attacks: one with its bite and one with its claws."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 18\
      \ (3d8 + 5) piercing damage."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 15\
      \ (3d6 + 5) slashing damage."
    "name": "Claws"
"source":
  - "GGR"
"image": "Інструменти%20ДМ/CLI/bestiary/undead/token/gloamwing-ggr.webp"
```
^statblock