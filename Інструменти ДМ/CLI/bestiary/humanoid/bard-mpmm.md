---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Bard
---
# [Bard](Інструменти ДМ\CLI\bestiary\humanoid/bard-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 59*  

Bards are gifted poets, storytellers, and entertainers who travel far and wide. They're commonly found in taverns or in the company of jolly bands of adventurers, rough-and-tumble mercenaries, and wealthy patrons.

Each bard is a master of at least one type of performance. You may choose a bard's main type, or you may roll on the Bard [Performance](Інструменти%20ДМ/CLI/rules/skills.md#Performance) Types table to determine it.

**Bard Performance Types**

`dice: [](bard-mpmm.md#^bard-performance-types)`

| dice: d10 | Performance Type |
|-----------|------------------|
| 1 | Poetry |
| 2 | Singing |
| 3 | Bagpipe |
| 4 | Flute |
| 5 | Dancing |
| 6 | Drum |
| 7 | Lute |
| 8 | Puppetry |
| 9 | Mime |
| 10 | Acting |
^bard-performance-types

```statblock
"name": "Bard (MPMM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "[chain shirt](Інструменти%20ДМ/CLI/items/chain-shirt-xphb.md)"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "12"
  - !!int "10"
  - !!int "13"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "4"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "[Acrobatics](Інструменти%20ДМ/CLI/rules/skills.md#Acrobatics)"
    "desc": "+4"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Performance](Інструменти%20ДМ/CLI/rules/skills.md#Performance)"
    "desc": "+6"
"senses": "passive Perception 15"
"languages": "any two languages"
"cr": "2"
"actions":
  - "desc": "The bard makes two Shortsword or Shortbow attacks. It can replace one\
      \ attack with a use of Spellcasting."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: dice:1d20+4|noform|noparens|text(+4) to hit,\
      \ reach 5 ft., one target. Hit: dice:1d6+2|noform|noparens|avg|text(5) (1d6\
      \ + 2) piercing damage."
    "name": "Shortsword"
  - "desc": "Ranged Weapon Attack: dice:1d20+4|noform|noparens|text(+4) to hit,\
      \ range 80/320 ft., one target. Hit: dice:1d6+2|noform|noparens|avg|text(5)\
      \ (1d6 + 2) piercing damage."
    "name": "Shortbow"
  - "desc": "Each creature in a 15-foot cube originating from the bard must make a\
      \ DC 12 Constitution saving throw. On a failed save, a creature takes dice:2d8|noform|noparens|avg|text(9)\
      \ (2d8) thunder damage and is pushed up to 10 feet away from the bard. On\
      \ a successful save, a creature takes half as much damage and isn't pushed."
    "name": "Cacophony (Recharge 4-6)"
  - "desc": "The bard casts one of the following spells, using Charisma as the spellcasting\
      \ ability (spell save DC 12):\n\nAt will: [dancing lights](Інструменти%20Д\
      М/CLI/spells/dancing-lights-xphb.md), [mage hand](Інструменти%20ДМ/CLI/spells/mage-hand-xphb.md),\
      \ [prestidigitation](Інструменти%20ДМ/CLI/spells/prestidigitation-xphb.md)\n\
      \n1/day each: [charm person](Інструменти%20ДМ/CLI/spells/charm-person-xphb.md),\
      \ [invisibility](Інструменти%20ДМ/CLI/spells/invisibility-xphb.md), [sleep](І\
      нструменти%20ДМ/CLI/spells/sleep-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The bard targets one creature within 30 feet of it. If the target can\
      \ hear the bard, the target must succeed on a DC 12 Charisma saving throw or\
      \ have disadvantage on ability checks, attack rolls, and saving throws until\
      \ the start of the bard's next turn."
    "name": "Taunt (2/Day)"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/bard-mpmm.webp"
```
^statblock

## Environment

urban