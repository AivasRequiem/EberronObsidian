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
- Archpriest
---
# [Archpriest](Інструменти ДМ\CLI\bestiary\humanoid/archpriest-xmm.md)
*Source: Monster Manual (2024) p. 248*  

By forging connections with divine beings and mastering mystical truths, archpriests become conduits for godly intentions and other supernatural forces. Their magic allows them to work wonders, whether to share the benevolence of their faiths or to vent divine wrath. Some archpriests attract vast followings as they claim to speak for divine forces, while others undertake personal spiritual journeys and seek to transcend mortal concerns.

## Priests

*Arbiters of the Mortal and the Divine*

- **Habitat.** Any  
- **Treasure.** Individual, Relics  

Priests harness the power of faith to work miracles. These religious adherents are as diverse as the faiths they follow. Some obey gods and their servants, while others live by age-old creeds. Belief guides priests' actions and their magic, which they use to shape the world in line with their ideologies.

Roll on or choose a result from the Priest Roles table to inspire different sorts of priests.

**Priest Roles**

`dice: [](archpriest-xmm.md#^priest-roles)`

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
"name": "Archpriest (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral"
"ac": !!int "16"
"hp": !!int "240"
"hit_dice": "32d8 + 96"
"modifier": !!int "5"
"stats":
  - !!int "16"
  - !!int "12"
  - !!int "17"
  - !!int "14"
  - !!int "21"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "strength": "+7"
  - "constitution": "+7"
  - "intelligence": "+6"
  - "wisdom": "+9"
"skillsaves":
  - "name": "[Insight](Інструменти%20ДМ/CLI/rules/skills.md#Insight)"
    "desc": "+9"
  - "name": "[Medicine](Інструменти%20ДМ/CLI/rules/skills.md#Medicine)"
    "desc": "+9"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+9"
  - "name": "[Religion](Інструменти%20ДМ/CLI/rules/skills.md#Religion)"
    "desc": "+10"
"senses": "passive Perception 19"
"languages": "Common plus two other languages"
"cr": "12"
"actions":
  - "desc": "The archpriest makes three Radiant Burst attacks."
    "name": "Multiattack"
  - "desc": "Melee  or Ranged Attack Roll: +9, reach 5 ft. or range 60 ft. Hit:\
      \ 27 (4d10 + 5) Radiant damage."
    "name": "Radiant Burst"
  - "desc": "Wisdom Saving Throw: DC 17, each enemy in a 20-foot [Emanation](Інс\
      трументи%20ДМ/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating\
      \ from the archpriest. Failure: 21 (6d6) Radiant damage, and the target\
      \ has the [Stunned](Інструменти%20ДМ/CLI/rules/conditions.md#Stunned) condition\
      \ until the end of the archpriest's next turn. Success: Half damage only."
    "name": "Holy Word (Recharge 4-6)"
  - "desc": "The archpriest casts one of the following spells, requiring no Material\
      \ components and using Wisdom as the spellcasting ability (spell save DC 17):\n\
      \nAt will: [Light](Інструменти%20ДМ/CLI/spells/light-xphb.md), [Thaumaturgy](І\
      нструменти%20ДМ/CLI/spells/thaumaturgy-xphb.md)\n\n1/day each: [Flame Strike](І\
      нструменти%20ДМ/CLI/spells/flame-strike-xphb.md) (level 6 version), [Greater\
      \ Restoration](Інструменти%20ДМ/CLI/spells/greater-restoration-xphb.md), [Raise\
      \ Dead](Інструменти%20ДМ/CLI/spells/raise-dead-xphb.md), [Zone of Truth](Інс\
      трументи%20ДМ/CLI/spells/zone-of-truth-xphb.md)"
    "name": "Spellcasting"
  - "desc": "The priest casts [Bless](Інструменти%20ДМ/CLI/spells/bless-xphb.md),\
      \ [Dispel Magic](Інструменти%20ДМ/CLI/spells/dispel-magic-xphb.md), [Healing\
      \ Word](Інструменти%20ДМ/CLI/spells/healing-word-xphb.md), or [Lesser Restoration](І\
      нструменти%20ДМ/CLI/spells/lesser-restoration-xphb.md), using the same spellcasting\
      \ ability as Spellcasting.\n"
    "name": "Divine Aid (3/Day)"
"bonus_actions":
  - "desc": "The archpriest casts one of the following spells, requiring no Material\
      \ components and using Wisdom as the spellcasting ability (spell save DC 17):\n\
      \nAt will: [Light](Інструменти%20ДМ/CLI/spells/light-xphb.md), [Thaumaturgy](І\
      нструменти%20ДМ/CLI/spells/thaumaturgy-xphb.md)\n\n1/day each: [Flame Strike](І\
      нструменти%20ДМ/CLI/spells/flame-strike-xphb.md) (level 6 version), [Greater\
      \ Restoration](Інструменти%20ДМ/CLI/spells/greater-restoration-xphb.md), [Raise\
      \ Dead](Інструменти%20ДМ/CLI/spells/raise-dead-xphb.md), [Zone of Truth](Інс\
      трументи%20ДМ/CLI/spells/zone-of-truth-xphb.md)"
    "name": "Spellcasting"
  - "desc": "The priest casts [Bless](Інструменти%20ДМ/CLI/spells/bless-xphb.md),\
      \ [Dispel Magic](Інструменти%20ДМ/CLI/spells/dispel-magic-xphb.md), [Healing\
      \ Word](Інструменти%20ДМ/CLI/spells/healing-word-xphb.md), or [Lesser Restoration](І\
      нструменти%20ДМ/CLI/spells/lesser-restoration-xphb.md), using the same spellcasting\
      \ ability as Spellcasting.\n"
    "name": "Divine Aid (3/Day)"
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/archpriest-xmm.webp"
```
^statblock

## Environment

any