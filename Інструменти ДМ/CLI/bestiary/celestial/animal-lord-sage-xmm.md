---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/20
- ttrpg-cli/monster/environment/beastlands
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- Animal Lord; Sage
---
# [Animal Lord; Sage](Інструменти ДМ\CLI\bestiary\celestial/animal-lord-sage-xmm.md)
*Source: Monster Manual (2024) p. 15*  

```statblock
"name": "Animal Lord; Sage (XMM)"
"size": "Medium"
"type": "celestial"
"alignment": "Neutral"
"ac": !!int "19"
"hp": !!int "323"
"hit_dice": "34d8 + 170"
"modifier": !!int "19"
"stats":
  - !!int "24"
  - !!int "25"
  - !!int "20"
  - !!int "19"
  - !!int "23"
  - !!int "22"
"speed": "60 ft., fly 60 ft. (hover), swim 60 ft."
"saves":
  - "constitution": !!int "11"
  - "wisdom": !!int "12"
"skillsaves":
  - "name": "[Acrobatics](Інструменти%20ДМ/CLI/rules/skills.md#Acrobatics)"
    "desc": "+13"
  - "name": "[Athletics](Інструменти%20ДМ/CLI/rules/skills.md#Athletics)"
    "desc": "+13"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+18"
  - "name": "[Stealth](Інструменти%20ДМ/CLI/rules/skills.md#Stealth)"
    "desc": "+13"
"damage_resistances": "cold, fire, necrotic, psychic, radiant"
"condition_immunities": "[charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed),\
  \ [frightened](Інструменти%20ДМ/CLI/rules/conditions.md#Frightened), [stunned](І\
  нструменти%20ДМ/CLI/rules/conditions.md#Stunned)"
"senses": "truesight 120 ft., passive Perception 28"
"languages": "all"
"cr": "20"
"traits":
  - "desc": "An animal lord represents a Forager, Hunter, or Sage (DM's choice), which\
      \ determines certain traits in this stat block."
    "name": "Animal Lordship"
  - "desc": "If the animal lord fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (4/Day)"
  - "desc": "Wisdom Saving Throw: DC 20, any enemy that starts its turn in a 30-foot\
      \ [Emanation](Інструменти%20ДМ/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from the animal lord. Failure: The target takes dice:3d6|noform|noparens|avg|text(10)\
      \ (3d6) Psychic damage, and the target is magically bewildered until the end\
      \ of its next turn. While bewildered, the target subtracts dice:1d4|noform|noparens|avg\
      \ (d4) from its saving throws."
    "name": "Lordly Presence"
  - "desc": "The animal lord has [Advantage](Інструменти%20ДМ/CLI/rules/variant-rules/advantage-xphb.md)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The animal lord makes two attacks, using Rend or Radiant Ray in any combination,\
      \ and uses Animal Spirit."
    "name": "Multiattack"
  - "desc": "Melee Attack Roll: dice:1d20+13|noform|noparens|text(+13), reach\
      \ 5 ft. Hit: dice:2d6+7|noform|noparens|avg|text(14) (2d6 + 7) Slashing\
      \ damage plus dice:2d6|noform|noparens|avg|text(7) (2d6) Force damage."
    "name": "Rend"
  - "desc": "Ranged Attack Roll: dice:1d20+12|noform|noparens|text(+12), range\
      \ 120 ft. Hit: dice:4d6+6|noform|noparens|avg|text(20) (4d6 + 6) Radiant\
      \ damage."
    "name": "Radiant Ray"
  - "desc": "The animal lord conjures an animal spirit that strikes at a creature\
      \ and then disappears. Dexterity Saving Throw: DC 20, one creature the animal\
      \ lord can see within 120 feet. Failure: dice:4d10+6|noform|noparens|avg|text(28)\
      \ (4d10 + 6) Radiant damage. Success: Half damage. Failure or Success:\
      \ The target has [Disadvantage](Інструменти%20ДМ/CLI/rules/variant-rules/disadvantage-xphb.md)\
      \ on attack rolls and ability checks until the end of its next turn."
    "name": "Animal Spirit"
  - "desc": "The animal lord casts one of the following spells, requiring no Material\
      \ components and using Wisdom as the spellcasting ability (spell save DC 20):\n\
      \nAt will: [Animal Friendship](Інструменти%20ДМ/CLI/spells/animal-friendship-xphb.md),\
      \ [Animal Messenger](Інструменти%20ДМ/CLI/spells/animal-messenger-xphb.md),\
      \ [Speak with Animals](Інструменти%20ДМ/CLI/spells/speak-with-animals-xphb.md)\n\
      \n2/day each: [Awaken](Інструменти%20ДМ/CLI/spells/awaken-xphb.md), [Greater\
      \ Restoration](Інструменти%20ДМ/CLI/spells/greater-restoration-xphb.md)\n\n\
      1/day each: [Animal Shapes](Інструменти%20ДМ/CLI/spells/animal-shapes-xphb.md),\
      \ [Sunburst](Інструменти%20ДМ/CLI/spells/sunburst-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The animal lord shape-shifts into a Huge or smaller version of the animal\
      \ it represents or a Medium or Small Humanoid, or it returns to its true form.\
      \ Its game statistics, other than its size, are the same in each form. Any equipment\
      \ it is wearing or carrying isn't transformed."
    "name": "Shape-Shift"
"legendary_actions":
  - "desc": "The animal lord moves up to its [Speed](Інструменти%20ДМ/CLI/rules/variant-rules/speed-xphb.md)\
      \ without provoking [Opportunity Attacks](Інструменти%20ДМ/CLI/rules/actions.md#Opportunity%20Attack),\
      \ and it makes one Rend attack."
    "name": "Feral Strike"
  - "desc": "The animal lord makes one Radiant Ray attack."
    "name": "Radiant Strike"
"source":
  - "XMM"
```
^statblock

## Environment

planar, beastlands