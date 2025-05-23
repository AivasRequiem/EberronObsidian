---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Archmage
---
# [Archmage](Інструменти ДМ\CLI\bestiary\humanoid/archmage-xmm.md)
*Source: Monster Manual (2024) p. 199. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

Archmages have mastered incredible magical power. While some use their magic to protect the world, others become tyrants or pursue forbidden secrets. Many archmages retain magical servants and collect magic items and occult lore.

## Mages

*Magical Scholars and Spellcasters*

- **Habitat.** Any  
- **Treasure.** Arcana, Individual  

Mages are magical wonder-workers, ranging from spellcasting overlords to reclusive witches. They study mystical secrets and possess insight into monsters, legends, omens, and other lore. Mages often gather allies or hire assistants to aid them in their research or to attain magical might.

Roll on or choose a result from the Mage Roles table to inspire different sorts of mages.

**Mage Roles**

`dice: [](archmage-xmm.md#^mage-roles)`

| dice: 1d10 | The Mage Is... |
|------------|----------------|
| 1 | An astronomer who draws magic from stars. |
| 2 | An author who writes about the occult. |
| 3 | A magical engineer who creates wonders. |
| 4 | An oracle who interprets omens. |
| 5 | A prodigy with a remarkable magical heritage. |
| 6 | A psion whose powers manifest as spells. |
| 7 | A scholar investigating ancient lore. |
| 8 | A soothsayer who advises rulers. |
| 9 | A war mage who aids soldiers in battle. |
| 10 | A witch who shares secret wisdom. |
^mage-roles

> [!quote] A quote from Nathor, Thayan Refugee  
> 
> Have you gazed on the Runes of Chaos, held the Death Moon Orb in your trembling hands, entered the Devouring Portal and walked the Paths of the Doomed, or sat at the left hand of Szass Tam during the Ritual of Twin Burnings? No? Then speak not to me of wizards. Speak not to me of Thay.


```statblock
"name": "Archmage (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral"
"ac": !!int "17"
"hp": !!int "170"
"hit_dice": "31d8 + 31"
"modifier": !!int "6"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "12"
  - !!int "20"
  - !!int "15"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "intelligence": "+9"
  - "wisdom": "+6"
"skillsaves":
  - "name": "[Arcana](Інструменти%20ДМ/CLI/rules/skills.md#Arcana)"
    "desc": "+13"
  - "name": "[History](Інструменти%20ДМ/CLI/rules/skills.md#History)"
    "desc": "+9"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+6"
"damage_immunities": "psychic"
"condition_immunities": "[charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed)\
  \ (with Mind Blank)"
"senses": "passive Perception 16"
"languages": "Common plus five other languages"
"cr": "12"
"traits":
  - "desc": "The archmage has [Advantage](Інструменти%20ДМ/CLI/rules/variant-rules/advantage-xphb.md)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The archmage makes four Arcane Burst attacks."
    "name": "Multiattack"
  - "desc": "Melee  or Ranged Attack Roll: +9, reach 5 ft. or range 150 ft. Hit:\
      \ 27 (4d10 + 5) Force damage."
    "name": "Arcane Burst"
  - "desc": "The archmage casts one of the following spells, using Intelligence as\
      \ the spellcasting ability (spell save DC 17):\n\nAt will: [Detect Magic](І\
      нструменти%20ДМ/CLI/spells/detect-magic-xphb.md), [Detect Thoughts](Інструме\
      нти%20ДМ/CLI/spells/detect-thoughts-xphb.md), [Disguise Self](Інструменти%20Д\
      М/CLI/spells/disguise-self-xphb.md), [Invisibility](Інструменти%20ДМ/CLI/spells/invisibility-xphb.md),\
      \ [Light](Інструменти%20ДМ/CLI/spells/light-xphb.md), [Mage Armor](Інструмен\
      ти%20ДМ/CLI/spells/mage-armor-xphb.md) (included in AC), [Mage Hand](Інструм\
      енти%20ДМ/CLI/spells/mage-hand-xphb.md), [Prestidigitation](Інструменти%20ДМ\
      /CLI/spells/prestidigitation-xphb.md)\n\n2/day each: [Fly](Інструменти%20Д\
      М/CLI/spells/fly-xphb.md), [Lightning Bolt](Інструменти%20ДМ/CLI/spells/lightning-bolt-xphb.md)\
      \ (level 7 version)\n\n1/day each: [Cone of Cold](Інструменти%20ДМ/CLI/spells/cone-of-cold-xphb.md)\
      \ (level 9 version), [Mind Blank](Інструменти%20ДМ/CLI/spells/mind-blank-xphb.md)\
      \ (cast before combat), [Scrying](Інструменти%20ДМ/CLI/spells/scrying-xphb.md),\
      \ [Teleport](Інструменти%20ДМ/CLI/spells/teleport-xphb.md)"
    "name": "Spellcasting"
  - "desc": "The mage casts [Misty Step](Інструменти%20ДМ/CLI/spells/misty-step-xphb.md),\
      \ using the same spellcasting ability as Spellcasting.\n"
    "name": "Misty Step (3/Day)"
  - "desc": "The archmage casts [Counterspell](Інструменти%20ДМ/CLI/spells/counterspell-xphb.md)\
      \ or [Shield](Інструменти%20ДМ/CLI/spells/shield-xphb.md) in response to the\
      \ spell's trigger, using the same spellcasting ability as Spellcasting.\n"
    "name": "Protective Magic (3/Day)"
"bonus_actions":
  - "desc": "The archmage casts one of the following spells, using Intelligence as\
      \ the spellcasting ability (spell save DC 17):\n\nAt will: [Detect Magic](І\
      нструменти%20ДМ/CLI/spells/detect-magic-xphb.md), [Detect Thoughts](Інструме\
      нти%20ДМ/CLI/spells/detect-thoughts-xphb.md), [Disguise Self](Інструменти%20Д\
      М/CLI/spells/disguise-self-xphb.md), [Invisibility](Інструменти%20ДМ/CLI/spells/invisibility-xphb.md),\
      \ [Light](Інструменти%20ДМ/CLI/spells/light-xphb.md), [Mage Armor](Інструмен\
      ти%20ДМ/CLI/spells/mage-armor-xphb.md) (included in AC), [Mage Hand](Інструм\
      енти%20ДМ/CLI/spells/mage-hand-xphb.md), [Prestidigitation](Інструменти%20ДМ\
      /CLI/spells/prestidigitation-xphb.md)\n\n2/day each: [Fly](Інструменти%20Д\
      М/CLI/spells/fly-xphb.md), [Lightning Bolt](Інструменти%20ДМ/CLI/spells/lightning-bolt-xphb.md)\
      \ (level 7 version)\n\n1/day each: [Cone of Cold](Інструменти%20ДМ/CLI/spells/cone-of-cold-xphb.md)\
      \ (level 9 version), [Mind Blank](Інструменти%20ДМ/CLI/spells/mind-blank-xphb.md)\
      \ (cast before combat), [Scrying](Інструменти%20ДМ/CLI/spells/scrying-xphb.md),\
      \ [Teleport](Інструменти%20ДМ/CLI/spells/teleport-xphb.md)"
    "name": "Spellcasting"
  - "desc": "The mage casts [Misty Step](Інструменти%20ДМ/CLI/spells/misty-step-xphb.md),\
      \ using the same spellcasting ability as Spellcasting.\n"
    "name": "Misty Step (3/Day)"
  - "desc": "The archmage casts [Counterspell](Інструменти%20ДМ/CLI/spells/counterspell-xphb.md)\
      \ or [Shield](Інструменти%20ДМ/CLI/spells/shield-xphb.md) in response to the\
      \ spell's trigger, using the same spellcasting ability as Spellcasting.\n"
    "name": "Protective Magic (3/Day)"
"reactions":
  - "desc": "The archmage casts one of the following spells, using Intelligence as\
      \ the spellcasting ability (spell save DC 17):\n\nAt will: [Detect Magic](І\
      нструменти%20ДМ/CLI/spells/detect-magic-xphb.md), [Detect Thoughts](Інструме\
      нти%20ДМ/CLI/spells/detect-thoughts-xphb.md), [Disguise Self](Інструменти%20Д\
      М/CLI/spells/disguise-self-xphb.md), [Invisibility](Інструменти%20ДМ/CLI/spells/invisibility-xphb.md),\
      \ [Light](Інструменти%20ДМ/CLI/spells/light-xphb.md), [Mage Armor](Інструмен\
      ти%20ДМ/CLI/spells/mage-armor-xphb.md) (included in AC), [Mage Hand](Інструм\
      енти%20ДМ/CLI/spells/mage-hand-xphb.md), [Prestidigitation](Інструменти%20ДМ\
      /CLI/spells/prestidigitation-xphb.md)\n\n2/day each: [Fly](Інструменти%20Д\
      М/CLI/spells/fly-xphb.md), [Lightning Bolt](Інструменти%20ДМ/CLI/spells/lightning-bolt-xphb.md)\
      \ (level 7 version)\n\n1/day each: [Cone of Cold](Інструменти%20ДМ/CLI/spells/cone-of-cold-xphb.md)\
      \ (level 9 version), [Mind Blank](Інструменти%20ДМ/CLI/spells/mind-blank-xphb.md)\
      \ (cast before combat), [Scrying](Інструменти%20ДМ/CLI/spells/scrying-xphb.md),\
      \ [Teleport](Інструменти%20ДМ/CLI/spells/teleport-xphb.md)"
    "name": "Spellcasting"
  - "desc": "The mage casts [Misty Step](Інструменти%20ДМ/CLI/spells/misty-step-xphb.md),\
      \ using the same spellcasting ability as Spellcasting.\n"
    "name": "Misty Step (3/Day)"
  - "desc": "The archmage casts [Counterspell](Інструменти%20ДМ/CLI/spells/counterspell-xphb.md)\
      \ or [Shield](Інструменти%20ДМ/CLI/spells/shield-xphb.md) in response to the\
      \ spell's trigger, using the same spellcasting ability as Spellcasting.\n"
    "name": "Protective Magic (3/Day)"
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/archmage-xmm.webp"
```
^statblock

## Environment

any