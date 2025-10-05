---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/yugoloth
statblock: inline
statblock-link: "#^statblock"
aliases:
- Oinoloth
---
# [Oinoloth](Інструменти ДМ\CLI\bestiary\fiend/oinoloth-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 202*  

Grim specters of death, oinoloths bring pestilence wherever they go. When armies recognize their awful forms, their mere appearance causes soldiers to break ranks and flee, lest they succumb to one of the awful plagues that oinoloths let loose.

Oinoloths solve thorny problems by killing everyone involved. They are typically hired as a last resort when a siege has gone on too long or an army has proven too strong to overcome. Once summoned, oinoloths stalk the killing field, poisoning the ground and sickening creatures they encounter. Sometimes they might be hired to lift the very plagues they spread, but the price for such work is high, and the effort turns the creatures they save into debilitated wrecks.

```statblock
"name": "Oinoloth (MPMM)"
"size": "Medium"
"type": "fiend"
"subtype": "yugoloth"
"alignment": "Typically  Neutral Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "119"
"hit_dice": "14d8 + 56"
"modifier": !!int "3"
"stats":
  - !!int "19"
  - !!int "17"
  - !!int "18"
  - !!int "17"
  - !!int "16"
  - !!int "19"
"speed": "40 ft."
"saves":
  - "constitution": !!int "8"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "[Deception](Інструменти%20ДМ/CLI/rules/skills.md#Deception)"
    "desc": "+8"
  - "name": "[Intimidation](Інструменти%20ДМ/CLI/rules/skills.md#Intimidation)"
    "desc": "+8"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+7"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "acid, poison"
"condition_immunities": "[poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned)"
"senses": "blindsight 60 ft., darkvision 60 ft., passive Perception 17"
"languages": "Abyssal, Infernal, telepathy 60 ft."
"cr": "12"
"traits":
  - "desc": "The oinoloth has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The oinoloth makes two Claw attacks, and it uses Spellcasting or Teleport."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: dice:1d20+8|noform|noparens|text(+8) to hit,\
      \ reach 5 ft., one target. Hit: dice:3d6+4|noform|noparens|avg|text(14)\
      \ (3d6 + 4) slashing damage plus dice:4d10|noform|noparens|avg|text(22)\
      \ (4d10) necrotic damage."
    "name": "Claw"
  - "desc": "The oinoloth touches one willing creature within 5 feet of it. The target\
      \ regains all its hit points. In addition, the oinoloth can end one disease\
      \ on the target or remove one of the following conditions from it: [blinded](І\
      нструменти%20ДМ/CLI/rules/conditions.md#Blinded), [deafened](Інструменти%20Д\
      М/CLI/rules/conditions.md#Deafened), [paralyzed](Інструменти%20ДМ/CLI/rules/conditions.md#Paralyzed),\
      \ or [poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned). The target\
      \ then gains 1 level of [exhaustion](Інструменти%20ДМ/CLI/rules/conditions.md#Exhaustion),\
      \ and its hit point maximum is reduced by dice:2d6|noform|noparens|avg|text(7)\
      \ (2d6). This reduction can be removed only by a [wish](Інструменти%20ДМ/CLI/spells/wish-xphb.md)\
      \ spell or by casting [greater restoration](Інструменти%20ДМ/CLI/spells/greater-restoration-xphb.md)\
      \ on the target three times within the same hour. The target dies if its hit\
      \ point maximum is reduced to 0."
    "name": "Corrupted Healing (Recharge 6)"
  - "desc": "The oinoloth teleports, along with any equipment it is wearing or carrying,\
      \ up to 60 feet to an unoccupied space it can see."
    "name": "Teleport"
  - "desc": "The oinoloth casts one of the following spells, requiring no material\
      \ components and using Charisma as the spellcasting ability (spell save DC 16):\n\
      \nAt will: [darkness](Інструменти%20ДМ/CLI/spells/darkness-xphb.md), [detect\
      \ magic](Інструменти%20ДМ/CLI/spells/detect-magic-xphb.md), [dispel magic](І\
      нструменти%20ДМ/CLI/spells/dispel-magic-xphb.md), [hold monster](Інструменти\
      %20ДМ/CLI/spells/hold-monster-xphb.md), [invisibility](Інструменти%20ДМ/CLI/spells/invisibility-xphb.md)\
      \ (self only)\n\n1/day each: [feeblemind](Інструменти%20ДМ/CLI/spells/befuddlement-xphb.md),\
      \ [globe of invulnerability](Інструменти%20ДМ/CLI/spells/globe-of-invulnerability-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The oinoloth blights the area in a 30-foot-radius sphere centered on\
      \ itself. The blight lasts for 24 hours. While the area is blighted, all normal\
      \ plants there wither and die.\n\nFurthermore, when a creature moves into the\
      \ blighted area or starts its turn there, that creature must make a DC 16 Constitution\
      \ saving throw. On a failed save, the creature takes dice:4d6|noform|noparens|avg|text(14)\
      \ (4d6) poison damage and is [poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned).\
      \ On a successful save, the creature is immune to the oinoloth's Bringer of\
      \ Plagues for the next 24 hours.\n\nThe [poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned)\
      \ creature can't regain hit points. After every 24 hours that elapse, the [poisoned](І\
      нструменти%20ДМ/CLI/rules/conditions.md#Poisoned) creature can repeat the saving\
      \ throw. On a failed save, the creature's hit point maximum is reduced by dice:1d10|noform|noparens|avg|text(5)\
      \ (d10). This reduction lasts until the poison ends, and the target dies if\
      \ its hit point maximum is reduced to 0. The poison ends after the creature\
      \ successfully saves against it three times."
    "name": "Bringer of Plagues (Recharge 5-6)"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/fiend/token/oinoloth-mpmm.webp"
```
^statblock

## Environment

desert, underdark