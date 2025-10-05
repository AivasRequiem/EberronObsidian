---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- Cosmotronic Blastseeker
---
# [Cosmotronic Blastseeker](Інструменти ДМ\CLI\bestiary\humanoid/cosmotronic-blastseeker-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 242*  

While chemisters focus on inventing new tools, weapons, and other devices for the guild to use, the role of a blastseeker is to put those devices to work. Despite the name, not all such devices produce explosions, but all the most interesting ones (from the Izzet perspective) do.

```statblock
"name": "Cosmotronic Blastseeker (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Neutral"
"ac": !!int "15"
"ac_class": "[chain shirt](Інструменти%20ДМ/CLI/items/chain-shirt-xphb.md)"
"hp": !!int "37"
"hit_dice": "5d8 + 15"
"modifier": !!int "2"
"stats":
  - !!int "14"
  - !!int "15"
  - !!int "16"
  - !!int "18"
  - !!int "9"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "4"
  - "constitution": !!int "5"
"skillsaves":
  - "name": "[Arcana](Інструменти%20ДМ/CLI/rules/skills.md#Arcana)"
    "desc": "+6"
  - "name": "[Intimidation](Інструменти%20ДМ/CLI/rules/skills.md#Intimidation)"
    "desc": "+3"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+1"
"senses": "passive Perception 11"
"languages": "any one language (usually Common)"
"cr": "4"
"traits":
  - "desc": "The blastseeker's innate spellcasting ability is Intelligence (spell\
      \ save DC 14, dice:1d20+6|noform|noparens|text(+6) to hit with spell attacks).\
      \ The blastseeker can innately cast the following spells, requiring no components\
      \ other than its Izzet gear, which doesn't function for others:\n\n3/day each:\
      \ [scorching ray](Інструменти%20ДМ/CLI/spells/scorching-ray-xphb.md), [shield](І\
      нструменти%20ДМ/CLI/spells/shield-xphb.md), [thunderwave](Інструменти%20ДМ/CLI/spells/thunderwave-xphb.md)\n\
      \n2/day: [fireball](Інструменти%20ДМ/CLI/spells/fireball-xphb.md)"
    "name": "Innate Spellcasting"
  - "desc": "When the blastseeker rolls damage for a spell, it can reroll up to four\
      \ dice of damage. It must use the new dice."
    "name": "Empowered Spell (3/Day)"
  - "desc": "The blastseeker makes one attack roll, ability check, or saving throw\
      \ with advantage."
    "name": "Tides of Chaos (1/Day)"
"actions":
  - "desc": "Melee Weapon Attack: dice:1d20+4|noform|noparens|text(+4) to hit,\
      \ reach 5 ft., one target. Hit: dice:1d8+2|noform|noparens|avg|text(6) (1d8\
      \ + 2) bludgeoning damage, or dice:1d10+2|noform|noparens|avg|text(7) (1d10\
      \ + 2) bludgeoning damage if used with two hands."
    "name": "Warhammer"
"source":
  - "GGR"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/cosmotronic-blastseeker-ggr.webp"
```
^statblock