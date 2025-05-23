---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/18
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/elf
- ttrpg-cli/monster/type/humanoid/wizard
statblock: inline
statblock-link: "#^statblock"
aliases:
- Drow Favored Consort
---
# [Drow Favored Consort](Інструменти ДМ\CLI\bestiary\humanoid/drow-favored-consort-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 100*  

Nearly every priestess of Lolth, including the powerful [drow matron mother](Інструменти%20ДМ/CLI/bestiary/humanoid/drow-matron-mother-mpmm.md) in this book, takes an attractive drow as consort. Chosen as much for beauty as for magical might, a drow favored consort can hold their own in both conversation and combat. Combining the roles of advisor, protector, and beloved, some favored consorts are content with a supporting role, while more ambitious consorts aspire to be the power behind the throne—or even to claim the throne themselves.

Those favored consorts who prove their cunning gain the ear, and perhaps even the heart, of their priestess and are relied on to provide useful advice. No position of consort is assured for long, though; Lolth's priestesses are notoriously fickle, and a consort must often contend with rivals.

Some favored consorts work behind the scenes to undermine the evils encouraged by Lolth. Others can be found in Underdark cities free of Lolth's influence, where these powerful spellcasters apply their might toward ending her tyranny.

```statblock
"name": "Drow Favored Consort (MPMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf, wizard"
"alignment": "Any alignment"
"ac": !!int "15"
"hp": !!int "240"
"hit_dice": "32d8 + 96"
"modifier": !!int "5"
"stats":
  - !!int "15"
  - !!int "20"
  - !!int "16"
  - !!int "18"
  - !!int "15"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "dexterity": "+11"
  - "constitution": "+9"
  - "charisma": "+10"
"skillsaves":
  - "name": "[Acrobatics](Інструменти%20ДМ/CLI/rules/skills.md#Acrobatics)"
    "desc": "+11"
  - "name": "[Athletics](Інструменти%20ДМ/CLI/rules/skills.md#Athletics)"
    "desc": "+8"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+8"
  - "name": "[Stealth](Інструменти%20ДМ/CLI/rules/skills.md#Stealth)"
    "desc": "+11"
"senses": "darkvision 120 ft., passive Perception 18"
"languages": "Elvish, Undercommon"
"cr": "18"
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
  - "desc": "The drow makes three Scimitar or Arcane Eruption attacks. The drow can\
      \ replace one of the attacks with a use of Spellcasting."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +11 to hit, reach 5 ft., one target. Hit:\
      \ 8 (1d6 + 5) slashing damage plus 27 (6d8) poison damage."
    "name": "Scimitar"
  - "desc": "Ranged Spell Attack: +10 to hit, range 120 ft., one target. Hit:\
      \ 36 (8d8) force damage, and the drow can push the target up to 10 feet away\
      \ if it is a Large or smaller creature."
    "name": "Arcane Eruption"
  - "desc": "The drow casts one of the following spells, requiring no material components\
      \ and using Intelligence as the spellcasting ability (spell save DC 18):\n\n\
      At will: [dancing lights](Інструменти%20ДМ/CLI/spells/dancing-lights-xphb.md),\
      \ [mage armor](Інструменти%20ДМ/CLI/spells/mage-armor-xphb.md), [mage hand](І\
      нструменти%20ДМ/CLI/spells/mage-hand-xphb.md), [message](Інструменти%20ДМ/CLI/spells/message-xphb.md)\n\
      \n3/day each: [dimension door](Інструменти%20ДМ/CLI/spells/dimension-door-xphb.md),\
      \ [fireball](Інструменти%20ДМ/CLI/spells/fireball-xphb.md), [invisibility](І\
      нструменти%20ДМ/CLI/spells/invisibility-xphb.md)\n\n1/day each: [darkness](І\
      нструменти%20ДМ/CLI/spells/darkness-xphb.md), [faerie fire](Інструменти%20ДМ\
      /CLI/spells/faerie-fire-xphb.md), [levitate](Інструменти%20ДМ/CLI/spells/levitate-xphb.md)\
      \ (self only)"
    "name": "Spellcasting"
"reactions":
  - "desc": "When the drow or a creature within 10 feet of it is hit by an attack\
      \ roll, the drow gives the target a +5 bonus to its AC until the start of the\
      \ drow's next turn, which can cause the triggering attack roll to miss."
    "name": "Protective Shield (3/Day)"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/drow-favored-consort-mpmm.webp"
```
^statblock

## Environment

underdark