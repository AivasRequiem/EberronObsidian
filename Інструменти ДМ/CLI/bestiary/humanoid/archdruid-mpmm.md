---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/underwater
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/druid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Archdruid
---
# [Archdruid](Інструменти ДМ\CLI\bestiary\humanoid/archdruid-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 48*  

Archdruids watch over the natural wonders of their domains. They seldom interact with folk away from their druid groves and shrines, unless there is a great threat to the natural order or to a nearby community. An archdruid typically has one or more pupils who are [druids](Інструменти%20ДМ/CLI/bestiary/humanoid/druid-xmm.md), and the archdruid's lair is usually guarded by loyal Beasts and Fey creatures.

When an archdruid uses their Change Shape action, you may choose the creature they turn into, abiding by the action's restrictions. Or you may roll on the Archdruid Favored Shapes table to determine the form the archdruid adopts.

**Archdruid Favored Shapes**

`dice: [](archdruid-mpmm.md#^archdruid-favored-shapes)`

| dice: d8 | Favored Shape |
|----------|---------------|
| 1 | [Air elemental](Інструменти%20ДМ/CLI/bestiary/elemental/air-elemental-xmm.md) |
| 2 | [Earth elemental](Інструменти%20ДМ/CLI/bestiary/elemental/earth-elemental-xmm.md) |
| 3 | [Fire elemental](Інструменти%20ДМ/CLI/bestiary/elemental/fire-elemental-xmm.md) |
| 4 | [Giant crocodile](Інструменти%20ДМ/CLI/bestiary/beast/giant-crocodile-xmm.md) |
| 5 | [Mammoth](Інструменти%20ДМ/CLI/bestiary/beast/mammoth-xmm.md) |
| 6 | [Flail snail](Інструменти%20ДМ/CLI/bestiary/elemental/flail-snail-mpmm.md) |
| 7 | [Triceratops](Інструменти%20ДМ/CLI/bestiary/beast/triceratops-xmm.md) |
| 8 | [Water elemental](Інструменти%20ДМ/CLI/bestiary/elemental/water-elemental-xmm.md) |
^archdruid-favored-shapes

```statblock
"name": "Archdruid (MPMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "druid"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[hide armor](Інструменти%20ДМ/CLI/items/hide-armor-xphb.md)"
"hp": !!int "154"
"hit_dice": "28d8 + 28"
"modifier": !!int "2"
"stats":
  - !!int "14"
  - !!int "14"
  - !!int "12"
  - !!int "12"
  - !!int "20"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": "+5"
  - "wisdom": "+9"
"skillsaves":
  - "name": "[Medicine](Інструменти%20ДМ/CLI/rules/skills.md#Medicine)"
    "desc": "+9"
  - "name": "[Nature](Інструменти%20ДМ/CLI/rules/skills.md#Nature)"
    "desc": "+5"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+9"
"senses": "passive Perception 19"
"languages": "Druidic plus any two languages"
"cr": "12"
"actions":
  - "desc": "The archdruid makes three Staff or Wildfire attacks. It can replace one\
      \ attack with a use of Spellcasting."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 5\
      \ (1d6 + 2) bludgeoning damage plus 21 (6d6) poison damage."
    "name": "Staff"
  - "desc": "Ranged Spell Attack: +9 to hit, range 120 ft., one target. Hit:\
      \ 26 (6d6 + 5) fire damage, and the target is [blinded](Інструменти%20ДМ/CLI/rules/conditions.md#Blinded)\
      \ until the start of the druid's next turn."
    "name": "Wildfire"
  - "desc": "The archdruid casts one of the following spells, using Wisdom as the\
      \ spellcasting ability (spell save DC 17):\n\nAt will: [beast sense](Інс\
      трументи%20ДМ/CLI/spells/beast-sense-xphb.md), [entangle](Інструменти%20ДМ/CLI/spells/entangle-xphb.md),\
      \ [speak with animals](Інструменти%20ДМ/CLI/spells/speak-with-animals-xphb.md)\n\
      \n3/day each: [animal messenger](Інструменти%20ДМ/CLI/spells/animal-messenger-xphb.md),\
      \ [dominate beast](Інструменти%20ДМ/CLI/spells/dominate-beast-xphb.md), [faerie\
      \ fire](Інструменти%20ДМ/CLI/spells/faerie-fire-xphb.md), [tree stride](Інст\
      рументи%20ДМ/CLI/spells/tree-stride-xphb.md)\n\n1/day each: [commune with\
      \ nature](Інструменти%20ДМ/CLI/spells/commune-with-nature-xphb.md) (as an action),\
      \ [mass cure wounds](Інструменти%20ДМ/CLI/spells/mass-cure-wounds-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The archdruid magically transforms into a Beast or an Elemental with\
      \ a challenge rating of 6 or less and can remain in that form for up to 9 hours.\
      \ The archdruid can choose whether its equipment falls to the ground, melds\
      \ with its new form, or is worn by the new form. The archdruid reverts to its\
      \ true form if it dies or falls [unconscious](Інструменти%20ДМ/CLI/rules/conditions.md#Unconscious).\
      \ The archdruid can revert to its true form using a bonus action.\n\nWhile in\
      \ a new form, the archdruid's stat block is replaced by the stat block of that\
      \ form, except the archdruid keeps its current hit points, its hit point maximum,\
      \ this bonus action, its languages and ability to speak, and its Spellcasting\
      \ action.\n\nThe new form's attacks count as magical for the purpose of overcoming\
      \ resistances and immunity to nonmagical attacks."
    "name": "Change Shape (2/Day)"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/archdruid-mpmm.webp"
```
^statblock

## Environment

forest, mountain, swamp, underwater