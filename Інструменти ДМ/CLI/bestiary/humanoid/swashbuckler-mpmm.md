---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Swashbuckler
---
# [Swashbuckler](Інструменти ДМ\CLI\bestiary\humanoid/swashbuckler-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 238*  

Swashbucklers are charming ne'er-do-wells who live by their own codes of honor. They crave notoriety, often indulge in romantic trysts, and eke out livings as pirates and corsairs, rarely staying in one place for too long.

Many swashbucklers have a signature flourish with which they embellish their actions to make themselves more memorable. You can roll on the Swashbuckler Flourishes table or choose one of the options to find a suitably dramatic flourish for a swashbuckler.

**Swashbuckler Flourishes**

`dice: [](swashbuckler-mpmm.md#^swashbuckler-flourishes)`

| dice: d8 | Flourish |
|----------|----------|
| 1 | Winks and flashes a charming grin |
| 2 | Bows theatrically |
| 3 | Constantly flips their dagger |
| 4 | Punctuates sentences with a boisterous "Ha-HA!" |
| 5 | Sings catchy sea chanteys |
| 6 | Dexterously manipulates a silver coin through their fingers |
| 7 | Hurls colorful insults |
| 8 | Adds showy embellishments to rapier strokes |
^swashbuckler-flourishes

```statblock
"name": "Swashbuckler (MPMM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "17"
"ac_class": "[leather armor](Інструменти%20ДМ/CLI/items/leather-armor-xphb.md), suave\
  \ defense"
"hp": !!int "66"
"hit_dice": "12d8 + 12"
"modifier": !!int "4"
"stats":
  - !!int "12"
  - !!int "18"
  - !!int "12"
  - !!int "14"
  - !!int "11"
  - !!int "15"
"speed": "30 ft."
"skillsaves":
  - "name": "[Acrobatics](Інструменти%20ДМ/CLI/rules/skills.md#Acrobatics)"
    "desc": "+8"
  - "name": "[Athletics](Інструменти%20ДМ/CLI/rules/skills.md#Athletics)"
    "desc": "+5"
  - "name": "[Persuasion](Інструменти%20ДМ/CLI/rules/skills.md#Persuasion)"
    "desc": "+6"
"senses": "passive Perception 10"
"languages": "any one language (usually Common)"
"cr": "3"
"traits":
  - "desc": "While the swashbuckler is wearing light or no armor and wielding no [shield](І\
      нструменти%20ДМ/CLI/items/shield-xphb.md), its AC includes its Charisma modifier."
    "name": "Suave Defense"
"actions":
  - "desc": "The swashbuckler makes one Dagger attack and two Rapier attacks."
    "name": "Multiattack"
  - "desc": "Melee  or Ranged Weapon Attack: dice:1d20+6|noform|noparens|text(+6)\
      \ to hit, reach 5 ft. or range 20/60 ft., one target. Hit: dice:1d4+4|noform|noparens|avg|text(6)\
      \ (1d4 + 4) piercing damage."
    "name": "Dagger"
  - "desc": "Melee Weapon Attack: dice:1d20+6|noform|noparens|text(+6) to hit,\
      \ reach 5 ft., one target. Hit: dice:1d8+4|noform|noparens|avg|text(8) (1d8\
      \ + 4) piercing damage."
    "name": "Rapier"
"bonus_actions":
  - "desc": "The swashbuckler takes the [Dash](Інструменти%20ДМ/CLI/rules/actions.md#Dash)\
      \ or [Disengage](Інструменти%20ДМ/CLI/rules/actions.md#Disengage) action."
    "name": "Lightfooted"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/swashbuckler-mpmm.webp"
```
^statblock

## Environment

coastal, urban