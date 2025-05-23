---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
statblock-link: "#^statblock"
aliases:
- Narzugon
---
# [Narzugon](Інструменти ДМ\CLI\bestiary\fiend/narzugon-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 190*  

Paladins who make deals with devils and carry their twisted sense of honor into the afterlife are especially valuable to the archdukes of the Nine Hells. These narzugons act as horrific perversions of knights errant, carrying out their masters' will.

Narzugons wield hell-forged lances that shunt the souls of any they killed to the River Styx for rebirth as [lemures](Інструменти%20ДМ/CLI/bestiary/fiend/lemure-xmm.md). Every lance bears the marks of both a narzugon and its master.

Each narzugon claims a [nightmare](Інструменти%20ДМ/CLI/bestiary/fiend/nightmare-xmm.md) as its mount. These steeds are bound by [infernal tack](Інструменти%20ДМ/CLI/items/infernal-tack-mtf.md) and must respond to the summons and commands of the spurs' wearer.

```statblock
"name": "Narzugon (MPMM)"
"size": "Medium"
"type": "fiend"
"subtype": "devil"
"alignment": "Typically  Lawful Evil"
"ac": !!int "20"
"ac_class": "[plate armor](Інструменти%20ДМ/CLI/items/plate-armor-xphb.md), [shield](І\
  нструменти%20ДМ/CLI/items/shield-xphb.md)"
"hp": !!int "112"
"hit_dice": "15d8 + 45"
"modifier": !!int "0"
"stats":
  - !!int "20"
  - !!int "10"
  - !!int "17"
  - !!int "16"
  - !!int "14"
  - !!int "19"
"speed": "30 ft."
"saves":
  - "dexterity": "+5"
  - "constitution": "+8"
  - "charisma": "+9"
"skillsaves":
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+12"
"damage_resistances": "acid; cold; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "[charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed),\
  \ [frightened](Інструменти%20ДМ/CLI/rules/conditions.md#Frightened), [poisoned](І\
  нструменти%20ДМ/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 22"
"languages": "Common, Infernal, telepathy 120 ft."
"cr": "13"
"traits":
  - "desc": "The narzugon wears spurs that are part of [infernal tack](Інструменти\
      %20ДМ/CLI/items/infernal-tack-mtf.md), which allow it to summon its [nightmare](І\
      нструменти%20ДМ/CLI/bestiary/fiend/nightmare-xmm.md) companion as an action."
    "name": "Infernal Tack"
  - "desc": "The narzugon has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The narzugon makes three Hellfire Lance attacks. It also uses Infernal\
      \ Command or Terrifying Command."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit:\
      \ 11 (1d12 + 5) piercing damage plus 16 (3d10) fire damage. If this damage\
      \ kills a creature with a soul, the soul rises from the River Styx as a [lemure](І\
      нструменти%20ДМ/CLI/bestiary/fiend/lemure-xmm.md) in Avernus in d4 hours.\
      \ If the creature isn't revived before then, only a [wish](Інструменти%20ДМ\
      /CLI/spells/wish-xphb.md) spell or killing the lemure and casting true resurrection\
      \ on the creature's original body can restore it to life. Constructs and devils\
      \ are immune to this effect."
    "name": "Hellfire Lance"
  - "desc": "Each ally of the narzugon within 60 feet of it can't be [charmed](Інс\
      трументи%20ДМ/CLI/rules/conditions.md#Charmed) or [frightened](Інструменти%20Д\
      М/CLI/rules/conditions.md#Frightened) until the end of the narzugon's next turn."
    "name": "Infernal Command"
  - "desc": "Each creature within 60 feet of the narzugon that isn't a Fiend must\
      \ succeed on a DC 17 Charisma saving throw or become [frightened](Інструмент\
      и%20ДМ/CLI/rules/conditions.md#Frightened) of the narzugon for 1 minute. A creature\
      \ can repeat the saving throw at the end of each of its turns, ending the effect\
      \ on itself on a success. A creature that makes a successful saving throw is\
      \ immune to this narzugon's Terrifying Command for 24 hours."
    "name": "Terrifying Command"
  - "desc": "The narzugon, or one creature it touches, regains 100 hit points."
    "name": "Healing (1/Day)"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/fiend/token/narzugon-mpmm.webp"
```
^statblock