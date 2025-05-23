---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- Skulk
---
# [Skulk](Інструменти ДМ\CLI\bestiary\monstrosity/skulk-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 219*  

> [!quote] A quote from Mordenkainen  
> 
> Some children have imaginary friends that their parents can't see. Sometimes those invisible friends aren't imaginary.

Skulks are the soulless shells of travelers who became lost in the Shadowfell, wandering its gray wastes until they lost all sense of self. They are so devoid of identity that they have become permanently [invisible](Інструменти%20ДМ/CLI/rules/conditions.md#Invisible). Only children can see a skulk without the help of a mirror or a special candle. On the rare occasions when a skulk is visible, it appears as a drab, featureless, hairless biped.

A skulk can be summoned from the Shadowfell by performing a ritual, and it is bound to obey the summoner's commands for 30 days. During this time, if the skulk is visible, an astute observer might deduce who summoned it, because the skulk assumes a vague likeness of its master.

Cruel and chaotic, skulks carry out their orders in the most violent manner possible. A summoned skulk can't return to the Shadowfell until it dies, so many throw themselves into creating bloodshed and mayhem with no regard for their own lives. After killing a person on the Material Plane, some skulks take up a silent imitation of that person's life. In extreme cases, skulks have invaded villages, killed all the occupants, and turned the places into seeming ghost towns where flavorless food is prepared daily, colorless clothes are hung up to dry, and livestock is shifted from pen to pen until it starves.

```statblock
"name": "Skulk (MPMM)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Typically  Chaotic Neutral"
"ac": !!int "14"
"hp": !!int "18"
"hit_dice": "4d8"
"modifier": !!int "4"
"stats":
  - !!int "6"
  - !!int "19"
  - !!int "10"
  - !!int "10"
  - !!int "7"
  - !!int "1"
"speed": "30 ft."
"saves":
  - "constitution": "+2"
"skillsaves":
  - "name": "[Stealth](Інструменти%20ДМ/CLI/rules/skills.md#Stealth)"
    "desc": "+8"
"condition_immunities": "[blinded](Інструменти%20ДМ/CLI/rules/conditions.md#Blinded)"
"senses": "darkvision 120 ft., passive Perception 8"
"languages": "understands Common but can't speak"
"cr": "1/2"
"traits":
  - "desc": "The skulk is [invisible](Інструменти%20ДМ/CLI/rules/conditions.md#Invisible).\
      \ This invisibility can be circumvented by three things:\n\n- Charnel Candles.\
      \ The skulk appears as a dim, translucent form in the light of a candle made\
      \ of fat rendered from a corpse whose identity is unknown.  \n- Children.\
      \ Humanoid children, aged 10 and under, can see through this invisibility. \
      \ \n- Reflective Surfaces. The skulk appears as a drab, smoothskinned biped\
      \ if its reflection can be seen in a mirror or on another surface.  "
    "name": "Fallible Invisibility"
  - "desc": "The skulk leaves no tracks to indicate where it has been or where it's\
      \ headed."
    "name": "Trackless"
"actions":
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 6\
      \ (1d4 + 4) slashing damage plus 3 (d6) necrotic damage."
    "name": "Claw"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/monstrosity/token/skulk-mpmm.webp"
```
^statblock

## Environment

coastal, forest, swamp, underdark, urban