---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/21
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
- Molydeus
---
# [Molydeus](Інструменти ДМ\CLI\bestiary\fiend/molydeus-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 184*  

The fearsome molydeus speaks for the demon lord it serves and enforces its master's will. This demon is 12 feet tall, and its bipedal body has a slavering wolfs head and a fanged serpent's head. Its demon lord can speak and see through the serpent head; this master also uses the molydeus to guard treasures, slay foes, and terrify troops into obedience.

A molydeus's demon lord bestows on it a powerful weapon that dissolves if the molydeus dies. The weapon's form varies depending on the creator, but that doesn't affect the weapon's capabilities.

```statblock
"name": "Molydeus (MPMM)"
"size": "Huge"
"type": "fiend"
"subtype": "demon"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "216"
"hit_dice": "16d12 + 112"
"modifier": !!int "6"
"stats":
  - !!int "28"
  - !!int "22"
  - !!int "25"
  - !!int "21"
  - !!int "24"
  - !!int "24"
"speed": "40 ft."
"saves":
  - "strength": "+16"
  - "constitution": "+14"
  - "wisdom": "+14"
  - "charisma": "+14"
"skillsaves":
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+21"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[blinded](Інструменти%20ДМ/CLI/rules/conditions.md#Blinded),\
  \ [charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed), [deafened](Інстру\
  менти%20ДМ/CLI/rules/conditions.md#Deafened), [frightened](Інструменти%20ДМ/CLI/rules/conditions.md#Frightened),\
  \ [poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned), [stunned](Інстр\
  ументи%20ДМ/CLI/rules/conditions.md#Stunned)"
"senses": "truesight 120 ft., passive Perception 31"
"languages": "Abyssal, telepathy 120 ft."
"cr": "21"
"traits":
  - "desc": "If the molydeus fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "The molydeus has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The molydeus makes one Demonic Weapon attack, one Snakebite attack, and\
      \ one Wolf Bite attack."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +16 to hit, reach 15 ft., one target. Hit:\
      \ 35 (4d12 + 9) force damage. If the target has at least one head and the\
      \ molydeus rolled a 20 on the attack roll, the target is decapitated and dies\
      \ if it can't survive without that head. A target is immune to this effect if\
      \ it takes none of the damage, has legendary actions, or is Huge or larger.\
      \ Such a creature takes an extra 27 (6d8) force damage from the hit."
    "name": "Demonic Weapon"
  - "desc": "Melee Weapon Attack: +16 to hit, reach 15 ft., one creature. Hit:\
      \ 16 (2d6 + 9) poison damage. The target must succeed on a DC 22 Constitution\
      \ saving throw, or its hit point maximum is reduced by an amount equal to the\
      \ damage taken. This reduction lasts until the target finishes a long rest.\
      \ The target transforms into a [manes](Інструменти%20ДМ/CLI/bestiary/fiend/manes-xmm.md)\
      \ if this reduces its hit point maximum to 0. This transformation can be ended\
      \ only by a [wish](Інструменти%20ДМ/CLI/spells/wish-xphb.md) spell."
    "name": "Snakebite"
  - "desc": "Melee Weapon Attack: +16 to hit, reach 10 ft., one target. Hit:\
      \ 25 (3d10 + 9) necrotic damage."
    "name": "Wolf Bite"
  - "desc": "The molydeus casts one of the following spells, requiring no material\
      \ components and using Charisma as the spellcasting ability (spell save DC 22):\n\
      \nAt will: [dispel magic](Інструменти%20ДМ/CLI/spells/dispel-magic-xphb.md),\
      \ [polymorph](Інструменти%20ДМ/CLI/spells/polymorph-xphb.md), [telekinesis](І\
      нструменти%20ДМ/CLI/spells/telekinesis-xphb.md), [teleport](Інструменти%20ДМ\
      /CLI/spells/teleport-xphb.md)\n\n3/day: [lightning bolt](Інструменти%20Д\
      М/CLI/spells/lightning-bolt-xphb.md)"
    "name": "Spellcasting"
"legendary_actions":
  - "desc": "The molydeus makes one Demonic Weapon or Snakebite attack."
    "name": "Attack"
  - "desc": "The molydeus moves without provoking [opportunity attacks](Інструмент\
      и%20ДМ/CLI/rules/actions.md#Opportunity%20Attack)."
    "name": "Move"
  - "desc": "The molydeus uses Spellcasting."
    "name": "Cast a Spell (Costs 2 Actions)"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/fiend/token/molydeus-mpmm.webp"
```
^statblock