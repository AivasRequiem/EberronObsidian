---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Tortle Druid
---
# [Tortle Druid](Інструменти ДМ\CLI\bestiary\humanoid/tortle-druid-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 244*  

Many tortles view the world as a place of wonder. They live for the chance to hear a soft wind blowing through trees, to watch a frog croaking on a lily pad, or to stand in a crowded marketplace. A tortle druid savors such things more than most, channeling the natural magic of the world around them.

## Tortles

Tortles are omnivorous, turtle-like bipeds with shells that cover most of their bodies. Because they carry their homes on their backs, tortles feel little need to stay put for long.

Most tortles like to see how other folk live. A tortle can spend decades away from their native land without feeling homesick, often viewing their current companions as their family.

```statblock
"name": "Tortle Druid (MPMM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"modifier": !!int "0"
"stats":
  - !!int "14"
  - !!int "10"
  - !!int "12"
  - !!int "11"
  - !!int "15"
  - !!int "12"
"speed": "30 ft."
"skillsaves":
  - "name": "[Animal Handling](Інструменти%20ДМ/CLI/rules/skills.md#Animal%20Handling)"
    "desc": "+4"
  - "name": "[Nature](Інструменти%20ДМ/CLI/rules/skills.md#Nature)"
    "desc": "+2"
  - "name": "[Survival](Інструменти%20ДМ/CLI/rules/skills.md#Survival)"
    "desc": "+4"
"senses": "passive Perception 12"
"languages": "Aquan, Common"
"cr": "2"
"traits":
  - "desc": "The tortle can hold its breath for 1 hour."
    "name": "Hold Breath"
"actions":
  - "desc": "The tortle makes four Claw attacks or two [Nature](Інструменти%20ДМ/CLI/rules/skills.md#Nature)'s\
      \ Wrath attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4\
      \ (1d4 + 2) slashing damage."
    "name": "Claw"
  - "desc": "Ranged Spell Attack: +4 to hit, range 90 ft., one target. Hit:\
      \ 9 (2d6 + 2) damage of a type chosen by the tortle: cold, fire, lightning,\
      \ or thunder."
    "name": "Nature's Wrath"
  - "desc": "The tortle withdraws into its shell. Until it emerges, it gains a +4\
      \ bonus to AC and has advantage on Strength and Constitution saving throws.\
      \ While in its shell, the tortle is [prone](Інструменти%20ДМ/CLI/rules/conditions.md#Prone),\
      \ its speed is 0 and can't increase, it has disadvantage on Dexterity saving\
      \ throws, it can't take reactions, and the only action it can take is a bonus\
      \ action to emerge."
    "name": "Shell Defense"
  - "desc": "The tortle casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 12):\n\nAt will: [druidcraft](Інструменти%20ДМ\
      /CLI/spells/druidcraft-xphb.md), [guidance](Інструменти%20ДМ/CLI/spells/guidance-xphb.md)\n\
      \n2/day each: [cure wounds](Інструменти%20ДМ/CLI/spells/cure-wounds-xphb.md),\
      \ [hold person](Інструменти%20ДМ/CLI/spells/hold-person-xphb.md), [speak with\
      \ animals](Інструменти%20ДМ/CLI/spells/speak-with-animals-xphb.md), [thunderwave](І\
      нструменти%20ДМ/CLI/spells/thunderwave-xphb.md)"
    "name": "Spellcasting"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/tortle-druid-mpmm.webp"
```
^statblock

## Environment

coastal