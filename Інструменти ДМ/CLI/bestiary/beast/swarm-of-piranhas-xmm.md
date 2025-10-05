---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/underwater
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- Swarm of Piranhas
---
# [Swarm of Piranhas](Інструменти ДМ\CLI\bestiary\beast/swarm-of-piranhas-xmm.md)
*Source: Monster Manual (2024) p. 370. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](Інструменти%20ДМ/CLI/bestiary/beast/panther-xmm.md) stat block can also represent a mountain lion, while the [Giant Goat](Інструменти%20ДМ/CLI/bestiary/beast/giant-goat-xmm.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Swarm of Piranhas (XMM)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "28"
"hit_dice": "8d8 - 8"
"modifier": !!int "3"
"stats":
  - !!int "13"
  - !!int "16"
  - !!int "9"
  - !!int "1"
  - !!int "7"
  - !!int "2"
"speed": "5 ft., swim 40 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed),\
  \ [frightened](Інструменти%20ДМ/CLI/rules/conditions.md#Frightened), [grappled](І\
  нструменти%20ДМ/CLI/rules/conditions.md#Grappled), [paralyzed](Інструменти%20ДМ\
  /CLI/rules/conditions.md#Paralyzed), [petrified](Інструменти%20ДМ/CLI/rules/conditions.md#Petrified),\
  \ [prone](Інструменти%20ДМ/CLI/rules/conditions.md#Prone), [restrained](Інструме\
  нти%20ДМ/CLI/rules/conditions.md#Restrained), [stunned](Інструменти%20ДМ/CLI/rules/conditions.md#Stunned)"
"senses": "darkvision 60 ft., passive Perception 8"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The swarm can occupy another creature's space and vice versa, and the\
      \ swarm can move through any opening large enough for a Tiny piranha. The swarm\
      \ can't regain [Hit Points](Інструменти%20ДМ/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ or gain [Temporary Hit Points](Інструменти%20ДМ/CLI/rules/variant-rules/temporary-hit-points-xphb.md)."
    "name": "Swarm"
  - "desc": "The swarm can breathe only underwater."
    "name": "Water Breathing"
"actions":
  - "desc": "Melee Attack Roll: dice:1d20+5|noform|noparens|text(+5) (with [Advantage](І\
      нструменти%20ДМ/CLI/rules/variant-rules/advantage-xphb.md) if the target doesn't\
      \ have all its [Hit Points](Інструменти%20ДМ/CLI/rules/variant-rules/hit-points-xphb.md)),\
      \ reach 5 ft. Hit: dice:2d4+3|noform|noparens|avg|text(8) (2d4 + 3) Piercing\
      \ damage, or dice:1d4+3|noform|noparens|avg|text(5) (1d4 + 3) Piercing damage\
      \ if the swarm is [Bloodied](Інструменти%20ДМ/CLI/rules/conditions.md#Bloodied)."
    "name": "Bites"
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/beast/token/swarm-of-piranhas-xmm.webp"
```
^statblock

## Environment

underwater