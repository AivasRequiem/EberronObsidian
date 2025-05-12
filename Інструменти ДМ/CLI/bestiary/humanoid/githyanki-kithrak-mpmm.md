---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/gith
statblock: inline
statblock-link: "#^statblock"
aliases:
- Githyanki Kith'rak
---
# [Githyanki Kith'rak](Інструменти ДМ\CLI\bestiary\humanoid/githyanki-kithrak-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 140*  

Militarized githyanki cultures assign ranks and responsibilities to citizens. Groups of ten warriors follow the commands of sarths ([githyanki warriors](Інструменти%20ДМ/CLI/bestiary/aberration/githyanki-warrior-xmm.md)), while ten sarths obey the commands of a mighty kith'rak. These champions undergo torturous training and psionic testing until they can command the respect of their underlings.

## Githyanki

Githyanki descend from an ancient people who were also the progenitors of githzerai (also in this book). These tall, gaunt folk have potent psionic powers and dwell, for the most part, on the Astral Plane. Among the best-known githyanki are the bellicose followers of the Lich Queen Vlaakith. They terrorize the Astral Plane, raiding into other planes to plunder the multiverse of its magic and riches.

```statblock
"name": "Githyanki Kith'rak (MPMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "gith"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "[plate](Інструменти%20ДМ/CLI/items/plate-armor-xphb.md)"
"hp": !!int "180"
"hit_dice": "24d8 + 72"
"modifier": !!int "3"
"stats":
  - !!int "18"
  - !!int "16"
  - !!int "17"
  - !!int "16"
  - !!int "15"
  - !!int "17"
"speed": "30 ft."
"saves":
  - "constitution": "+7"
  - "intelligence": "+7"
  - "wisdom": "+6"
"skillsaves":
  - "name": "[Intimidation](Інструменти%20ДМ/CLI/rules/skills.md#Intimidation)"
    "desc": "+7"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+6"
"senses": "passive Perception 16"
"languages": "Gith"
"cr": "12"
"actions":
  - "desc": "The githyanki makes three Greatsword attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 11\
      \ (2d6 + 4) slashing damage plus 17 (5d6) psychic damage."
    "name": "Greatsword"
  - "desc": "The githyanki casts one of the following spells, requiring no spell components\
      \ and using Intelligence as the spellcasting ability (spell save DC 15):\n\n\
      At will: [mage hand](Інструменти%20ДМ/CLI/spells/mage-hand-xphb.md) (the\
      \ hand is invisible)\n\n3/day each: [blur](Інструменти%20ДМ/CLI/spells/blur-xphb.md),\
      \ [nondetection](Інструменти%20ДМ/CLI/spells/nondetection-xphb.md) (self only)\n\
      \n1/day each: [plane shift](Інструменти%20ДМ/CLI/spells/plane-shift-xphb.md),\
      \ [telekinesis](Інструменти%20ДМ/CLI/spells/telekinesis-xphb.md)"
    "name": "Spellcasting (Psionics)"
"bonus_actions":
  - "desc": "The githyanki teleports, along with any equipment it is wearing or carrying,\
      \ up to 30 feet to an unoccupied space it can see."
    "name": "Astral Step (Recharge 4-6)"
  - "desc": "The githyanki magically ends the [charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed)\
      \ and [frightened](Інструменти%20ДМ/CLI/rules/conditions.md#Frightened) conditions\
      \ on itself and each creature of its choice that it can see within 30 feet of\
      \ it."
    "name": "Rally the Troops"
"reactions":
  - "desc": "The githyanki adds 4 to its AC against one melee attack that would hit\
      \ it. To do so, the githyanki must see the attacker and be wielding a melee\
      \ weapon."
    "name": "Parry"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/githyanki-kithrak-mpmm.webp"
```
^statblock

## Environment

desert, mountain, urban