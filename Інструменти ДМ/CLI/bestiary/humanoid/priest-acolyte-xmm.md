---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Priest Acolyte
---
# [Priest Acolyte](Інструменти ДМ\CLI\bestiary\humanoid/priest-acolyte-xmm.md)
*Source: Monster Manual (2024) p. 247. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

Priest acolytes have great faith but modest magical skill. Some might be trainees in religious organizations or soldiers in zealous armies, while others are faith leaders in small communities or wanderers on pilgrimages.

## Priests

*Arbiters of the Mortal and the Divine*

- **Habitat.** Any  
- **Treasure.** Individual, Relics  

Priests harness the power of faith to work miracles. These religious adherents are as diverse as the faiths they follow. Some obey gods and their servants, while others live by age-old creeds. Belief guides priests' actions and their magic, which they use to shape the world in line with their ideologies.

Roll on or choose a result from the Priest Roles table to inspire different sorts of priests.

**Priest Roles**

`dice: [](priest-acolyte-xmm.md#^priest-roles)`

| dice: 1d10 | The Priest Is... |
|------------|------------------|
| 1 | An ascetic who keeps wicked spirits at bay. |
| 2 | An elder who speaks for the dead. |
| 3 | An exorcist who hunts wicked spirits. |
| 4 | A follower of a god no one has heard of. |
| 5 | A mediator and teacher of traditional ways. |
| 6 | A philosopher devoted to a concept, multiversal view, or plane of existence. |
| 7 | The reincarnation of an ancient faith leader. |
| 8 | A ritualist who uses tinctures and performances to access the divine. |
| 9 | A shaman whose medicines ease many ills. |
| 10 | A zealot who wages war for a divine cause. |
^priest-roles

> [!quote]  
> 
> Shining One, light my hours. Enkindle my soul, and inspire my deeds. Chase the shadows from my path, and let me walk in your brilliance.


```statblock
"name": "Priest Acolyte (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral"
"ac": !!int "13"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"modifier": !!int "0"
"stats":
  - !!int "14"
  - !!int "10"
  - !!int "12"
  - !!int "10"
  - !!int "14"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Medicine](Інструменти%20ДМ/CLI/rules/skills.md#Medicine)"
    "desc": "+4"
  - "name": "[Religion](Інструменти%20ДМ/CLI/rules/skills.md#Religion)"
    "desc": "+2"
"senses": "passive Perception 12"
"languages": "Common"
"cr": "1/4"
"actions":
  - "desc": "Melee Attack Roll: +4, reach 5 ft. Hit: 5 (1d6 + 2) Bludgeoning\
      \ damage plus 2 (d4) Radiant damage."
    "name": "Mace"
  - "desc": "Ranged Attack Roll: +4, range 60 ft. Hit: 7 (2d6) Radiant damage."
    "name": "Radiant Flame"
  - "desc": "The priest casts one of the following spells, using Wisdom as the spellcasting\
      \ ability:\n\nAt will: [Light](Інструменти%20ДМ/CLI/spells/light-xphb.md),\
      \ [Thaumaturgy](Інструменти%20ДМ/CLI/spells/thaumaturgy-xphb.md)"
    "name": "Spellcasting"
  - "desc": "The priest casts [Bless](Інструменти%20ДМ/CLI/spells/bless-xphb.md),\
      \ [Healing Word](Інструменти%20ДМ/CLI/spells/healing-word-xphb.md), or [Sanctuary](І\
      нструменти%20ДМ/CLI/spells/sanctuary-xphb.md), using the same spellcasting ability\
      \ as Spellcasting.\n"
    "name": "Divine Aid (1/Day)"
"bonus_actions":
  - "desc": "The priest casts one of the following spells, using Wisdom as the spellcasting\
      \ ability:\n\nAt will: [Light](Інструменти%20ДМ/CLI/spells/light-xphb.md),\
      \ [Thaumaturgy](Інструменти%20ДМ/CLI/spells/thaumaturgy-xphb.md)"
    "name": "Spellcasting"
  - "desc": "The priest casts [Bless](Інструменти%20ДМ/CLI/spells/bless-xphb.md),\
      \ [Healing Word](Інструменти%20ДМ/CLI/spells/healing-word-xphb.md), or [Sanctuary](І\
      нструменти%20ДМ/CLI/spells/sanctuary-xphb.md), using the same spellcasting ability\
      \ as Spellcasting.\n"
    "name": "Divine Aid (1/Day)"
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/priest-acolyte-xmm.webp"
```
^statblock

## Environment

any