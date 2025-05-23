---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/environment/arctic
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Warlock of the Archfey
---
# [Warlock of the Archfey](Інструменти ДМ\CLI\bestiary\humanoid/warlock-of-the-archfey-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 255*  

Warlocks of the Archfey gain their powers through magical pacts forged with lords of the Feywild. These warlocks commonly associate with lesser Fey creatures such as [boggles](Інструменти%20ДМ/CLI/bestiary/fey/boggle-mpmm.md), [quicklings](Інструменти%20ДМ/CLI/bestiary/fey/quickling-mpmm.md), and [redcaps](Інструменти%20ДМ/CLI/bestiary/fey/redcap-mpmm.md) (all appear in "this book") or even [satyrs](Інструменти%20ДМ/CLI/bestiary/fey/satyr-xmm.md) and [sprites](Інструменти%20ДМ/CLI/bestiary/fey/sprite-xmm.md).

## Warlocks

Warlocks gain arcane might through magical pacts with mysterious entities. While some use their abilities to serve the sources of their power, others use them to undermine or even destroy these entities.

```statblock
"name": "Warlock of the Archfey (MPMM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "16 with [mage armor](Інструменти%20ДМ/CLI/spells/mage-armor-xphb.md)"
"hp": !!int "67"
"hit_dice": "15d8"
"modifier": !!int "3"
"stats":
  - !!int "9"
  - !!int "16"
  - !!int "11"
  - !!int "11"
  - !!int "12"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "wisdom": "+3"
  - "charisma": "+6"
"skillsaves":
  - "name": "[Arcana](Інструменти%20ДМ/CLI/rules/skills.md#Arcana)"
    "desc": "+2"
  - "name": "[Deception](Інструменти%20ДМ/CLI/rules/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Nature](Інструменти%20ДМ/CLI/rules/skills.md#Nature)"
    "desc": "+2"
  - "name": "[Persuasion](Інструменти%20ДМ/CLI/rules/skills.md#Persuasion)"
    "desc": "+6"
"condition_immunities": "[charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed)"
"senses": "passive Perception 11"
"languages": "any two languages (usually Sylvan)"
"cr": "4"
"actions":
  - "desc": "The warlock makes two Rapier attacks, or it uses Bewildering Word twice."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7\
      \ (1d8 + 3) piercing damage plus 7 (2d6) force damage."
    "name": "Rapier"
  - "desc": "The warlock utters a magical bewilderment, targeting one creature it\
      \ can see within 60 feet of it. The target must succeed on a DC 14 Wisdom saving\
      \ throw or take 9 (2d8) psychic damage and have disadvantage on attack rolls\
      \ until the end of the warlock's next turn."
    "name": "Bewildering Word"
  - "desc": "The warlock casts one of the following spells, using Charisma as the\
      \ spellcasting ability (spell save DC 14): \n\nAt will: [dancing lights](І\
      нструменти%20ДМ/CLI/spells/dancing-lights-xphb.md), [disguise self](Інструме\
      нти%20ДМ/CLI/spells/disguise-self-xphb.md), [mage armor](Інструменти%20ДМ/CLI/spells/mage-armor-xphb.md)\
      \ (self only), [mage hand](Інструменти%20ДМ/CLI/spells/mage-hand-xphb.md), [minor\
      \ illusion](Інструменти%20ДМ/CLI/spells/minor-illusion-xphb.md), [prestidigitation](І\
      нструменти%20ДМ/CLI/spells/prestidigitation-xphb.md), [speak with animals](І\
      нструменти%20ДМ/CLI/spells/speak-with-animals-xphb.md)\n\n1/day each: [charm\
      \ person](Інструменти%20ДМ/CLI/spells/charm-person-xphb.md), [dimension door](І\
      нструменти%20ДМ/CLI/spells/dimension-door-xphb.md), [hold monster](Інструмен\
      ти%20ДМ/CLI/spells/hold-monster-xphb.md)"
    "name": "Spellcasting"
"reactions":
  - "desc": "In response to taking damage, the warlock turns [invisible](Інструмен\
      ти%20ДМ/CLI/rules/conditions.md#Invisible) and teleports, along with any equipment\
      \ it is wearing or carrying, up to 60 feet to an unoccupied space it can see.\
      \ It remains [invisible](Інструменти%20ДМ/CLI/rules/conditions.md#Invisible)\
      \ until the start of its next turn or until it attacks, makes a damage roll,\
      \ or casts a spell."
    "name": "Misty Escape (Recharges after a Short or Long Rest)"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/warlock-of-the-archfey-mpmm.webp"
```
^statblock

## Environment

arctic, forest, mountain, swamp, urban