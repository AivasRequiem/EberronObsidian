---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant
statblock: inline
statblock-link: "#^statblock"
aliases:
- Cyclops Oracle
---
# [Cyclops Oracle](Інструменти ДМ\CLI\bestiary\giant/cyclops-oracle-xmm.md)
*Source: Monster Manual (2024) p. 88*  

Cyclops oracles gaze through history to learn hidden truths. Many share these secrets with those who aid them in correcting the mistakes of the past.

## Cyclopes

*Monocular Servants of Destiny*

- **Habitat.** Coastal, Desert, Grassland, Hill, Mountain, Underdark  
- **Treasure.** Armaments  

Cyclopes are gigantic, one-eyed descendants of the gods. Using their mystical vision, cyclopes can witness how future events are likely to occur.

```statblock
"name": "Cyclops Oracle (XMM)"
"size": "Huge"
"type": "giant"
"alignment": "Chaotic Neutral"
"ac": !!int "16"
"hp": !!int "207"
"hit_dice": "18d12 + 90"
"modifier": !!int "8"
"stats":
  - !!int "22"
  - !!int "11"
  - !!int "20"
  - !!int "16"
  - !!int "18"
  - !!int "10"
"speed": "40 ft."
"saves":
  - "constitution": "+9"
  - "wisdom": "+8"
"skillsaves":
  - "name": "[History](Інструменти%20ДМ/CLI/rules/skills.md#History)"
    "desc": "+11"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+12"
"senses": "truesight 30 ft., passive Perception 22"
"languages": "Giant"
"cr": "10"
"actions":
  - "desc": "The cyclops makes three attacks, using Radiant Strike or Flash of Light\
      \ in any combination."
    "name": "Multiattack"
  - "desc": "Melee Attack Roll: +10, reach 10 ft. Hit: 22 (3d10 + 6) Radiant\
      \ damage."
    "name": "Radiant Strike"
  - "desc": "Ranged Attack Roll: +10, range 120 ft. Hit: 17 (2d10 + 6) Radiant\
      \ damage, and the target has [Disadvantage](Інструменти%20ДМ/CLI/rules/variant-rules/disadvantage-xphb.md)\
      \ on attack rolls until the end of the cyclops's next turn."
    "name": "Flash of Light"
  - "desc": "The cyclops casts one of the following spells, requiring no Material\
      \ components and using Wisdom as the spellcasting ability (spell save DC 16):\n\
      \n2/day each: [Arcane Eye](Інструменти%20ДМ/CLI/spells/arcane-eye-xphb.md),\
      \ [Detect Magic](Інструменти%20ДМ/CLI/spells/detect-magic-xphb.md), [Locate\
      \ Object](Інструменти%20ДМ/CLI/spells/locate-object-xphb.md)\n\n1/day: [Legend\
      \ Lore](Інструменти%20ДМ/CLI/spells/legend-lore-xphb.md)"
    "name": "Spellcasting"
"reactions":
  - "desc": "Trigger: The cyclops or an ally it can see makes a [D20 Test](Інструм\
      енти%20ДМ/CLI/rules/variant-rules/d20-test-xphb.md). _Response:_ The cyclops\
      \ rolls d20 and chooses whether to use that roll in place of the d20 rolled\
      \ for the [D20 Test](Інструменти%20ДМ/CLI/rules/variant-rules/d20-test-xphb.md)."
    "name": "Portent (Recharge 4-6)"
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/giant/token/cyclops-oracle-xmm.webp"
```
^statblock

## Environment

coastal, desert, grassland, hill, mountain, underdark