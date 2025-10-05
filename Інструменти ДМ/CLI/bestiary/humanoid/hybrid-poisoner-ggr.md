---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/simic-hybrid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Hybrid Poisoner
---
# [Hybrid Poisoner](Інструменти ДМ\CLI\bestiary\humanoid/hybrid-poisoner-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 217*  

## Simic Hybrids

The Guardian Project is a consequence of increasing tension within the Simic Combine as the threat of interguild conflict looms. Believing that the Simic must be prepared to fight for their lives when that conflict comes to a head, biomancers have created soldiers to help defend the guild. These hybrids (also called guardians, after the name of the project) are created from human, vedalken, and elf guild members who volunteer to be transformed.

```statblock
"name": "Hybrid Poisoner (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "Simic hybrid"
"alignment": "Neutral Good"
"ac": !!int "14"
"hp": !!int "26"
"hit_dice": "4d8 + 8"
"modifier": !!int "4"
"stats":
  - !!int "12"
  - !!int "19"
  - !!int "14"
  - !!int "12"
  - !!int "13"
  - !!int "12"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "6"
  - "constitution": !!int "4"
"skillsaves":
  - "name": "[Athletics](Інструменти%20ДМ/CLI/rules/skills.md#Athletics)"
    "desc": "+3"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](Інструменти%20ДМ/CLI/rules/skills.md#Stealth)"
    "desc": "+6"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 30 ft., passive Perception 13"
"languages": "Common plus any one language"
"cr": "1"
"traits":
  - "desc": "During its first turn, the hybrid poisoner has advantage on attack rolls\
      \ against any creature that hasn't taken a turn. Any hit the hybrid scores against\
      \ a [surprised](Інструменти%20ДМ/CLI/rules/conditions.md#Surprised) creature\
      \ is a critical hit."
    "name": "Assassinate"
  - "desc": "Any creature that touches the hybrid or hits it with a melee attack while\
      \ within 5 feet of it takes dice:1d6|noform|noparens|avg|text(3) (d6) poison\
      \ damage."
    "name": "Poisonous Skin"
"actions":
  - "desc": "Melee Weapon Attack: dice:1d20+6|noform|noparens|text(+6) to hit,\
      \ reach 5 ft., one target. Hit: dice:2d6|noform|noparens|avg|text(7) (2d6)\
      \ bludgeoning damage, and the target must succeed on a DC 12 Constitution saving\
      \ throw or become [poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned)\
      \ for 1 minute. At the end of each of the [poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned)\
      \ target's turns, it must repeat the save, taking dice:1d6|noform|noparens|avg|text(3)\
      \ (d6) poison damage on a failed save, or ending the effect on itself on a\
      \ successful one."
    "name": "Toxic Touch"
"source":
  - "GGR"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/hybrid-poisoner-ggr.webp"
```
^statblock