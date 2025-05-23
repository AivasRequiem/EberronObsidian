---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/environment/fire
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- Azer Pyromancer
---
# [Azer Pyromancer](Інструменти ДМ\CLI\bestiary\elemental/azer-pyromancer-xmm.md)
*Source: Monster Manual (2024) p. 25*  

Azer pyromancers conjure flames from the Elemental Plane of Fire to defend themselves and stoke magical forges.

## Azers

*Fiery Smiths of Living Metal*

- **Habitat.** Mountain, Planar (Elemental Plane of Fire)  
- **Treasure.** Armaments, Individual  

Azers are living bronze folk who work the primal elements of creation to craft weapons and magical wonders among the multiverse's mightiest infernos.

```statblock
"name": "Azer Pyromancer (XMM)"
"size": "Medium"
"type": "elemental"
"alignment": "Lawful Neutral"
"ac": !!int "18"
"hp": !!int "97"
"hit_dice": "13d8 + 39"
"modifier": !!int "2"
"stats":
  - !!int "15"
  - !!int "14"
  - !!int "16"
  - !!int "12"
  - !!int "18"
  - !!int "13"
"speed": "30 ft."
"saves":
  - "constitution": "+6"
  - "wisdom": "+7"
"skillsaves":
  - "name": "[Arcana](Інструменти%20ДМ/CLI/rules/skills.md#Arcana)"
    "desc": "+4"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+7"
"damage_immunities": "fire, poison"
"condition_immunities": "[poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned)"
"senses": "passive Perception 17"
"languages": "Primordial (Ignan)"
"cr": "6"
"traits":
  - "desc": "At the end of each of the azer's turns, each creature of the azer's choice\
      \ in a 5-foot [Emanation](Інструменти%20ДМ/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from the azer takes 11 (2d10) Fire damage unless the azer has\
      \ the [Incapacitated](Інструменти%20ДМ/CLI/rules/conditions.md#Incapacitated)\
      \ condition."
    "name": "Fire Aura"
  - "desc": "The azer sheds [Bright Light](Інструменти%20ДМ/CLI/rules/variant-rules/bright-light-xphb.md)\
      \ in a 10-foot radius and [Dim Light](Інструменти%20ДМ/CLI/rules/variant-rules/dim-light-xphb.md)\
      \ for an additional 10 feet."
    "name": "Illumination"
"actions":
  - "desc": "The azer makes two Flame Burst attacks."
    "name": "Multiattack"
  - "desc": "Melee  or Ranged Attack Roll: +7, reach 5 ft. or range 120 ft. Hit:\
      \ 15 (2d10 + 4) Fire damage."
    "name": "Flame Burst"
  - "desc": "The azer casts one of the following spells, requiring no Material components\
      \ and using Wisdom as the spellcasting ability (spell save DC 15):\n\nAt will:\
      \ [Elementalism](Інструменти%20ДМ/CLI/spells/elementalism-xphb.md), [Mage Hand](І\
      нструменти%20ДМ/CLI/spells/mage-hand-xphb.md)\n\n1/day: [Fireball](Інстр\
      ументи%20ДМ/CLI/spells/fireball-xphb.md)"
    "name": "Spellcasting"
  - "desc": "The azer casts [Hellish Rebuke](Інструменти%20ДМ/CLI/spells/hellish-rebuke-xphb.md)\
      \ in response to that spell's trigger, using the same spellcasting ability as\
      \ Spellcasting.\n"
    "name": "Hellish Rebuke (2/Day)"
"reactions":
  - "desc": "The azer casts one of the following spells, requiring no Material components\
      \ and using Wisdom as the spellcasting ability (spell save DC 15):\n\nAt will:\
      \ [Elementalism](Інструменти%20ДМ/CLI/spells/elementalism-xphb.md), [Mage Hand](І\
      нструменти%20ДМ/CLI/spells/mage-hand-xphb.md)\n\n1/day: [Fireball](Інстр\
      ументи%20ДМ/CLI/spells/fireball-xphb.md)"
    "name": "Spellcasting"
  - "desc": "The azer casts [Hellish Rebuke](Інструменти%20ДМ/CLI/spells/hellish-rebuke-xphb.md)\
      \ in response to that spell's trigger, using the same spellcasting ability as\
      \ Spellcasting.\n"
    "name": "Hellish Rebuke (2/Day)"
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/elemental/token/azer-pyromancer-xmm.webp"
```
^statblock

## Environment

mountain, planar, fire