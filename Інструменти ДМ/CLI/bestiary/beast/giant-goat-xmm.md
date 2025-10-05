---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- Giant Goat
---
# [Giant Goat](Інструменти ДМ\CLI\bestiary\beast/giant-goat-xmm.md)
*Source: Monster Manual (2024) p. 357, Player's Handbook (2024) p. 350. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](Інструменти%20ДМ/CLI/bestiary/beast/panther-xmm.md) stat block can also represent a mountain lion, while the [Giant Goat](Інструменти%20ДМ/CLI/bestiary/beast/giant-goat-xmm.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Giant Goat (XMM)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "19"
"hit_dice": "3d10 + 3"
"modifier": !!int "1"
"stats":
  - !!int "17"
  - !!int "13"
  - !!int "12"
  - !!int "3"
  - !!int "12"
  - !!int "6"
"speed": "40 ft., climb 30 ft."
"saves":
  - "strength": !!int "5"
"skillsaves":
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+3"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": ""
"cr": "1/2"
"actions":
  - "desc": "Melee Attack Roll: dice:1d20+5|noform|noparens|text(+5), reach 5\
      \ ft. Hit: dice:1d6+3|noform|noparens|avg|text(6) (1d6 + 3) Bludgeoning\
      \ damage. If the target is a Large or smaller creature and the goat moved 20+\
      \ feet straight toward it immediately before the hit, the target takes an extra\
      \ dice:2d4|noform|noparens|avg|text(5) (2d4) Bludgeoning damage and has\
      \ the [Prone](Інструменти%20ДМ/CLI/rules/conditions.md#Prone) condition."
    "name": "Ram"
"source":
  - "XMM"
  - "XPHB"
"image": "Інструменти%20ДМ/CLI/bestiary/beast/token/giant-goat-xmm.webp"
```
^statblock

## Environment

grassland, hill, mountain