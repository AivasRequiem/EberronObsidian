---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Necromancer Wizard
---
# [Necromancer Wizard](Інструменти ДМ\CLI\bestiary\humanoid/necromancer-wizard-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 264*  

Necromancers study the interaction of life, death, and undeath. Some necromancers dig up or purchase corpses to create Undead servitors. A few instead use their powers for good, hunting Undead.

## Wizards

Wizards pursue magical power through the study of arcane texts. Some travel the world searching for esoteric tomes while others train lesser wizards or collaborate with colleagues to create new spells.

```statblock
"name": "Necromancer Wizard (MPMM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](Інструменти%20ДМ/CLI/spells/mage-armor-xphb.md)"
"hp": !!int "110"
"hit_dice": "20d8 + 20"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "12"
  - !!int "17"
  - !!int "12"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "7"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "[Arcana](Інструменти%20ДМ/CLI/rules/skills.md#Arcana)"
    "desc": "+7"
  - "name": "[History](Інструменти%20ДМ/CLI/rules/skills.md#History)"
    "desc": "+7"
"damage_resistances": "necrotic"
"senses": "passive Perception 11"
"languages": "any four languages"
"cr": "9"
"actions":
  - "desc": "The necromancer makes three Arcane Burst attacks."
    "name": "Multiattack"
  - "desc": "Melee  or Ranged Spell Attack: dice:1d20+7|noform|noparens|text(+7)\
      \ to hit, reach 5 ft. or range 120 ft., one target. Hit: dice:4d10+3|noform|noparens|avg|text(25)\
      \ (4d10 + 3) necrotic damage."
    "name": "Arcane Burst"
  - "desc": "The necromancer casts one of the following spells, using Intelligence\
      \ as the spellcasting ability (spell save DC 15):\n\nAt will: [dancing lights](І\
      нструменти%20ДМ/CLI/spells/dancing-lights-xphb.md), [mage hand](Інструменти\
      %20ДМ/CLI/spells/mage-hand-xphb.md), [prestidigitation](Інструменти%20ДМ/CLI/spells/prestidigitation-xphb.md)\n\
      \n2/day each: [bestow curse](Інструменти%20ДМ/CLI/spells/bestow-curse-xphb.md),\
      \ [dimension door](Інструменти%20ДМ/CLI/spells/dimension-door-xphb.md), [mage\
      \ armor](Інструменти%20ДМ/CLI/spells/mage-armor-xphb.md), [web](Інструменти\
      %20ДМ/CLI/spells/web-xphb.md)\n\n1/day each: [circle of death](Інструмен\
      ти%20ДМ/CLI/spells/circle-of-death-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The necromancer magically summons five [skeletons](Інструменти%20ДМ/CLI/bestiary/undead/skeleton-xmm.md)\
      \ or [zombies](Інструменти%20ДМ/CLI/bestiary/undead/zombie-xmm.md). The summoned\
      \ creatures appear in unoccupied spaces within 60 feet of the necromancer, whom\
      \ they obey. They take their turns immediately after the necromancer. Each lasts\
      \ for 1 hour, until it or the necromancer dies, or until the necromancer dismisses\
      \ it as a bonus action."
    "name": "Summon Undead (1/Day)"
"reactions":
  - "desc": "When the necromancer kills a creature with necrotic damage, the necromancer\
      \ regains dice:2d8|noform|noparens|avg|text(9) (2d8) hit points. "
    "name": "Grim Harvest (1/Turn)"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/necromancer-wizard-mpmm.webp"
```
^statblock

## Environment

desert, urban