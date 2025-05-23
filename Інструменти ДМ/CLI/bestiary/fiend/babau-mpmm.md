---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
- Babau
---
# [Babau](Інструменти ДМ\CLI\bestiary\fiend/babau-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 52*  

> [!quote] A quote from Mordenkainen  
> 
> I'm unimpressed by most children. They are a blend of their ancestors but often more disappointing. You'd think two of the most beautiful, bloodthirsty beings of the Lower Planes would create a creature of greater potential. Instead, the ghastly babau fails to match the fiendish splendor of its parents.

Demons and devils clash endlessly for control of the Lower Planes. One of these battles pitted the legions of the archdevil Glasya against the screaming hordes of the demon lord Graz'zt. It is said that when Glasya wounded Graz'zt with her sword, the first babaus arose where his blood struck the ground. Their sudden appearance helped rout Glasya and secured Graz'zt's place as one of the preeminent demon lords of the Abyss.

A babau demon has the cunning of a devil and the bloodthirstiness of a demon. It has leathery skin pulled tight over its gaunt frame and a curved horn protruding from the back of its elongated skull. A babau's baleful glare can weaken a creature, and its talons gleam with acidic slime.

```statblock
"name": "Babau (MPMM)"
"size": "Medium"
"type": "fiend"
"subtype": "demon"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "82"
"hit_dice": "11d8 + 33"
"modifier": !!int "3"
"stats":
  - !!int "19"
  - !!int "16"
  - !!int "16"
  - !!int "11"
  - !!int "12"
  - !!int "13"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](Інструменти%20ДМ/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 15"
"languages": "Abyssal"
"cr": "4"
"actions":
  - "desc": "The babau makes two Claw attacks. It can replace one attack with a use\
      \ of Spellcasting or Weakening Gaze."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 6\
      \ (1d4 + 4) slashing damage plus 2 (d4) acid damage."
    "name": "Claw"
  - "desc": "The babau targets one creature that it can see within 20 feet of it.\
      \ The target must make a DC 13 Constitution saving throw. On a failed save,\
      \ the target deals only half damage with weapon attacks that use Strength for\
      \ 1 minute. The target can repeat the saving throw at the end of each of its\
      \ turns, ending the effect on itself on a success."
    "name": "Weakening Gaze"
  - "desc": "The babau casts one of the following spells, requiring no material components\
      \ and using Wisdom as the spellcasting ability (spell save DC 11):\n\nAt will:\
      \ [darkness](Інструменти%20ДМ/CLI/spells/darkness-xphb.md), [dispel magic](І\
      нструменти%20ДМ/CLI/spells/dispel-magic-xphb.md), [fear](Інструменти%20ДМ/CLI/spells/fear-xphb.md),\
      \ [heat metal](Інструменти%20ДМ/CLI/spells/heat-metal-xphb.md), [levitate](І\
      нструменти%20ДМ/CLI/spells/levitate-xphb.md)"
    "name": "Spellcasting"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/fiend/token/babau-mpmm.webp"
```
^statblock

## Environment

underdark, urban