---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/16
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/merfolk
statblock: inline
statblock-link: "#^statblock"
aliases:
- Zegana
---
# [Zegana](Інструменти ДМ\CLI\bestiary\npc/zegana-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 255*  

The regal and reticent Prime Speaker Zegana is the merfolk guildmaster of the Simic Combine. She upholds the traditional ways of the guild and its utopian philosophy, which espouses a vision of an ideal world in which nature and civilization coexist in perfect balance. Some people in the guild-members of the Adaptationist faction in particular-argue that her ways are outdated and the guild requires more practical leadership. In response, Zegana maintains that she serves as prime speaker only at the sufferance of the Speakers' Chamber, and if the other speakers wish to replace her, they are certainly within their rights to do so.

```statblock
"name": "Zegana (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "merfolk"
"alignment": "Lawful Neutral"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "130"
"hit_dice": "20d8 + 40"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "14"
  - !!int "20"
  - !!int "18"
  - !!int "16"
"speed": "30 ft., swim 40 ft."
"saves":
  - "intelligence": "+10"
  - "wisdom": "+9"
"skillsaves":
  - "name": "[Insight](Інструменти%20ДМ/CLI/rules/skills.md#Insight)"
    "desc": "+9"
  - "name": "[Nature](Інструменти%20ДМ/CLI/rules/skills.md#Nature)"
    "desc": "+10"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+9"
"damage_resistances": "cold, poison"
"senses": "darkvision 60 ft., passive Perception 19"
"languages": "Common, Elvish, Merfolk"
"cr": "16"
"traits":
  - "desc": "Zegana is a 15th-level Simic spellcaster. Her spellcasting ability is\
      \ Intelligence (spell save DC 18, +10 to hit with spell attacks). She has\
      \ the following wizard spells prepared:\n\nCantrips (at will): [acid splash](І\
      нструменти%20ДМ/CLI/spells/acid-splash-xphb.md), [druidcraft](Інструменти%20Д\
      М/CLI/spells/druidcraft-xphb.md), [ray of frost](Інструменти%20ДМ/CLI/spells/ray-of-frost-xphb.md),\
      \ shape water\n\n1st level (4 slots): [color spray](Інструменти%20ДМ/CLI/spells/color-spray-xphb.md),\
      \ [expeditious retreat](Інструменти%20ДМ/CLI/spells/expeditious-retreat-xphb.md),\
      \ [fog cloud](Інструменти%20ДМ/CLI/spells/fog-cloud-xphb.md), [shield](Інстр\
      ументи%20ДМ/CLI/spells/shield-xphb.md)\n\n2nd level (3 slots): [enlarge/reduce](І\
      нструменти%20ДМ/CLI/spells/enlarge-reduce-xphb.md), [gust of wind](Інструмен\
      ти%20ДМ/CLI/spells/gust-of-wind-xphb.md)\n\n3rd level (3 slots): [counterspell](І\
      нструменти%20ДМ/CLI/spells/counterspell-xphb.md), [fly](Інструменти%20ДМ/CLI/spells/fly-xphb.md),\
      \ [slow](Інструменти%20ДМ/CLI/spells/slow-xphb.md)\n\n4th level (3 slots):\
      \ [control water](Інструменти%20ДМ/CLI/spells/control-water-xphb.md), [ice storm](І\
      нструменти%20ДМ/CLI/spells/ice-storm-xphb.md), [polymorph](Інструменти%20ДМ\
      /CLI/spells/polymorph-xphb.md)\n\n5th level (2 slots): [conjure elemental](І\
      нструменти%20ДМ/CLI/spells/conjure-elemental-xphb.md), [creation](Інструмент\
      и%20ДМ/CLI/spells/creation-xphb.md)\n\n6th level (1 slots): [move earth](І\
      нструменти%20ДМ/CLI/spells/move-earth-xphb.md), [wall of ice](Інструменти%20Д\
      М/CLI/spells/wall-of-ice-xphb.md)\n\n7th level (1 slots): [prismatic spray](І\
      нструменти%20ДМ/CLI/spells/prismatic-spray-xphb.md), [teleport](Інструменти\
      %20ДМ/CLI/spells/teleport-xphb.md)\n\n8th level (1 slots): [control weather](І\
      нструменти%20ДМ/CLI/spells/control-weather-xphb.md), [dominate monster](Інст\
      рументи%20ДМ/CLI/spells/dominate-monster-xphb.md)"
    "name": "Spellcasting"
  - "desc": "Zegana can breathe air and water."
    "name": "Amphibious"
  - "desc": "If Zegana fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Zegana has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Melee  or Ranged Weapon Attack: +10 to hit, reach 5 ft. or range\
      \ 20/60 ft., one target. Hit: 12 (2d6 + 5) piercing damage, and the trident\
      \ emits a thunderous boom. Each creature in a 15-foot cube originating from\
      \ the prongs of the trident must make a DC 18 Constitution saving throw. On\
      \ a failed save, the creature takes 9 (2d8) thunder damage and is pushed 10\
      \ feet away from Zegana. If the creature is underwater, the damage is increased\
      \ to 13 (3d8). On a successful save, the creature takes half as much damage\
      \ and isn't pushed."
    "name": "Prime Speaker's Trident"
  - "desc": "Zegana conjures a wave of water that crashes down on an area within 120\
      \ feet of her. The area can be up to 30 feet long, up to 10 feet wide, and up\
      \ to 10 feet tall. Each creature in that area must make a DC 18 Dexterity saving\
      \ throw. On a failed save, a creature takes 18 (4d8) bludgeoning damage and\
      \ is knocked [prone](Інструменти%20ДМ/CLI/rules/conditions.md#Prone). On a successful\
      \ save, a creature takes half as much damage and isn't knocked [prone](Інстр\
      ументи%20ДМ/CLI/rules/conditions.md#Prone). The water spreads out across the\
      \ ground, extinguishing unprotected flames it comes in contact with, and then\
      \ vanishes."
    "name": "Deluge (Recharge 4-6)"
"legendary_actions":
  - "desc": "Zegana gains resistance to one damage type of her choice-acid, fire,\
      \ lightning, or thunder-until the start of her next turn."
    "name": "Adaptive Skin"
  - "desc": "Zegana makes one melee attack with the Prime Speaker's Trident."
    "name": "Trident"
  - "desc": "Zegana casts [enlarge/reduce](Інструменти%20ДМ/CLI/spells/enlarge-reduce-xphb.md)\
      \ on herself, using the enlarge option, without expending a spell slot."
    "name": "Enlarge (Costs 2 Actions)"
  - "desc": "Zegana uses Deluge, if available."
    "name": "Deluge (Costs 3 Actions)"
"source":
  - "GGR"
"image": "Інструменти%20ДМ/CLI/bestiary/npc/token/zegana-ggr.webp"
```
^statblock