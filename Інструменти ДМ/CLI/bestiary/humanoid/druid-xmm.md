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
- Druid
---
# [Druid](Інструменти ДМ\CLI\bestiary\humanoid/druid-xmm.md)
*Source: Monster Manual (2024) p. 106. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Druid

*Steward and Sage of Nature*

- **Habitat.** Any  
- **Treasure.** Individual, Relics  

Druids use primal magic, traditional teachings, and bonds with animals and eldritch beings to guard the natural world and heal its ills. These magic-users might be recluses devoted to a particular land, or they might be part of a mystic organization. Roll on or choose a result from the Druidic Traditions table to inspire a druid's magical practices.

**Druid Traditions**

`dice: [](druid-xmm.md#^druid-traditions)`

| dice: 1d6 | The Druid Is... |
|-----------|-----------------|
| 1 | An avenger who strikes against destructive civilizations and those who abuse nature. |
| 2 | A guide who aids travelers in navigating the realms of Beasts, Fey, or Plants. |
| 3 | A hermit who works alone to protect the lands, seas, or skies they call home. |
| 4 | A mender who travels the world healing natural, magical, or manufactured disasters. |
| 5 | Part of a loose organization that adheres to timeless rituals and guards natural secrets. |
| 6 | A warden who minds the underpinnings of reality and protects against extraplanar threats. |
^druid-traditions

```statblock
"name": "Druid (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral"
"ac": !!int "13"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"modifier": !!int "1"
"stats":
  - !!int "10"
  - !!int "12"
  - !!int "13"
  - !!int "12"
  - !!int "16"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Medicine](Інструменти%20ДМ/CLI/rules/skills.md#Medicine)"
    "desc": "+5"
  - "name": "[Nature](Інструменти%20ДМ/CLI/rules/skills.md#Nature)"
    "desc": "+3"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+5"
"senses": "passive Perception 15"
"languages": "Common, Druidic, Sylvan"
"cr": "2"
"actions":
  - "desc": "The druid makes two attacks, using Vine Staff or Verdant Wisp in any\
      \ combination."
    "name": "Multiattack"
  - "desc": "Melee Attack Roll: +5, reach 5 ft. Hit: 7 (1d8 + 3) Bludgeoning\
      \ damage plus 2 (d4) Poison damage."
    "name": "Vine Staff"
  - "desc": "Ranged Attack Roll: +5, range 90 ft. Hit: 10 (3d6) Radiant damage."
    "name": "Verdant Wisp"
  - "desc": "The druid casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 13):\n\nAt will: [Druidcraft](Інструменти%20ДМ\
      /CLI/spells/druidcraft-xphb.md), [Speak with Animals](Інструменти%20ДМ/CLI/spells/speak-with-animals-xphb.md)\n\
      \n2/day each: [Entangle](Інструменти%20ДМ/CLI/spells/entangle-xphb.md),\
      \ [Thunderwave](Інструменти%20ДМ/CLI/spells/thunderwave-xphb.md)\n\n1/day\
      \ each: [Animal Messenger](Інструменти%20ДМ/CLI/spells/animal-messenger-xphb.md),\
      \ [Longstrider](Інструменти%20ДМ/CLI/spells/longstrider-xphb.md), [Moonbeam](І\
      нструменти%20ДМ/CLI/spells/moonbeam-xphb.md)"
    "name": "Spellcasting"
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/druid-xmm.webp"
```
^statblock

## Environment

any