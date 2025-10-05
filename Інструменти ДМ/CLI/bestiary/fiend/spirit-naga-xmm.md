---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/environment/lower
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- Spirit Naga
---
# [Spirit Naga](Інструменти ДМ\CLI\bestiary\fiend/spirit-naga-xmm.md)
*Source: Monster Manual (2024) p. 297. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Spirit Naga

*Spiteful Serpentine Grudge Keeper*

- **Habitat.** Planar (Lower Planes), Underdark  
- **Treasure.** Arcana  

Spirit nagas loathe the world and all creatures. Possessing perfect memories, these venomous, cobra-like creatures recall every slight committed against them during their immortal existences. In their dank, joyless lairs, they create vicious plots to avenge themselves against even petty offenses.

Spirit nagas seek to claim what they believe they deserve. Their schemes often involve poisons, vile spells, cursed objects, or magical compulsions, eventually making them wellsprings of diabolical knowledge and evil inspiration. Other villains often seek out spirit nagas as advisers and allies. Roll on or choose a result from the Spirit Naga Grievances table to inspire what motivates a spirit naga's schemes.

**Spirit Naga Grievances**

`dice: [](spirit-naga-xmm.md#^spirit-naga-grievances)`

| dice: 1d6 | The Spirit Naga Believes... |
|-----------|-----------------------------|
| 1 | A character is to blame for its recent failures. |
| 2 | It has been evicted from its rightful home. |
| 3 | Locals have reneged on an age-old bargain. |
| 4 | Other creatures are mocking it. |
| 5 | A rival is spying on it. |
| 6 | Someone's treasure rightfully belongs to it. |
^spirit-naga-grievances

```statblock
"name": "Spirit Naga (XMM)"
"size": "Large"
"type": "fiend"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"hp": !!int "135"
"hit_dice": "18d10 + 36"
"modifier": !!int "3"
"stats":
  - !!int "18"
  - !!int "17"
  - !!int "14"
  - !!int "16"
  - !!int "15"
  - !!int "16"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "6"
  - "constitution": !!int "5"
  - "wisdom": !!int "5"
  - "charisma": !!int "6"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed),\
  \ [poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Abyssal, Common"
"cr": "8"
"traits":
  - "desc": "If it dies, the naga returns to life in dice:1d6|noform|noparens|avg\
      \ (d6) days and regains all its [Hit Points](Інструменти%20ДМ/CLI/rules/variant-rules/hit-points-xphb.md).\
      \ Only a [Wish](Інструменти%20ДМ/CLI/spells/wish-xphb.md) spell can prevent\
      \ this trait from functioning."
    "name": "Fiendish Restoration"
"actions":
  - "desc": "The naga makes three attacks, using Bite or Necrotic Ray in any combination."
    "name": "Multiattack"
  - "desc": "Melee Attack Roll: dice:1d20+7|noform|noparens|text(+7), reach 10\
      \ ft. Hit: dice:1d6+4|noform|noparens|avg|text(7) (1d6 + 4) Piercing damage\
      \ plus dice:4d6|noform|noparens|avg|text(14) (4d6) Poison damage."
    "name": "Bite"
  - "desc": "Ranged Attack Roll: dice:1d20+6|noform|noparens|text(+6), range 60\
      \ ft. Hit: dice:6d6|noform|noparens|avg|text(21) (6d6) Necrotic damage."
    "name": "Necrotic Ray"
  - "desc": "The naga casts one of the following spells, requiring no Somatic or Material\
      \ components and using Intelligence as the spellcasting ability (spell save\
      \ DC 14):\n\nAt will: [Detect Magic](Інструменти%20ДМ/CLI/spells/detect-magic-xphb.md),\
      \ [Mage Hand](Інструменти%20ДМ/CLI/spells/mage-hand-xphb.md), [Minor Illusion](І\
      нструменти%20ДМ/CLI/spells/minor-illusion-xphb.md), [Water Breathing](Інстру\
      менти%20ДМ/CLI/spells/water-breathing-xphb.md)\n\n2/day each: [Detect Thoughts](І\
      нструменти%20ДМ/CLI/spells/detect-thoughts-xphb.md), [Dimension Door](Інстру\
      менти%20ДМ/CLI/spells/dimension-door-xphb.md), [Hold Person](Інструменти%20Д\
      М/CLI/spells/hold-person-xphb.md) (level 3 version), [Lightning Bolt](Інстру\
      менти%20ДМ/CLI/spells/lightning-bolt-xphb.md) (level 4 version)"
    "name": "Spellcasting"
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/fiend/token/spirit-naga-xmm.webp"
```
^statblock

## Environment

planar, lower, underdark