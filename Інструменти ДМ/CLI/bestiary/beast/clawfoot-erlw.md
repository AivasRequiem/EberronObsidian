---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/erlw
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- Clawfoot
---
# [Clawfoot](Інструменти ДМ\CLI\bestiary\beast/clawfoot-erlw.md)
*Source: Eberron: Rising from the Last War p. 289*  

Clawfoot dinosaurs are two-legged saurians with sharp teeth and toe claws that resemble deadly sickles. They are imposing creatures, about the size of a tall human, and are fierce enough to take down even larger prey.

In the wild, an untrained clawfoot can easily hold its own in combat, but they are even fiercer when hunting in packs. Their instinct for pack structure has made these dinosaurs a traditional war mount for the halflings of the Talenta Plains, with clawfoots quickly and eagerly responding to training and control.

Dinosaurs are widespread on Eberron, particularly in Q'barra, the Talenta Plains, Xen'drik, and Argonnessen. Smaller dinosaurs are the rule in Q'barra and the Talenta Plains, including varieties commonly used by Talenta halflings as mounts.

```statblock
"name": "Clawfoot (ERLW)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "19"
"hit_dice": "3d8 + 6"
"modifier": !!int "3"
"stats":
  - !!int "12"
  - !!int "16"
  - !!int "14"
  - !!int "4"
  - !!int "12"
  - !!int "10"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](Інструменти%20ДМ/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"senses": "passive Perception 13"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The clawfoot has advantage on an attack roll against a creature if at\
      \ least one of the clawfoot's allies is within 5 feet of the creature and the\
      \ ally isn't [incapacitated](Інструменти%20ДМ/CLI/rules/conditions.md#Incapacitated)."
    "name": "Pack Tactics"
  - "desc": "If the clawfoot moves at least 20 feet straight toward a creature and\
      \ then hits it with a claw attack on the same turn, that target must succeed\
      \ on a DC 11 Strength saving throw or be knocked [prone](Інструменти%20ДМ/CLI/rules/conditions.md#Prone).\
      \ If the target is [prone](Інструменти%20ДМ/CLI/rules/conditions.md#Prone),\
      \ the clawfoot can make one bite attack against it as a bonus action."
    "name": "Pounce"
"actions":
  - "desc": "The clawfoot makes two attacks: one with its bite and one with its claws."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: dice:1d20+5|noform|noparens|text(+5) to hit,\
      \ reach 5 ft., one target. Hit: dice:1d8+3|noform|noparens|avg|text(7) (1d8\
      \ + 3) piercing damage."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: dice:1d20+5|noform|noparens|text(+5) to hit,\
      \ reach 5 ft., one target. Hit: dice:1d8+3|noform|noparens|avg|text(7) (1d8\
      \ + 3) slashing damage."
    "name": "Claws"
"source":
  - "ERLW"
"image": "Інструменти%20ДМ/CLI/bestiary/beast/token/clawfoot-erlw.webp"
```
^statblock