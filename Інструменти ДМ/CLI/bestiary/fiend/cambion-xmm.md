---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- Cambion
---
# [Cambion](Інструменти ДМ\CLI\bestiary\fiend/cambion-xmm.md)
*Source: Monster Manual (2024) p. 65*  

## Cambion

*Mortal Infused with Fiendish Might*

- **Habitat.** Any  
- **Treasure.** Relics  

Cambions are former mortals corrupted by fiendish power or possessed by insidious forces. While tieflings are free-willed individuals with a hint of fiendish ancestry, cambions are inherently tied to or remade by the wicked magic of the Lower Planes.

Many cambions serve the malevolent forces that are the source of their powers. Others seek to claim the might of whatever created them or to seize otherworldly powers of their own. Among the most notorious of such cambions is Iuz, a villain who became an evil demigod and whose villainous nation threatens the Free City of Greyhawk on Oerth.

Cambions come into being in disparate ways. Roll on or choose a result from the Cambion Origins table to determine the source of a cambion's fiendish might.

> [!quote] A quote from Iuz the Evil, Cambion Demigod  
> 
> It seems that I must do everything myself, since I have only fools for servants. Clearly disappointment must ever be the price of divinity.

**Cambion Origins**

`dice: [](cambion-xmm.md#^cambion-origins)`

| dice: 1d6 | The Cambion Gained Its Power After... |
|-----------|---------------------------------------|
| 1 | Being possessed by a fiendish being. |
| 2 | Being resurrected by an evil magic-user. |
| 3 | Lengthy exposure to a Lower Plane. |
| 4 | Making a bargain with a Fiend. |
| 5 | Suffering a god's curse. |
| 6 | Taking part in fiendish rituals. |
^cambion-origins

```statblock
"name": "Cambion (XMM)"
"size": "Medium"
"type": "fiend"
"alignment": "Neutral Evil"
"ac": !!int "19"
"hp": !!int "105"
"hit_dice": "14d8 + 42"
"modifier": !!int "4"
"stats":
  - !!int "18"
  - !!int "18"
  - !!int "16"
  - !!int "14"
  - !!int "12"
  - !!int "16"
"speed": "30 ft., fly 60 ft."
"saves":
  - "strength": "+7"
  - "constitution": "+6"
  - "intelligence": "+5"
  - "charisma": "+6"
"skillsaves":
  - "name": "[Deception](Інструменти%20ДМ/CLI/rules/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](Інструменти%20ДМ/CLI/rules/skills.md#Stealth)"
    "desc": "+7"
"damage_resistances": "cold, fire, lightning, poison"
"condition_immunities": "[poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 14"
"languages": "Abyssal, Common, Infernal"
"cr": "5"
"actions":
  - "desc": "The cambion makes two attacks, using Claw or Fire Ray in any combination."
    "name": "Multiattack"
  - "desc": "Melee Attack Roll: +7, reach 5 ft. Hit: 8 (1d8 + 4) Slashing\
      \ damage plus 7 (2d6) Fire damage."
    "name": "Claw"
  - "desc": "Ranged Attack Roll: +7, range 120 ft. Hit: 13 (3d6 + 3) Fire\
      \ damage."
    "name": "Fire Ray"
  - "desc": "The cambion casts one of the following spells, requiring no Material\
      \ components and using Charisma as the spellcasting ability (spell save DC 14):\n\
      \n2/day each: [Alter Self](Інструменти%20ДМ/CLI/spells/alter-self-xphb.md),\
      \ [Command](Інструменти%20ДМ/CLI/spells/command-xphb.md) (level 3 version),\
      \ [Detect Magic](Інструменти%20ДМ/CLI/spells/detect-magic-xphb.md)\n\n1/day\
      \ each: [Dominate Person](Інструменти%20ДМ/CLI/spells/dominate-person-xphb.md)\
      \ (level 8 version), [Plane Shift](Інструменти%20ДМ/CLI/spells/plane-shift-xphb.md)\
      \ (self only)"
    "name": "Spellcasting"
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/fiend/token/cambion-xmm.webp"
```
^statblock

## Environment

any