---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Mage Apprentice
---
# [Mage Apprentice](Інструменти ДМ\CLI\bestiary\humanoid/mage-apprentice-xmm.md)
*Source: Monster Manual (2024) p. 198*  

Mage apprentices are spellcasters of humble skill. Some are students of accomplished mages, while others have innate powers.

## Mages

*Magical Scholars and Spellcasters*

- **Habitat.** Any  
- **Treasure.** Arcana, Individual  

Mages are magical wonder-workers, ranging from spellcasting overlords to reclusive witches. They study mystical secrets and possess insight into monsters, legends, omens, and other lore. Mages often gather allies or hire assistants to aid them in their research or to attain magical might.

Roll on or choose a result from the Mage Roles table to inspire different sorts of mages.

**Mage Roles**

`dice: [](mage-apprentice-xmm.md#^mage-roles)`

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
"name": "Mage Apprentice (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral"
"ac": !!int "15"
"hp": !!int "49"
"hit_dice": "9d8 + 9"
"modifier": !!int "2"
"stats":
  - !!int "8"
  - !!int "14"
  - !!int "12"
  - !!int "16"
  - !!int "13"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "intelligence": "+5"
  - "wisdom": "+3"
"skillsaves":
  - "name": "[Arcana](Інструменти%20ДМ/CLI/rules/skills.md#Arcana)"
    "desc": "+5"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+3"
"senses": "passive Perception 13"
"languages": "Common plus one other language"
"cr": "2"
"actions":
  - "desc": "Melee  or Ranged Attack Roll: +5, reach 5 ft. or range 120 ft. Hit:\
      \ 14 (2d10 + 3) Force damage."
    "name": "Arcane Burst"
  - "desc": "The mage casts one of the following spells, using Intelligence as the\
      \ spellcasting ability (spell save DC 13, +5 to hit with spell attacks):\n\
      \nAt will: [Mage Hand](Інструменти%20ДМ/CLI/spells/mage-hand-xphb.md), [Prestidigitation](І\
      нструменти%20ДМ/CLI/spells/prestidigitation-xphb.md)\n\n1/day each: [Disguise\
      \ Self](Інструменти%20ДМ/CLI/spells/disguise-self-xphb.md), [Ice Knife](Інст\
      рументи%20ДМ/CLI/spells/ice-knife-xphb.md), [Mage Armor](Інструменти%20ДМ/CLI/spells/mage-armor-xphb.md)\
      \ (included in AC), [Thunderwave](Інструменти%20ДМ/CLI/spells/thunderwave-xphb.md)"
    "name": "Spellcasting"
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/mage-apprentice-xmm.webp"
```
^statblock

## Environment

any