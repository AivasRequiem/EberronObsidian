---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- Cloaker
---
# [Cloaker](Інструменти ДМ\CLI\bestiary\aberration/cloaker-xmm.md)
*Source: Monster Manual (2024) p. 73. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Cloaker

*Haunter in the Dark*

- **Habitat.** Underdark  
- **Treasure.** Implements  

Cloakers are mysterious Underdark predators, named by adventurers for their resemblance to hanging cloaks when they cling to walls. What cloakers call themselves is unknown, if they refer to themselves at all. Though they're undeniably intelligent, their behavior is often inscrutable.

Cloakers sometimes gather in Underdark enclaves, but they rarely build settlements or form social structures. Most operate as solitary predators, lurking in dismal subterranean reaches or abandoned dungeons—sometimes for months at a time—as they wait for prey to pass. They use their mottled hides to blend in with their surroundings. When unsuspecting prey nears, cloakers unfurl and attempt to latch on and then smother their victims in their powerful wings.

Cloakers delight in frightening foes. In addition to their methods of ambush, cloakers can create illusory duplicates of themselves and emit surreal moans that non-cloakers find terrifying in unexplainable, primal ways. Cloakers might antagonize explorers lost in the Underdark for days, terrorizing and scattering them before attacking. They rarely converse with other beings, except to whisper eerie riddles to those they're about to consume.

```statblock
"name": "Cloaker (XMM)"
"size": "Large"
"type": "aberration"
"alignment": "Chaotic Neutral"
"ac": !!int "14"
"hp": !!int "91"
"hit_dice": "14d10 + 14"
"modifier": !!int "5"
"stats":
  - !!int "17"
  - !!int "15"
  - !!int "12"
  - !!int "13"
  - !!int "14"
  - !!int "7"
"speed": "10 ft., fly 40 ft."
"skillsaves":
  - "name": "[Stealth](Інструменти%20ДМ/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"condition_immunities": "[frightened](Інструменти%20ДМ/CLI/rules/conditions.md#Frightened)"
"senses": "darkvision 120 ft., passive Perception 12"
"languages": "Deep Speech, Undercommon"
"cr": "8"
"traits":
  - "desc": "While in [Bright Light](Інструменти%20ДМ/CLI/rules/variant-rules/bright-light-xphb.md),\
      \ the cloaker has [Disadvantage](Інструменти%20ДМ/CLI/rules/variant-rules/disadvantage-xphb.md)\
      \ on attack rolls."
    "name": "Light Sensitivity"
"actions":
  - "desc": "The cloaker makes one Attach attack and two Tail attacks."
    "name": "Multiattack"
  - "desc": "Melee Attack Roll: +6, reach 5 ft. Hit: 13 (3d6 + 3) Piercing\
      \ damage. If the target is a Large or smaller creature, the cloaker attaches\
      \ to it. While the cloaker is attached, the target has the [Blinded](Інструм\
      енти%20ДМ/CLI/rules/conditions.md#Blinded) condition, and the cloaker can't\
      \ make Attach attacks against other targets. In addition, the cloaker halves\
      \ the damage it takes (round down), and the target takes the same amount of\
      \ damage.\n\nThe cloaker can detach itself by spending 5 feet of movement. The\
      \ target or a creature within 5 feet of it can take an action to try to detach\
      \ the cloaker, doing so by succeeding on a DC 14 Strength ([Athletics](Інстр\
      ументи%20ДМ/CLI/rules/skills.md#Athletics)) check."
    "name": "Attach"
  - "desc": "Melee Attack Roll: +6, reach 10 ft. Hit: 8 (1d10 + 3) Slashing\
      \ damage."
    "name": "Tail"
"bonus_actions":
  - "desc": "Wisdom Saving Throw: DC 13, each creature in a 60-foot [Emanation](І\
      нструменти%20ДМ/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating\
      \ from the cloaker. Failure: The target has the [Frightened](Інструменти%20Д\
      М/CLI/rules/conditions.md#Frightened) condition until the end of the cloaker's\
      \ next turn. Success: The target is immune to this cloaker's Moan for the\
      \ next 24 hours."
    "name": "Moan"
  - "desc": "The cloaker casts the [Mirror Image](Інструменти%20ДМ/CLI/spells/mirror-image-xphb.md)\
      \ spell, requiring no spell components and using Wisdom as the spellcasting\
      \ ability. The spell ends early if the cloaker starts or ends its turn in [Bright\
      \ Light](Інструменти%20ДМ/CLI/rules/variant-rules/bright-light-xphb.md).\n"
    "name": "Phantasms (Recharge after a Short or Long Rest)"
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/aberration/token/cloaker-xmm.webp"
```
^statblock

## Environment

underdark