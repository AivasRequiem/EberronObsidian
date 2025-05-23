---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/environment/air
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- Aarakocra Aeromancer
---
# [Aarakocra Aeromancer](Інструменти ДМ\CLI\bestiary\elemental/aarakocra-aeromancer-xmm.md)
*Source: Monster Manual (2024) p. 10*  

Aarakocra aeromancers control magical winds from the endless storms of the Elemental Plane of Air.

## Aarakocra

*Winged Guardians of the Sky*

- **Habitat.** Mountain, Planar (Elemental Plane of Air)  
- **Treasure.** Implements, Individual  

Aarakocra are birdlike folk who soar the skies of countless worlds and the endless expanses of the Elemental Plane of Air. They often resemble avians common to the lands where they dwell; some resemble hawks or condors, while others appear similar to hummingbirds or archaeopteryxes. In many lands, aarakocra tell of their ancient heroics resisting the wicked Queen of Chaos alongside the mysterious Wind Dukes of Aaqa.

```statblock
"name": "Aarakocra Aeromancer (XMM)"
"size": "Medium"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "16"
"hp": !!int "66"
"hit_dice": "12d8 + 12"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "12"
  - !!int "13"
  - !!int "17"
  - !!int "12"
"speed": "20 ft., fly 50 ft."
"saves":
  - "dexterity": "+5"
  - "wisdom": "+5"
"skillsaves":
  - "name": "[Arcana](Інструменти%20ДМ/CLI/rules/skills.md#Arcana)"
    "desc": "+3"
  - "name": "[Nature](Інструменти%20ДМ/CLI/rules/skills.md#Nature)"
    "desc": "+5"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+7"
"senses": "passive Perception 17"
"languages": "Aarakocra, Primordial (Auran)"
"cr": "4"
"actions":
  - "desc": "The aarakocra makes two Wind Staff attacks, and it can use Spellcasting\
      \ to cast [Gust of Wind](Інструменти%20ДМ/CLI/spells/gust-of-wind-xphb.md)."
    "name": "Multiattack"
  - "desc": "Melee  or Ranged Attack Roll: +5, reach 5 ft. or range 120 ft. Hit:\
      \ 7 (1d8 + 3) Bludgeoning damage plus 11 (2d10) Lightning damage."
    "name": "Wind Staff"
  - "desc": "The aarakocra casts one of the following spells, requiring no Material\
      \ components and using Wisdom as the spellcasting ability (spell save DC 13):\n\
      \nAt will: [Elementalism](Інструменти%20ДМ/CLI/spells/elementalism-xphb.md),\
      \ [Gust of Wind](Інструменти%20ДМ/CLI/spells/gust-of-wind-xphb.md), [Mage Hand](І\
      нструменти%20ДМ/CLI/spells/mage-hand-xphb.md), [Message](Інструменти%20ДМ/CLI/spells/message-xphb.md)\n\
      \n1/day: [Lightning Bolt](Інструменти%20ДМ/CLI/spells/lightning-bolt-xphb.md)"
    "name": "Spellcasting"
  - "desc": "The aarakocra casts [Feather Fall](Інструменти%20ДМ/CLI/spells/feather-fall-xphb.md)\
      \ in response to that spell's trigger, using the same spellcasting ability as\
      \ Spellcasting.\n"
    "name": "Feather Fall (1/Day)"
"reactions":
  - "desc": "The aarakocra casts one of the following spells, requiring no Material\
      \ components and using Wisdom as the spellcasting ability (spell save DC 13):\n\
      \nAt will: [Elementalism](Інструменти%20ДМ/CLI/spells/elementalism-xphb.md),\
      \ [Gust of Wind](Інструменти%20ДМ/CLI/spells/gust-of-wind-xphb.md), [Mage Hand](І\
      нструменти%20ДМ/CLI/spells/mage-hand-xphb.md), [Message](Інструменти%20ДМ/CLI/spells/message-xphb.md)\n\
      \n1/day: [Lightning Bolt](Інструменти%20ДМ/CLI/spells/lightning-bolt-xphb.md)"
    "name": "Spellcasting"
  - "desc": "The aarakocra casts [Feather Fall](Інструменти%20ДМ/CLI/spells/feather-fall-xphb.md)\
      \ in response to that spell's trigger, using the same spellcasting ability as\
      \ Spellcasting.\n"
    "name": "Feather Fall (1/Day)"
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/elemental/token/aarakocra-aeromancer-xmm.webp"
```
^statblock

## Environment

mountain, planar, air