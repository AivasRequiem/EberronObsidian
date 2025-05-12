---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/environment/lower
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/yugoloth
statblock: inline
statblock-link: "#^statblock"
aliases:
- Arcanaloth
---
# [Arcanaloth](Інструменти ДМ\CLI\bestiary\fiend/arcanaloth-xmm.md)
*Source: Monster Manual (2024) p. 19*  

## Arcanaloth

*Yugoloth of Magical Manipulation*

- **Habitat.** Planar (Lower Planes)  
- **Treasure.** Arcana  

While all yugoloths are fiendish manifestations of wickedness and greed, arcanaloths bend their considerable intellects toward hoarding and exploiting secrets. They then deploy these secrets to ensnare countless victims and lesser villains, beguiling foes with false promises and powerful magic.

Arcanaloths possess considerable spellcasting prowess and frequently disguise themselves with magic. While they prefer to let magical servants or other yugoloths do their fighting for them, arcanaloths can defend themselves with arcane might, banishing opponents into the pages of their magic tomes.

```statblock
"name": "Arcanaloth (XMM)"
"size": "Medium"
"type": "fiend"
"subtype": "yugoloth"
"alignment": "Neutral Evil"
"ac": !!int "18"
"hp": !!int "175"
"hit_dice": "27d8 + 54"
"modifier": !!int "5"
"stats":
  - !!int "17"
  - !!int "12"
  - !!int "14"
  - !!int "20"
  - !!int "16"
  - !!int "17"
"speed": "30 ft., fly 30 ft. (hover)"
"saves":
  - "dexterity": "+5"
  - "constitution": "+6"
  - "intelligence": "+9"
  - "wisdom": "+7"
"skillsaves":
  - "name": "[Arcana](Інструменти%20ДМ/CLI/rules/skills.md#Arcana)"
    "desc": "+9"
  - "name": "[Deception](Інструменти%20ДМ/CLI/rules/skills.md#Deception)"
    "desc": "+7"
  - "name": "[Insight](Інструменти%20ДМ/CLI/rules/skills.md#Insight)"
    "desc": "+7"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+7"
"damage_resistances": "cold, fire, lightning"
"damage_immunities": "acid, poison"
"condition_immunities": "[charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed),\
  \ [poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned)"
"senses": "truesight 120 ft., passive Perception 17"
"languages": "all; telepathy 120 ft."
"cr": "12"
"traits":
  - "desc": "If the arcanaloth dies outside Gehenna, its body dissolves into ichor,\
      \ and it gains a new body instantly and revives with all its [Hit Points](Ін\
      струменти%20ДМ/CLI/rules/variant-rules/hit-points-xphb.md) in Gehenna."
    "name": "Fiendish Restoration"
  - "desc": "The arcanaloth has [Advantage](Інструменти%20ДМ/CLI/rules/variant-rules/advantage-xphb.md)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "The arcanaloth has a magic tome. While holding or carrying the tome,\
      \ the arcanaloth can use its Banishing Claw action.\n\nThe tome has AC 17; HP\
      \ 35; and [Immunity](Інструменти%20ДМ/CLI/rules/variant-rules/immunity-xphb.md)\
      \ to Necrotic, Poison, and Psychic damage. The tome regains all its [Hit Points](І\
      нструменти%20ДМ/CLI/rules/variant-rules/hit-points-xphb.md) at the end of every\
      \ turn, but it turns to dust if reduced to 0 [Hit Points](Інструменти%20ДМ/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ or when the arcanaloth dies. If the tome is destroyed, the arcanaloth can\
      \ create a new one when it finishes a [Short](Інструменти%20ДМ/CLI/rules/variant-rules/short-rest-xphb.md)\
      \ or [Long Rest](Інструменти%20ДМ/CLI/rules/variant-rules/long-rest-xphb.md)."
    "name": "Soul Tome"
"actions":
  - "desc": "The arcanaloth makes three Fiendish Burst attacks. It can replace one\
      \ attack with a Banishing Claw attack."
    "name": "Multiattack"
  - "desc": "Melee  or Ranged Attack Roll: +9, reach 5 ft. or range 120 ft. Hit:\
      \ 31 (4d12 + 5) Necrotic damage."
    "name": "Fiendish Burst"
  - "desc": "Melee Attack Roll: +9, reach 5 ft. Hit: 10 (2d4 + 5) Slashing\
      \ damage plus 19 (3d12) Psychic damage. If the target is a creature, it is\
      \ subjected to the following effect. Charisma Saving Throw: DC 17. Failure:\
      \ The target is trapped in a demiplane inside the Soul Tome. While trapped there,\
      \ the target has the [Incapacitated](Інструменти%20ДМ/CLI/rules/conditions.md#Incapacitated)\
      \ condition. At the end of each of its turns, the target repeats the save, escaping\
      \ the tome on a success. When the target escapes, it appears in the space it\
      \ left or, if that space is occupied, the nearest unoccupied space.\n\nIf the\
      \ target fails three of these saves while in the demiplane, it becomes bound\
      \ to the tome and can escape only if the tome is reduced to 0 [Hit Points](І\
      нструменти%20ДМ/CLI/rules/variant-rules/hit-points-xphb.md)."
    "name": "Banishing Claw (Requires Soul Tome)"
  - "desc": "The arcanaloth casts one of the following spells, requiring no Material\
      \ components and using Intelligence as the spellcasting ability (spell save\
      \ DC 17):\n\nAt will: [Alter Self](Інструменти%20ДМ/CLI/spells/alter-self-xphb.md),\
      \ [Detect Magic](Інструменти%20ДМ/CLI/spells/detect-magic-xphb.md), [Identify](І\
      нструменти%20ДМ/CLI/spells/identify-xphb.md), [Mage Hand](Інструменти%20ДМ/CLI/spells/mage-hand-xphb.md),\
      \ [Prestidigitation](Інструменти%20ДМ/CLI/spells/prestidigitation-xphb.md)\n\
      \n1/day each: [Contact Other Plane](Інструменти%20ДМ/CLI/spells/contact-other-plane-xphb.md),\
      \ [Detect Thoughts](Інструменти%20ДМ/CLI/spells/detect-thoughts-xphb.md), [Dimension\
      \ Door](Інструменти%20ДМ/CLI/spells/dimension-door-xphb.md), [Mind Blank](Ін\
      струменти%20ДМ/CLI/spells/mind-blank-xphb.md)"
    "name": "Spellcasting"
  - "desc": "The arcanaloth casts [Counterspell](Інструменти%20ДМ/CLI/spells/counterspell-xphb.md)\
      \ in response to that spell's trigger, using the same spellcasting ability as\
      \ Spellcasting.\n"
    "name": "Counterspell"
"bonus_actions":
  - "desc": "The arcanaloth teleports up to 30 feet to an unoccupied space it can\
      \ see."
    "name": "Teleport"
"reactions":
  - "desc": "The arcanaloth casts one of the following spells, requiring no Material\
      \ components and using Intelligence as the spellcasting ability (spell save\
      \ DC 17):\n\nAt will: [Alter Self](Інструменти%20ДМ/CLI/spells/alter-self-xphb.md),\
      \ [Detect Magic](Інструменти%20ДМ/CLI/spells/detect-magic-xphb.md), [Identify](І\
      нструменти%20ДМ/CLI/spells/identify-xphb.md), [Mage Hand](Інструменти%20ДМ/CLI/spells/mage-hand-xphb.md),\
      \ [Prestidigitation](Інструменти%20ДМ/CLI/spells/prestidigitation-xphb.md)\n\
      \n1/day each: [Contact Other Plane](Інструменти%20ДМ/CLI/spells/contact-other-plane-xphb.md),\
      \ [Detect Thoughts](Інструменти%20ДМ/CLI/spells/detect-thoughts-xphb.md), [Dimension\
      \ Door](Інструменти%20ДМ/CLI/spells/dimension-door-xphb.md), [Mind Blank](Ін\
      струменти%20ДМ/CLI/spells/mind-blank-xphb.md)"
    "name": "Spellcasting"
  - "desc": "The arcanaloth casts [Counterspell](Інструменти%20ДМ/CLI/spells/counterspell-xphb.md)\
      \ in response to that spell's trigger, using the same spellcasting ability as\
      \ Spellcasting.\n"
    "name": "Counterspell"
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/fiend/token/arcanaloth-xmm.webp"
```
^statblock

## Environment

planar, lower