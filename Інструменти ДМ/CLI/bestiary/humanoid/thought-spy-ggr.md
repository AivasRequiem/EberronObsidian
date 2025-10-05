---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- Thought Spy
---
# [Thought Spy](Інструменти ДМ\CLI\bestiary\humanoid/thought-spy-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 233*  

Thought spies form the backbone of House Dimir's covert operations. They are trained in stealth and infiltration, tactics that they supplement with rigorously developed mental abilities. To ensure that no secrets slip through Dimir's fingers, they infiltrate rival guilds. In addition to traditional means of gathering intelligence, thought spies use their magic to spy on the thoughts of their targets.

```statblock
"name": "Thought Spy (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Evil"
"ac": !!int "13"
"ac_class": "[leather armor](Інструменти%20ДМ/CLI/items/leather-armor-xphb.md)"
"hp": !!int "27"
"hit_dice": "6d8"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "10"
  - !!int "16"
  - !!int "13"
  - !!int "14"
"speed": "30 ft."
"skillsaves":
  - "name": "[Deception](Інструменти%20ДМ/CLI/rules/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Insight](Інструменти%20ДМ/CLI/rules/skills.md#Insight)"
    "desc": "+3"
  - "name": "[Investigation](Інструменти%20ДМ/CLI/rules/skills.md#Investigation)"
    "desc": "+5"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Sleight of Hand](Інструменти%20ДМ/CLI/rules/skills.md#Sleight%20of%20Hand)"
    "desc": "+4"
  - "name": "[Stealth](Інструменти%20ДМ/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"senses": "darkvision 30 ft., passive Perception 13"
"languages": "Common plus any one language"
"cr": "1"
"traits":
  - "desc": "The thought spy's innate spellcasting ability is Intelligence (spell\
      \ save DC 13). The thought spy can innately cast the following spells, requiring\
      \ no components:\n\nAt will: [charm person](Інструменти%20ДМ/CLI/spells/charm-person-xphb.md),\
      \ [disguise self](Інструменти%20ДМ/CLI/spells/disguise-self-xphb.md), [encode\
      \ thoughts](Інструменти%20ДМ/CLI/spells/encode-thoughts-ggr.md) (see chapter\
      \ 2)\n\n1/day each: [blur](Інструменти%20ДМ/CLI/spells/blur-xphb.md), [detect\
      \ thoughts](Інструменти%20ДМ/CLI/spells/detect-thoughts-xphb.md), [gaseous form](І\
      нструменти%20ДМ/CLI/spells/gaseous-form-xphb.md)"
    "name": "Innate Spellcasting (Psionics)"
  - "desc": "On each of its turns, the thought spy can use a bonus action to take\
      \ the Dash, Disengage, or Hide action."
    "name": "Cunning Action"
"actions":
  - "desc": "The thought spy makes two melee attacks, or it makes three ranged attacks\
      \ with its daggers."
    "name": "Multiattack"
  - "desc": "Melee  or Ranged Weapon Attack: dice:1d20+4|noform|noparens|text(+4)\
      \ to hit, reach 5 ft. or range 20/60 ft., one target. Hit: dice:1d4+2|noform|noparens|avg|text(4)\
      \ (1d4 + 2) piercing damage."
    "name": "Dagger"
  - "desc": "Melee Weapon Attack: dice:1d20+4|noform|noparens|text(+4) to hit,\
      \ reach 5 ft., one target. Hit: dice:1d8+2|noform|noparens|avg|text(6) (1d8\
      \ + 2) piercing damage."
    "name": "Rapier"
"source":
  - "GGR"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/thought-spy-ggr.webp"
```
^statblock