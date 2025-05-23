---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/14
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/cleric
- ttrpg-cli/monster/type/humanoid/elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- Drow Inquisitor
---
# [Drow Inquisitor](Інструменти ДМ\CLI\bestiary\humanoid/drow-inquisitor-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 102*  

Lolth's worshipers expect treachery—the Spider Queen encourages it, after all. A certain amount of backstabbing and double-crossing can be managed, but too much can undermine an entire community. To keep some semblance of order and to root out traitors, priestesses of Lolth employ inquisitors. Inquisitors are chosen from the ranks of the priesthood, and their authority is equaled only by that of the [drow matron mothers](Інструменти%20ДМ/CLI/bestiary/humanoid/drow-matron-mother-mpmm.md) (also in this book) of the noble houses. Anyone they decide is at odds with the hierarchy faces painful interrogation and usually an excruciating death.

```statblock
"name": "Drow Inquisitor (MPMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "cleric, elf"
"alignment": "Typically  Neutral Evil"
"ac": !!int "16"
"ac_class": "[breastplate](Інструменти%20ДМ/CLI/items/breastplate-xphb.md)"
"hp": !!int "149"
"hit_dice": "23d8 + 46"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "15"
  - !!int "14"
  - !!int "16"
  - !!int "21"
  - !!int "20"
"speed": "30 ft."
"saves":
  - "constitution": "+7"
  - "wisdom": "+10"
  - "charisma": "+10"
"skillsaves":
  - "name": "[Insight](Інструменти%20ДМ/CLI/rules/skills.md#Insight)"
    "desc": "+10"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+10"
  - "name": "[Religion](Інструменти%20ДМ/CLI/rules/skills.md#Religion)"
    "desc": "+8"
  - "name": "[Stealth](Інструменти%20ДМ/CLI/rules/skills.md#Stealth)"
    "desc": "+7"
"condition_immunities": "[frightened](Інструменти%20ДМ/CLI/rules/conditions.md#Frightened)"
"senses": "darkvision 120 ft., passive Perception 20"
"languages": "Elvish, Undercommon"
"cr": "14"
"traits":
  - "desc": "The drow discerns when a creature in earshot speaks a lie in a language\
      \ the drow knows."
    "name": "Discern Lie"
  - "desc": "The drow has advantage on saving throws against being [charmed](Інстр\
      ументи%20ДМ/CLI/rules/conditions.md#Charmed), and magic can't put the drow to\
      \ sleep."
    "name": "Fey Ancestry"
  - "desc": "While in sunlight, the drow has disadvantage on attack rolls, as well\
      \ as on Wisdom ([Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception))\
      \ checks that rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "The drow makes three Death Lance attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit:\
      \ 8 (1d6 + 5) piercing damage plus 18 (4d8) necrotic damage. The target's\
      \ hit point maximum is reduced by an amount equal to the necrotic damage taken.\
      \ This reduction lasts until the target finishes a long rest. The target dies\
      \ if its hit point maximum is reduced to 0."
    "name": "Death Lance"
  - "desc": "The drow's casts one of the following spells, requiring no material components\
      \ and using Charisma as the spellcasting ability (spell save DC 18):\n\nAt\
      \ will: [dancing lights](Інструменти%20ДМ/CLI/spells/dancing-lights-xphb.md),\
      \ [detect magic](Інструменти%20ДМ/CLI/spells/detect-magic-xphb.md), [message](І\
      нструменти%20ДМ/CLI/spells/message-xphb.md), [thaumaturgy](Інструменти%20ДМ\
      /CLI/spells/thaumaturgy-xphb.md)\n\n1/day each: [clairvoyance](Інструмен\
      ти%20ДМ/CLI/spells/clairvoyance-xphb.md), [darkness](Інструменти%20ДМ/CLI/spells/darkness-xphb.md),\
      \ [detect thoughts](Інструменти%20ДМ/CLI/spells/detect-thoughts-xphb.md), [dispel\
      \ magic](Інструменти%20ДМ/CLI/spells/dispel-magic-xphb.md), [faerie fire](Ін\
      струменти%20ДМ/CLI/spells/faerie-fire-xphb.md), [levitate](Інструменти%20ДМ\
      /CLI/spells/levitate-xphb.md) (self only), [silence](Інструменти%20ДМ/CLI/spells/silence-xphb.md),\
      \ [suggestion](Інструменти%20ДМ/CLI/spells/suggestion-xphb.md), [true seeing](І\
      нструменти%20ДМ/CLI/spells/true-seeing-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The drow conjures a floating, spectral dagger within 60 feet of itself.\
      \ The drow can make a melee spell attack (+10 to hit) against one creature\
      \ within 5 feet of the dagger. On a hit, the target takes 9 (1d8 + 5) force\
      \ damage.\n\nThe dagger lasts for 1 minute. As a bonus action on later turns,\
      \ the drow can move the dagger up to 20 feet and repeat the attack against one\
      \ creature within 5 feet of the dagger."
    "name": "Spectral Dagger (Recharges after a Short or Long Rest)"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/drow-inquisitor-mpmm.webp"
```
^statblock

## Environment

underdark