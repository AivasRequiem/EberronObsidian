---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Enchanter Wizard
---
# [Enchanter Wizard](Інструменти ДМ\CLI\bestiary\humanoid/enchanter-wizard-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 261*  

Enchanters know how to magically influence minds. Benign enchanters use this magic to defuse violence and sow peace, while malevolent enchanters are some of the most evil of all spellcasters.

## Wizards

Wizards pursue magical power through the study of arcane texts. Some travel the world searching for esoteric tomes while others train lesser wizards or collaborate with colleagues to create new spells.

```statblock
"name": "Enchanter Wizard (MPMM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](Інструменти%20ДМ/CLI/spells/mage-armor-xphb.md)"
"hp": !!int "49"
"hit_dice": "11d8"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "11"
  - !!int "17"
  - !!int "12"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": "+6"
  - "wisdom": "+4"
"skillsaves":
  - "name": "[Arcana](Інструменти%20ДМ/CLI/rules/skills.md#Arcana)"
    "desc": "+6"
  - "name": "[History](Інструменти%20ДМ/CLI/rules/skills.md#History)"
    "desc": "+6"
"senses": "passive Perception 11"
"languages": "any four languages"
"cr": "5"
"actions":
  - "desc": "The enchanter makes three Arcane Burst attacks."
    "name": "Multiattack"
  - "desc": "Melee  or Ranged Spell Attack: +6 to hit, reach 5 ft. or range 120\
      \ ft., one target. Hit: 19 (3d10 + 3) psychic damage."
    "name": "Arcane Burst"
  - "desc": "The enchanter casts one of the following spells, using Intelligence as\
      \ the spellcasting ability (spell save DC 14):\n\nAt will: [friends](Інс\
      трументи%20ДМ/CLI/spells/friends-xphb.md), [mage hand](Інструменти%20ДМ/CLI/spells/mage-hand-xphb.md),\
      \ [message](Інструменти%20ДМ/CLI/spells/message-xphb.md)\n\n2/day each:\
      \ [charm person](Інструменти%20ДМ/CLI/spells/charm-person-xphb.md), [mage armor](І\
      нструменти%20ДМ/CLI/spells/mage-armor-xphb.md), [hold person](Інструменти%20Д\
      М/CLI/spells/hold-person-xphb.md), [invisibility](Інструменти%20ДМ/CLI/spells/invisibility-xphb.md),\
      \ [suggestion](Інструменти%20ДМ/CLI/spells/suggestion-xphb.md), [tongues](Ін\
      струменти%20ДМ/CLI/spells/tongues-xphb.md)"
    "name": "Spellcasting"
"reactions":
  - "desc": "When a visible creature within 30 feet of the enchanter makes an attack\
      \ roll against it, the enchanter forces the attacker to make a DC 14 Wisdom\
      \ saving throw. On a failed save, the attacker redirects the attack roll to\
      \ the creature closest to it, other than the enchanter or itself. If multiple\
      \ eligible creatures are closest, the attacker chooses which one to target."
    "name": "Instinctive Charm (Recharge 4-6)"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/enchanter-wizard-mpmm.webp"
```
^statblock

## Environment

urban