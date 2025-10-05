---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/environment/earth
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental/genie
statblock: inline
statblock-link: "#^statblock"
aliases:
- Dao
---
# [Dao](Інструменти ДМ\CLI\bestiary\elemental/dao-xmm.md)
*Source: Monster Manual (2024) p. 89*  

## Dao

*Genie of the Earth*

- **Habitat.** Planar (Elemental Plane of Earth), Underdark  
- **Treasure.** Implements  

Genies of minerals and gemstones, dao embody the resolve of rock. Using innate magic, they move through the earth unimpeded, exploring depths inaccessible to most. Dao delight in the treasures of the earth, whether raw gemstones, jewelry crafted from pure metals, or wondrous fossils. In exchange for such treasures, dao might reveal underground mysteries, such as paths through the Underdark, buried ruins, or whole subterranean realms.

Many dao call the Elemental Plane of Earth home. There, they create cities that glitter with treasure. Among these realms is the labyrinthine expanse called the Great Dismal Delve or the Sevenfold Mazework, which protects the City of Jewels, the Iron Crucible, and the Strait of Magnets.

> [!quote] A quote from Gundren Rockseeker, Dwarf Treasure Hunter  
> 
> On the Elemental Plane of Earth, galaxies of gemstones twinkle over vaults of treasure. If dao are there, so is wealth worth hunting.


```statblock
"name": "Dao (XMM)"
"size": "Large"
"type": "elemental"
"subtype": "genie"
"alignment": "Neutral"
"ac": !!int "18"
"hp": !!int "200"
"hit_dice": "16d10 + 112"
"modifier": !!int "1"
"stats":
  - !!int "23"
  - !!int "12"
  - !!int "24"
  - !!int "12"
  - !!int "13"
  - !!int "18"
"speed": "30 ft., burrow 30 ft., fly 30 ft. (hover)"
"saves":
  - "dexterity": !!int "5"
  - "wisdom": !!int "5"
"condition_immunities": "[petrified](Інструменти%20ДМ/CLI/rules/conditions.md#Petrified)"
"senses": "darkvision 120 ft., passive Perception 11"
"languages": "Primordial (Terran)"
"cr": "11"
"traits":
  - "desc": "The dao can burrow through nonmagical, unworked earth and stone. While\
      \ doing so, the dao doesn't disturb the material it moves through."
    "name": "Earth Glide"
  - "desc": "If the dao dies outside the Elemental Plane of Earth, its body dissolves\
      \ into dirt, and it gains a new body in dice:1d4|noform|noparens|avg (d4)\
      \ days, reviving with all its [Hit Points](Інструменти%20ДМ/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ somewhere on the Plane of Earth."
    "name": "Elemental Restoration"
  - "desc": "The dao has [Advantage](Інструменти%20ДМ/CLI/rules/variant-rules/advantage-xphb.md)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "The dao has a 30 percent chance of knowing the [Wish](Інструменти%20Д\
      М/CLI/spells/wish-xphb.md) spell. If the dao knows it, the dao can cast it only\
      \ on behalf of a non-genie creature who communicates a wish in a way the dao\
      \ can understand. If the dao casts the spell for the creature, the dao suffers\
      \ none of the spell's stress. Once the dao has cast it three times, the dao\
      \ can't do so again for 365 days."
    "name": "Wishes"
"actions":
  - "desc": "The dao makes three Earthen Maul attacks or two Earth Burst attacks."
    "name": "Multiattack"
  - "desc": "Melee Attack Roll: dice:1d20+10|noform|noparens|text(+10), reach\
      \ 5 ft. Hit: dice:4d6+6|noform|noparens|avg|text(20) (4d6 + 6) Bludgeoning\
      \ damage. If the target is a Large or smaller creature, it has the [Prone](І\
      нструменти%20ДМ/CLI/rules/conditions.md#Prone) condition."
    "name": "Earthen Maul"
  - "desc": "Ranged Attack Roll: dice:1d20+10|noform|noparens|text(+10), range\
      \ 120 ft. Hit: dice:2d8+6|noform|noparens|avg|text(15) (2d8 + 6) Bludgeoning\
      \ damage. Hit or Miss: Earth explodes from the target's space, creating the\
      \ following effect. Dexterity Saving Throw: DC 16, each creature in a 10-foot\
      \ [Emanation](Інструменти%20ДМ/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from and including the target. Failure: dice:3d6|noform|noparens|avg|text(10)\
      \ (3d6) Thunder damage."
    "name": "Earth Burst"
  - "desc": "The dao casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 16):\n\nAt\
      \ will: [Detect Evil and Good](Інструменти%20ДМ/CLI/spells/detect-evil-and-good-xphb.md),\
      \ [Detect Magic](Інструменти%20ДМ/CLI/spells/detect-magic-xphb.md), [Stone Shape](І\
      нструменти%20ДМ/CLI/spells/stone-shape-xphb.md)\n\n1/day each: [Gaseous\
      \ Form](Інструменти%20ДМ/CLI/spells/gaseous-form-xphb.md), [Invisibility](Ін\
      струменти%20ДМ/CLI/spells/invisibility-xphb.md), [Move Earth](Інструменти%20Д\
      М/CLI/spells/move-earth-xphb.md), [Passwall](Інструменти%20ДМ/CLI/spells/passwall-xphb.md),\
      \ [Plane Shift](Інструменти%20ДМ/CLI/spells/plane-shift-xphb.md), [Tongues](І\
      нструменти%20ДМ/CLI/spells/tongues-xphb.md), [Wall of Stone](Інструменти%20Д\
      М/CLI/spells/wall-of-stone-xphb.md)"
    "name": "Spellcasting"
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/elemental/token/dao-xmm.webp"
```
^statblock

## Environment

planar, earth, underdark