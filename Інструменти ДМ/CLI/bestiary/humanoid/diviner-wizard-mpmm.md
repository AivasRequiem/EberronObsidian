---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Diviner Wizard
---
# [Diviner Wizard](Інструменти ДМ\CLI\bestiary\humanoid/diviner-wizard-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 261*  

Diviners peer into the future and know that knowledge is power. They might act aloof and mysterious, hinting at omens and secrets, or they might be know-it-alls, spilling insights to advance their own status.

## Wizards

Wizards pursue magical power through the study of arcane texts. Some travel the world searching for esoteric tomes while others train lesser wizards or collaborate with colleagues to create new spells.

```statblock
"name": "Diviner Wizard (MPMM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](Інструменти%20ДМ/CLI/spells/mage-armor-xphb.md)"
"hp": !!int "90"
"hit_dice": "20d8"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "11"
  - !!int "18"
  - !!int "12"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": "+7"
  - "wisdom": "+4"
"skillsaves":
  - "name": "[Arcana](Інструменти%20ДМ/CLI/rules/skills.md#Arcana)"
    "desc": "+7"
  - "name": "[History](Інструменти%20ДМ/CLI/rules/skills.md#History)"
    "desc": "+7"
"senses": "passive Perception 11"
"languages": "any four languages"
"cr": "8"
"actions":
  - "desc": "The diviner makes three Arcane Burst attacks."
    "name": "Multiattack"
  - "desc": "Melee  or Ranged Spell Attack: +7 to hit, reach 5 ft. or range 120\
      \ ft., one target. Hit: 20 (3d10 + 4) radiant damage."
    "name": "Arcane Burst"
  - "desc": "The diviner magically creates a burst of illumination in a 10-foot-radius\
      \ sphere centered on a point within 120 feet of it. Each creature in that area\
      \ must make a DC 15 Wisdom saving throw. On a failed save, a creature takes\
      \ 45 (10d8) psychic damage and is [stunned](Інструменти%20ДМ/CLI/rules/conditions.md#Stunned)\
      \ until the end of the diviner's next turn. On a successful save, the creature\
      \ takes half as much damage and isn't [stunned](Інструменти%20ДМ/CLI/rules/conditions.md#Stunned)."
    "name": "Overwhelming Revelation (Recharge 5-6)"
  - "desc": "The diviner casts one of the following spells, using Intelligence as\
      \ the spellcasting ability (spell save DC 15):\n\nAt will: [mage hand](І\
      нструменти%20ДМ/CLI/spells/mage-hand-xphb.md), [message](Інструменти%20ДМ/CLI/spells/message-xphb.md),\
      \ [prestidigitation](Інструменти%20ДМ/CLI/spells/prestidigitation-xphb.md)\n\
      \n2/day each: [arcane eye](Інструменти%20ДМ/CLI/spells/arcane-eye-xphb.md),\
      \ [detect magic](Інструменти%20ДМ/CLI/spells/detect-magic-xphb.md), [detect\
      \ thoughts](Інструменти%20ДМ/CLI/spells/detect-thoughts-xphb.md), [fly](Інст\
      рументи%20ДМ/CLI/spells/fly-xphb.md), [lightning bolt](Інструменти%20ДМ/CLI/spells/lightning-bolt-xphb.md),\
      \ [locate object](Інструменти%20ДМ/CLI/spells/locate-object-xphb.md), [mage\
      \ armor](Інструменти%20ДМ/CLI/spells/mage-armor-xphb.md), [Rary's telepathic\
      \ bond](Інструменти%20ДМ/CLI/spells/rarys-telepathic-bond-xphb.md)\n\n1/day\
      \ each: [true seeing](Інструменти%20ДМ/CLI/spells/true-seeing-xphb.md)"
    "name": "Spellcasting"
"reactions":
  - "desc": "When the diviner or a creature it can see makes an attack roll, a saving\
      \ throw, or an ability check, the diviner rolls a d20 and chooses whether\
      \ to use that roll in place of the d20 rolled for the attack roll, saving\
      \ throw, or ability check. "
    "name": "Portent (3/Day)"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/diviner-wizard-mpmm.webp"
```
^statblock

## Environment

urban