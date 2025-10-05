---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- Fluxcharger
---
# [Fluxcharger](Інструменти ДМ\CLI\bestiary\elemental/fluxcharger-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 208*  

In an effort to create a weird that could be more easily controlled, Izzet mages tried binding elemental lightning, fire, and smoke into a framework made of the magical alloy mizzium. The experiment was partly successful: the resulting weird, a fluxcharger, doesn't explode like some other weirds do, but it is more intelligent and more headstrong than other weirds.

A fluxcharger's mizzium frame is suggestive of an angel. A faceplate is meant to give it some personality, but most people find its solemn expression and unblinking stare more unnerving than relatable.

## Izzet Weirds

Weirds are the products of Izzet League experiments intended to combine two opposing elemental types in the hope of creating elementals that were more stable than the norm and easier to control. As commonly happens with Izzet experiments, the outcome was the exact opposite. Weirds are even wilder and more unpredictable than elementals of either of their component elements. Nevertheless, they can make potent guardian creatures and can be urged into fighting on behalf of their creators.

### Elemental Nature

An Izzet weird doesn't require air, food, drink, or sleep.

```statblock
"name": "Fluxcharger (GGR)"
"size": "Large"
"type": "elemental"
"alignment": "Chaotic Neutral"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "60"
"hit_dice": "8d10 + 16"
"modifier": !!int "4"
"stats":
  - !!int "15"
  - !!int "18"
  - !!int "15"
  - !!int "6"
  - !!int "10"
  - !!int "7"
"speed": "0 ft., fly 60 ft."
"damage_resistances": "thunder; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "lightning, poison"
"condition_immunities": "[exhaustion](Інструменти%20ДМ/CLI/rules/conditions.md#Exhaustion),\
  \ [grappled](Інструменти%20ДМ/CLI/rules/conditions.md#Grappled), [paralyzed](Інс\
  трументи%20ДМ/CLI/rules/conditions.md#Paralyzed), [petrified](Інструменти%20ДМ/CLI/rules/conditions.md#Petrified),\
  \ [poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned), [prone](Інструм\
  енти%20ДМ/CLI/rules/conditions.md#Prone), [restrained](Інструменти%20ДМ/CLI/rules/conditions.md#Restrained),\
  \ [unconscious](Інструменти%20ДМ/CLI/rules/conditions.md#Unconscious)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Draconic"
"cr": "7"
"traits":
  - "desc": "Whenever a spell that deals lightning damage includes one or more fluxchargers\
      \ in its area, the spell deals an extra dice:2d8|noform|noparens|avg|text(9)\
      \ (2d8) lightning damage."
    "name": "Amplify Lightning"
"actions":
  - "desc": "The fluxcharger makes two slam attacks or uses Arc Lightning twice."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: dice:1d20+7|noform|noparens|text(+7) to hit,\
      \ reach 10 ft., one target. Hit: dice:2d8+4|noform|noparens|avg|text(13)\
      \ (2d8 + 4) bludgeoning damage plus dice:3d6|noform|noparens|avg|text(10)\
      \ (3d6) fire damage."
    "name": "Slam"
  - "desc": "Ranged Spell Attack: dice:1d20+7|noform|noparens|text(+7) to hit,\
      \ range 30 ft., one target. Hit: dice:3d10|noform|noparens|avg|text(16)\
      \ (3d10) lightning damage, and lightning jumps from the target to one creature\
      \ of the fluxcharger's choice that it can see within 30 feet of the target.\
      \ That second creature must succeed on a DC 15 Dexterity saving throw or take\
      \ dice:3d8|noform|noparens|avg|text(13) (3d8) lightning damage. Hit or\
      \ Miss: The fluxcharger takes dice:1d10|noform|noparens|avg|text(5) (d10)\
      \ force damage after resolving the attack."
    "name": "Arc Lightning"
"source":
  - "GGR"
"image": "Інструменти%20ДМ/CLI/bestiary/elemental/token/fluxcharger-ggr.webp"
```
^statblock