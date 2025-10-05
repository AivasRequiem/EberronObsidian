---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- Drow House Captain
---
# [Drow House Captain](Інструменти ДМ\CLI\bestiary\humanoid/drow-house-captain-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 101*  

> [!quote] A quote from Tasha  
> 
> House captains will do anything to protect their family—whether that's their birth house or their platoon of scrappy rebels. I'd do anything for my (sometimes infuriating) mother and for my chosen family, so I admire their dedication.

A drow house captain leads the troops of an Underdark faction, whether defending a stronghold or leading forces against enemies. These officers make extensive study of strategy and tactics to become effective leaders in battle.

Among Lolth's devotees in the city of Menzoberranzan in the Forgotten Realms, each noble house entrusts the leadership of its military forces to a house captain, who is typically the first or second son of a drow matron mother. Elsewhere drow house captains fight in the war against Lolth, often allying with duergar and others who also wish to rid their subterranean world of that god's malevolence.

```statblock
"name": "Drow House Captain (MPMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "[chain mail](Інструменти%20ДМ/CLI/items/chain-mail-xphb.md)"
"hp": !!int "162"
"hit_dice": "25d8 + 50"
"modifier": !!int "4"
"stats":
  - !!int "14"
  - !!int "19"
  - !!int "15"
  - !!int "12"
  - !!int "14"
  - !!int "13"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "8"
  - "constitution": !!int "6"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Stealth](Інструменти%20ДМ/CLI/rules/skills.md#Stealth)"
    "desc": "+8"
"senses": "darkvision 120 ft., passive Perception 16"
"languages": "Elvish, Undercommon"
"cr": "9"
"traits":
  - "desc": "The drow has advantage on saving throws against being [charmed](Інстр\
      ументи%20ДМ/CLI/rules/conditions.md#Charmed), and magic can't put the drow to\
      \ sleep."
    "name": "Fey Ancestry"
  - "desc": "While in sunlight, the drow has disadvantage on attack rolls, as well\
      \ as on Wisdom ([Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception))\
      \ checks that rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "The drow makes two Scimitar attacks and one Whip or Hand Crossbow attack."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: dice:1d20+8|noform|noparens|text(+8) to hit,\
      \ reach 5 ft., one target. Hit: dice:1d6+4|noform|noparens|avg|text(7) (1d6\
      \ + 4) slashing damage plus dice:4d6|noform|noparens|avg|text(14) (4d6)\
      \ poison damage."
    "name": "Scimitar"
  - "desc": "Melee Weapon Attack: dice:1d20+8|noform|noparens|text(+8) to hit,\
      \ reach 10 ft., one target. Hit: dice:1d4+4|noform|noparens|avg|text(6)\
      \ (1d4 + 4) slashing damage."
    "name": "Whip"
  - "desc": "Ranged Weapon Attack: dice:1d20+8|noform|noparens|text(+8) to hit,\
      \ range 30/120 ft., one target. Hit: dice:1d6+4|noform|noparens|avg|text(7)\
      \ (1d6 + 4) piercing damage, and the target must succeed on a DC 13 Constitution\
      \ saving throw or be [poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned)\
      \ for 1 hour. If the saving throw fails by 5 or more, the target is also [unconscious](І\
      нструменти%20ДМ/CLI/rules/conditions.md#Unconscious) while [poisoned](Інстру\
      менти%20ДМ/CLI/rules/conditions.md#Poisoned) in this way. The target regains\
      \ consciousness if it takes damage or if another creature takes an action to\
      \ shake it."
    "name": "Hand Crossbow"
  - "desc": "The drow casts one of the following spells, requiring no material components\
      \ and using Charisma as the spellcasting ability (spell save DC 13):\n\nAt\
      \ will: [dancing lights](Інструменти%20ДМ/CLI/spells/dancing-lights-xphb.md)\n\
      \n1/day each: [darkness](Інструменти%20ДМ/CLI/spells/darkness-xphb.md),\
      \ [faerie fire](Інструменти%20ДМ/CLI/spells/faerie-fire-xphb.md), [levitate](І\
      нструменти%20ДМ/CLI/spells/levitate-xphb.md) (self only)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Choose one creature within 30 feet of the drow that the drow can see.\
      \ If the chosen creature can see or hear the drow, that creature can use its\
      \ reaction to make one melee attack or to take the [Dodge](Інструменти%20ДМ\
      /CLI/rules/actions.md#Dodge) or [Hide](Інструменти%20ДМ/CLI/rules/actions.md#Hide)\
      \ action."
    "name": "Battle Command"
"reactions":
  - "desc": "The drow adds 3 to its AC against one melee attack roll that would hit\
      \ it. To do so, the drow must see the attacker and be wielding a melee weapon."
    "name": "Parry"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/drow-house-captain-mpmm.webp"
```
^statblock

## Environment

underdark