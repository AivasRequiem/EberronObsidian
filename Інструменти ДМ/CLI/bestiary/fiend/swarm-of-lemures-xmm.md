---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/environment/nine-hells
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
statblock-link: "#^statblock"
aliases:
- Swarm of Lemures
---
# [Swarm of Lemures](Інструменти ДМ\CLI\bestiary\fiend/swarm-of-lemures-xmm.md)
*Source: Monster Manual (2024) p. 194*  

When devils drive hosts of lemures into close proximity or when lemures compress into a single mass, a swarm forms and adopts a unified mind.

## Lemures

*Devils of Agony and Despair*

- **Habitat.** Planar (Nine Hells)  
- **Treasure.** None  

The least of all devils, lemures arise from wicked souls, their mortal memories scoured away. Only vague limbs and anguished features jut from these slurries of infernal proto-matter.

```statblock
"name": "Swarm of Lemures (XMM)"
"size": "Large"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "12"
"hp": !!int "45"
"hit_dice": "6d10 + 12"
"modifier": !!int "-2"
"stats":
  - !!int "14"
  - !!int "7"
  - !!int "14"
  - !!int "1"
  - !!int "12"
  - !!int "3"
"speed": "40 ft."
"damage_resistances": "bludgeoning, cold, piercing, slashing"
"damage_immunities": "fire, poison"
"condition_immunities": "[charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed),\
  \ [frightened](Інструменти%20ДМ/CLI/rules/conditions.md#Frightened), [grappled](І\
  нструменти%20ДМ/CLI/rules/conditions.md#Grappled), [paralyzed](Інструменти%20ДМ\
  /CLI/rules/conditions.md#Paralyzed), [petrified](Інструменти%20ДМ/CLI/rules/conditions.md#Petrified),\
  \ [poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned), [prone](Інструм\
  енти%20ДМ/CLI/rules/conditions.md#Prone), [restrained](Інструменти%20ДМ/CLI/rules/conditions.md#Restrained),\
  \ [stunned](Інструменти%20ДМ/CLI/rules/conditions.md#Stunned)"
"senses": "darkvision 120 ft. (unimpeded by magical [Darkness](Інструменти%20ДМ/CLI/rules/variant-rules/darkness-xphb.md)),\
  \ passive Perception 11"
"languages": "understands Infernal but can't speak"
"cr": "3"
"traits":
  - "desc": "If the swarm dies in the Nine Hells, it revives with all its [Hit Points](І\
      нструменти%20ДМ/CLI/rules/variant-rules/hit-points-xphb.md) in d10 days unless\
      \ it is killed by a creature under the effects of a [Bless](Інструменти%20ДМ\
      /CLI/spells/bless-xphb.md) spell or its remains are sprinkled with Holy Water."
    "name": "Hellish Restoration"
  - "desc": "The swarm can occupy another creature's space and vice versa, and the\
      \ swarm can move through an opening large enough for a Medium creature. The\
      \ swarm can't regain [Hit Points](Інструменти%20ДМ/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ or gain [Temporary Hit Points](Інструменти%20ДМ/CLI/rules/variant-rules/temporary-hit-points-xphb.md)."
    "name": "Swarm"
"actions":
  - "desc": "The swarm makes two Vile Slime attacks."
    "name": "Multiattack"
  - "desc": "Melee Attack Roll: +4, reach 5 ft. Hit: 11 (2d8 + 2) Poison damage,\
      \ or 9 (2d6 + 2) Poison damage if the swarm is [Bloodied](Інструменти%20ДМ\
      /CLI/rules/variant-rules/bloodied-xphb.md)."
    "name": "Vile Slime"
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/fiend/token/swarm-of-lemures-xmm.webp"
```
^statblock

## Environment

planar, nine hells