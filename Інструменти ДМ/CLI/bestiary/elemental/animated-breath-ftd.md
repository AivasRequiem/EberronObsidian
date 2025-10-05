---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ftd
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- Animated Breath
---
# [Animated Breath](Інструменти ДМ\CLI\bestiary\elemental/animated-breath-ftd.md)
*Source: Fizban's Treasury of Dragons p. 163*  

A chromatic dragon's breath weapon is a manifestation of the energy that suffuses the dragon. With sufficient practice, dragons can learn to draw on magic from the Elemental Planes to shape their breath weapons into bipedal form, creating Elemental creatures called animated breaths. Chromatic dragons often use these creatures as guardians for their hoards or send them out to gather treasure from the territory around their lairs.

An animated breath is a bipedal creature formed from the same energy as the breath weapon of the dragon that created it. A red dragon's creation strongly resembles a fire elemental, while a black dragon's is similar to a water elemental, but viscous and foul-looking. A green dragon's animated poison breath looks like billowing clouds of green gas, while a white dragon's animated cold breath looks like a walking ice sculpture with frigid air whirling around it. A blue dragon's animated lightning breath is a constantly shifting form of crackling lightning, and it can suddenly vanish from one place to reappear in another, striking like a bolt from the blue.

```statblock
"name": "Animated Breath (FTD)"
"size": "Large"
"type": "elemental"
"alignment": "typically  Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor; 17 cold form only"
"hp": !!int "95"
"hit_dice": "10d10 + 40"
"modifier": !!int "0"
"stats":
  - !!int "19"
  - !!int "11"
  - !!int "18"
  - !!int "6"
  - !!int "10"
  - !!int "5"
"speed": "30 ft., fly 30 ft. (hover)"
"damage_resistances": "damage of the type matching the animated breath's form (acid,\
  \ cold, fire, lightning, or poison)"
"condition_immunities": "[exhaustion](Інструменти%20ДМ/CLI/rules/conditions.md#Exhaustion),\
  \ [paralyzed](Інструменти%20ДМ/CLI/rules/conditions.md#Paralyzed), [petrified](І\
  нструменти%20ДМ/CLI/rules/conditions.md#Petrified), [poisoned](Інструменти%20ДМ\
  /CLI/rules/conditions.md#Poisoned), [restrained](Інструменти%20ДМ/CLI/rules/conditions.md#Restrained),\
  \ [unconscious](Інструменти%20ДМ/CLI/rules/conditions.md#Unconscious)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "understands Draconic but can't speak"
"cr": "6"
"traits":
  - "desc": "When created, the animated breath takes one of five forms, matching its\
      \ creator's breath weapon: Acid, Cold, Fire, Lightning, or Poison. This form\
      \ determines the creature's AC, damage resistance, traits, and attacks."
    "name": "Chromatic Form"
  - "desc": "At the start of each of the animated breath's turns, each creature within\
      \ 5 feet of it takes dice:1d6|noform|noparens|avg|text(3) (d6) fire damage,\
      \ and flammable objects in the aura that aren't being worn or carried ignite.\
      \ A creature that touches the animated breath or hits it with a melee attack\
      \ takes dice:1d6|noform|noparens|avg|text(3) (d6) fire damage."
    "name": "Fire Aura (Fire Form Only)"
  - "desc": "A creature that starts its turn within 5 feet of the animated breath\
      \ must succeed on a DC 15 Constitution saving throw or be [poisoned](Інструм\
      енти%20ДМ/CLI/rules/conditions.md#Poisoned) until the start of its next turn.\
      \ A creature that touches the animated breath or hits it with a melee attack\
      \ takes dice:1d6|noform|noparens|avg|text(3) (d6) acid damage."
    "name": "Putrid Aura (Acid and Poison Forms Only)"
"actions":
  - "desc": "The animated breath makes two Slam attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: dice:1d20+7|noform|noparens|text(+7) to hit,\
      \ reach 5 ft., one target. Hit: dice:2d8+4|noform|noparens|avg|text(13)\
      \ (2d8 + 4) bludgeoning damage plus dice:2d10|noform|noparens|avg|text(11)\
      \ (2d10) damage of a type determined by the animated breath's form: acid,\
      \ cold, fire, lightning, or poison."
    "name": "Slam"
"bonus_actions":
  - "desc": "The animated breath magically teleports to an unoccupied space it can\
      \ see within 30 feet of it. Each creature within 5 feet of the animated breath\
      \ after it teleports takes dice:1d6|noform|noparens|avg|text(3) (d6) lightning\
      \ damage."
    "name": "Lightning Burst (Lightning Form Only)"
"source":
  - "FTD"
"image": "Інструменти%20ДМ/CLI/bestiary/elemental/token/animated-breath-ftd.webp"
```
^statblock