---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/environment/arctic
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- Giant Owl
---
# [Giant Owl](Інструменти ДМ\CLI\bestiary\celestial/giant-owl-xmm.md)
*Source: Monster Manual (2024) p. 358. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](Інструменти%20ДМ/CLI/bestiary/beast/panther-xmm.md) stat block can also represent a mountain lion, while the [Giant Goat](Інструменти%20ДМ/CLI/bestiary/beast/giant-goat-xmm.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Giant Owl (XMM)"
"size": "Large"
"type": "celestial"
"alignment": "Neutral"
"ac": !!int "12"
"hp": !!int "19"
"hit_dice": "3d10 + 3"
"modifier": !!int "2"
"stats":
  - !!int "13"
  - !!int "15"
  - !!int "12"
  - !!int "10"
  - !!int "14"
  - !!int "10"
"speed": "5 ft., fly 60 ft."
"saves":
  - "wisdom": "+4"
"skillsaves":
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Stealth](Інструменти%20ДМ/CLI/rules/skills.md#Stealth)"
    "desc": "+6"
"damage_resistances": "necrotic, radiant"
"senses": "darkvision 120 ft., passive Perception 16"
"languages": "Celestial; understands Common, Elvish, and Sylvan but can't speak them"
"cr": "1/4"
"traits":
  - "desc": "The owl doesn't provoke an Opportunity Attack when it flies out of an\
      \ enemy's reach."
    "name": "Flyby"
"actions":
  - "desc": "Melee Attack Roll: +4, reach 5 ft. Hit: 7 (1d10 + 2) Slashing\
      \ damage."
    "name": "Talons"
  - "desc": "The owl casts one of the following spells, requiring no spell components\
      \ and using Wisdom as the spellcasting ability:\n\nAt will: [Detect Evil\
      \ and Good](Інструменти%20ДМ/CLI/spells/detect-evil-and-good-xphb.md), [Detect\
      \ Magic](Інструменти%20ДМ/CLI/spells/detect-magic-xphb.md)\n\n1/day: [Clairvoyance](І\
      нструменти%20ДМ/CLI/spells/clairvoyance-xphb.md)"
    "name": "Spellcasting"
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/celestial/token/giant-owl-xmm.webp"
```
^statblock

## Environment

arctic, forest, hill