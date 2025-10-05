---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- Xvart Warlock of Raxivort
---
# [Xvart Warlock of Raxivort](Інструменти ДМ\CLI\bestiary\monstrosity/xvart-warlock-of-raxivort-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 267*  

Some xvarts are spawned with a trace of Raxivort's divine energy. These xvarts usually form a pact with him and wield magic in his service as warlocks.

## Xvarts

Xvarts are cowardly, greedy creatures spawned by a renegade demigod, Raxivort. They have blue skin, orange eyes, and receding hairlines, mirroring their creator's appearance. They stand about 3 feet tall.

Raxivort spent centuries watching over the treasury of Graz'zt, and in time, Raxivort plundered his lord's vault. One of the treasures he stole was the *Infinity Spindle*, a crystalline shard that could transform even a creature as lowly as Raxivort into a demigod. After his apotheosis, Raxivort forged the Black Sewers, a realm within Pandemonium that he filled with his beloved creatures, rats and bats, which xvarts befriend to this day. He enjoyed his reign only briefly before Graz'zt unleashed his vengeance. The demon prince urged villains far and wide to pursue the Infinity Spindle for themselves and destroy Raxivort.

```statblock
"name": "Xvart Warlock of Raxivort (MPMM)"
"size": "Small"
"type": "monstrosity"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "12"
"hp": !!int "22"
"hit_dice": "5d6 + 5"
"modifier": !!int "2"
"stats":
  - !!int "8"
  - !!int "14"
  - !!int "12"
  - !!int "8"
  - !!int "11"
  - !!int "12"
"speed": "30 ft."
"skillsaves":
  - "name": "[Stealth](Інструменти%20ДМ/CLI/rules/skills.md#Stealth)"
    "desc": "+3"
"senses": "darkvision 30 ft., passive Perception 10"
"languages": "Abyssal"
"cr": "1"
"traits":
  - "desc": "When the xvart reduces an enemy to 0 hit points, the xvart gains 4 temporary\
      \ hit points."
    "name": "Raxivort's Blessing"
  - "desc": "The xvart can communicate with ordinary [bats](Інструменти%20ДМ/CLI/bestiary/beast/bat-xmm.md)\
      \ and [rats](Інструменти%20ДМ/CLI/bestiary/beast/rat-xmm.md), as well as [giant\
      \ bats](Інструменти%20ДМ/CLI/bestiary/beast/giant-bat-xmm.md) and [giant rats](І\
      нструменти%20ДМ/CLI/bestiary/beast/giant-rat-xmm.md)."
    "name": "Raxivort's Tongue"
"actions":
  - "desc": "The xvart makes two Scimitar or Raxivort's Bite attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: dice:1d20+4|noform|noparens|text(+4) to hit,\
      \ reach 5 ft., one target. Hit: dice:1d6+2|noform|noparens|avg|text(5) (1d6\
      \ + 2) slashing damage."
    "name": "Scimitar"
  - "desc": "Ranged Spell Attack: dice:1d20+3|noform|noparens|text(+3) to hit,\
      \ range 30 ft., one creature. Hit: dice:1d10+2|noform|noparens|avg|text(7)\
      \ (1d10 + 2) poison damage."
    "name": "Raxivort's Bite"
  - "desc": "The xvart casts one of the following spells, requiring no material components\
      \ and using Charisma as the spellcasting ability (spell save DC 11):\n\nAt\
      \ will: [detect magic](Інструменти%20ДМ/CLI/spells/detect-magic-xphb.md),\
      \ [mage armor](Інструменти%20ДМ/CLI/spells/mage-armor-xphb.md) (self only),\
      \ [mage hand](Інструменти%20ДМ/CLI/spells/mage-hand-xphb.md), [minor illusion](І\
      нструменти%20ДМ/CLI/spells/minor-illusion-xphb.md), [prestidigitation](Інстр\
      ументи%20ДМ/CLI/spells/prestidigitation-xphb.md)\n\n1/day each: [burning\
      \ hands](Інструменти%20ДМ/CLI/spells/burning-hands-xphb.md), [invisibility](І\
      нструменти%20ДМ/CLI/spells/invisibility-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The xvart takes the [Disengage](Інструменти%20ДМ/CLI/rules/actions.md#Disengage)\
      \ action."
    "name": "Low Cunning"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/monstrosity/token/xvart-warlock-of-raxivort-mpmm.webp"
```
^statblock

## Environment

hill, underdark