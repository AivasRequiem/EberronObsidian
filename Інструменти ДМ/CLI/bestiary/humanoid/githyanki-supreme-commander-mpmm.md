---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/14
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/gith
statblock: inline
statblock-link: "#^statblock"
aliases:
- Githyanki Supreme Commander
---
# [Githyanki Supreme Commander](Інструменти ДМ\CLI\bestiary\humanoid/githyanki-supreme-commander-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 141*  

Supreme commanders lead armies, each one commanding ten kith'raks, who in turn lead the rest of their forces. Most supreme commanders ride [red dragons](Інструменти%20ДМ/CLI/bestiary/dragon/adult-red-dragon-xmm.md) into battle.

## Githyanki

Githyanki descend from an ancient people who were also the progenitors of githzerai (also in this book). These tall, gaunt folk have potent psionic powers and dwell, for the most part, on the Astral Plane. Among the best-known githyanki are the bellicose followers of the Lich Queen Vlaakith. They terrorize the Astral Plane, raiding into other planes to plunder the multiverse of its magic and riches.

```statblock
"name": "Githyanki Supreme Commander (MPMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "gith"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "[plate](Інструменти%20ДМ/CLI/items/plate-armor-xphb.md)"
"hp": !!int "187"
"hit_dice": "22d8 + 88"
"modifier": !!int "3"
"stats":
  - !!int "19"
  - !!int "17"
  - !!int "18"
  - !!int "16"
  - !!int "16"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "constitution": !!int "9"
  - "intelligence": !!int "8"
  - "wisdom": !!int "8"
"skillsaves":
  - "name": "[Intimidation](Інструменти%20ДМ/CLI/rules/skills.md#Intimidation)"
    "desc": "+9"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+8"
"senses": "passive Perception 18"
"languages": "Gith"
"cr": "14"
"traits":
  - "desc": "If the githyanki fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
"actions":
  - "desc": "The githyanki makes two Silver Greatsword attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: dice:1d20+12|noform|noparens|text(+12) to hit,\
      \ reach 5 ft., one target. Hit: dice:2d6+7|noform|noparens|avg|text(14)\
      \ (2d6 + 7) slashing damage plus dice:5d6|noform|noparens|avg|text(17) (5d6)\
      \ psychic damage. On a critical hit against a target in an astral body (as with\
      \ the [astral projection](Інструменти%20ДМ/CLI/spells/astral-projection-xphb.md)\
      \ spell), the githyanki can cut the silvery cord that tethers the target to\
      \ its material body, instead of dealing damage."
    "name": "Silver Greatsword"
  - "desc": "The githyanki casts one of the following spells, requiring no spell components\
      \ and using Intelligence as the spellcasting ability (spell save DC 16):\n\n\
      At will: [mage hand](Інструменти%20ДМ/CLI/spells/mage-hand-xphb.md) (the\
      \ hand is invisible)\n\n3/day each: [levitate](Інструменти%20ДМ/CLI/spells/levitate-xphb.md)\
      \ (self only), [nondetection](Інструменти%20ДМ/CLI/spells/nondetection-xphb.md)\
      \ (self only)\n\n1/day each: [Bigby's hand](Інструменти%20ДМ/CLI/spells/bigbys-hand-xphb.md),\
      \ [mass suggestion](Інструменти%20ДМ/CLI/spells/mass-suggestion-xphb.md), [plane\
      \ shift](Інструменти%20ДМ/CLI/spells/plane-shift-xphb.md), [telekinesis](Інс\
      трументи%20ДМ/CLI/spells/telekinesis-xphb.md)"
    "name": "Spellcasting (Psionics)"
"bonus_actions":
  - "desc": "The githyanki teleports, along with any equipment it is wearing or carrying,\
      \ up to 30 feet to an unoccupied space it can see."
    "name": "Astral Step"
"reactions":
  - "desc": "The githyanki adds 5 to its AC against one melee attack that would hit\
      \ it. To do so, the githyanki must see the attacker and be wielding a melee\
      \ weapon."
    "name": "Parry"
"legendary_actions":
  - "desc": "The githyanki targets one ally it can see within 30 feet of it. If the\
      \ target can see or hear the githyanki, the target can make one melee weapon\
      \ attack using its reaction, if available, and has advantage on the attack roll."
    "name": "Command Ally"
  - "desc": "The githyanki makes one Silver Greatsword attack."
    "name": "Attack (2 Actions)"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/githyanki-supreme-commander-mpmm.webp"
```
^statblock

## Environment

desert, mountain, urban