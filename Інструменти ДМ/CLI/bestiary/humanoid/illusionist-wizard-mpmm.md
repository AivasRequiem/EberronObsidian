---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Illusionist Wizard
---
# [Illusionist Wizard](Інструменти ДМ\CLI\bestiary\humanoid/illusionist-wizard-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 263*  

Illusionists twist light, sound, and even thought to create illusory effects. Some illusionists are delightful entertainers, while others are devilish tricksters.

## Wizards

Wizards pursue magical power through the study of arcane texts. Some travel the world searching for esoteric tomes while others train lesser wizards or collaborate with colleagues to create new spells.

```statblock
"name": "Illusionist Wizard (MPMM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](Інструменти%20ДМ/CLI/spells/mage-armor-xphb.md)"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "13"
  - !!int "16"
  - !!int "11"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "intelligence": "+5"
  - "wisdom": "+2"
"skillsaves":
  - "name": "[Arcana](Інструменти%20ДМ/CLI/rules/skills.md#Arcana)"
    "desc": "+5"
  - "name": "[History](Інструменти%20ДМ/CLI/rules/skills.md#History)"
    "desc": "+5"
"senses": "passive Perception 10"
"languages": "any four languages"
"cr": "3"
"actions":
  - "desc": "The illusionist makes two Arcane Burst attacks."
    "name": "Multiattack"
  - "desc": "Melee  or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 120\
      \ ft., one target. Hit: 14 (2d10 + 3) psychic damage."
    "name": "Arcane Burst"
  - "desc": "The illusionist casts one of the following spells, using Intelligence\
      \ as the spellcasting ability (spell save DC 13):\n\nAt will: [dancing lights](І\
      нструменти%20ДМ/CLI/spells/dancing-lights-xphb.md), [mage hand](Інструменти\
      %20ДМ/CLI/spells/mage-hand-xphb.md), [minor illusion](Інструменти%20ДМ/CLI/spells/minor-illusion-xphb.md)\n\
      \n2/day each: [disguise self](Інструменти%20ДМ/CLI/spells/disguise-self-xphb.md),\
      \ [invisibility](Інструменти%20ДМ/CLI/spells/invisibility-xphb.md), [mage armor](І\
      нструменти%20ДМ/CLI/spells/mage-armor-xphb.md), [major image](Інструменти%20Д\
      М/CLI/spells/major-image-xphb.md), [phantasmal force](Інструменти%20ДМ/CLI/spells/phantasmal-force-xphb.md),\
      \ [phantom steed](Інструменти%20ДМ/CLI/spells/phantom-steed-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The illusionist projects an illusion that makes the illusionist appear\
      \ to be standing in a place a few inches from its actual location, causing any\
      \ creature to have disadvantage on attack rolls against the illusionist. The\
      \ effect lasts for 1 minute, and it ends early if the illusionist takes damage,\
      \ if it is [incapacitated](Інструменти%20ДМ/CLI/rules/conditions.md#Incapacitated),\
      \ or if its speed becomes 0."
    "name": "Displacement (Recharge 5-6)"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/illusionist-wizard-mpmm.webp"
```
^statblock

## Environment

urban