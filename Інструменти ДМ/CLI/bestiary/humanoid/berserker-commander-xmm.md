---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Berserker Commander
---
# [Berserker Commander](Інструменти ДМ\CLI\bestiary\humanoid/berserker-commander-xmm.md)
*Source: Monster Manual (2024) p. 37*  

Berserker commanders bear the scars of battle and drive their followers to match their deadly zeal. These commanders tap into a primal magic to enhance their might.

## Berserkers

*Raging Invaders and Impassioned Warriors*

- **Habitat.** Any  
- **Treasure.** Armaments, Individual  

Gripped by the adrenaline of battle, berserkers are reckless invaders, pit fighters, and other ferocious warriors.

```statblock
"name": "Berserker Commander (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral"
"ac": !!int "16"
"hp": !!int "136"
"hit_dice": "16d8 + 64"
"modifier": !!int "5"
"stats":
  - !!int "19"
  - !!int "14"
  - !!int "19"
  - !!int "10"
  - !!int "14"
  - !!int "9"
"speed": "40 ft."
"saves":
  - "strength": "+7"
  - "constitution": "+7"
"skillsaves":
  - "name": "[Athletics](Інструменти%20ДМ/CLI/rules/skills.md#Athletics)"
    "desc": "+7"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+5"
"condition_immunities": "[charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed),\
  \ [frightened](Інструменти%20ДМ/CLI/rules/conditions.md#Frightened)"
"senses": "passive Perception 15"
"languages": "Common"
"cr": "8"
"traits":
  - "desc": "While [Bloodied](Інструменти%20ДМ/CLI/rules/variant-rules/bloodied-xphb.md),\
      \ the berserker has [Advantage](Інструменти%20ДМ/CLI/rules/variant-rules/advantage-xphb.md)\
      \ on attack rolls and saving throws."
    "name": "Bloodied Frenzy"
"actions":
  - "desc": "The berserker makes three attacks, using Greataxe or Javelin in any combination."
    "name": "Multiattack"
  - "desc": "Melee Attack Roll: +7, reach 5 ft. Hit: 10 (1d12 + 4) Slashing\
      \ damage, plus 10 (3d6) Thunder damage to the target or another creature within\
      \ 5 feet of the target."
    "name": "Greataxe"
  - "desc": "Melee  or Ranged Attack Roll: +7, reach 5 ft. or range 30/120 ft.\
      \ Hit: 18 (4d6 + 4) Piercing damage, and the target's [Speed](Інструмент\
      и%20ДМ/CLI/rules/variant-rules/speed-xphb.md) decreases by 5 feet until the\
      \ start of the berserker's next turn."
    "name": "Javelin"
"bonus_actions":
  - "desc": "Each ally within 30 feet of the berserker can take a [Reaction](Інстр\
      ументи%20ДМ/CLI/rules/variant-rules/reaction-xphb.md) to move up to half the\
      \ ally's [Speed](Інструменти%20ДМ/CLI/rules/variant-rules/speed-xphb.md) without\
      \ provoking Opportunity Attacks. The berserker can also move up to half its\
      \ [Speed](Інструменти%20ДМ/CLI/rules/variant-rules/speed-xphb.md) without provoking\
      \ Opportunity Attacks."
    "name": "Frenzied Rush"
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/berserker-commander-xmm.webp"
```
^statblock

## Environment

any