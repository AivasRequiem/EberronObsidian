---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/dmg
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Avatar of Death
---
# [Avatar of Death](Інструменти ДМ\CLI\bestiary\undead/avatar-of-death-dmg.md)
*Source: Dungeon Master's Guide p. 164, Tasha's Cauldron of Everything. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

Summoned by the "Skull" card from the [Deck of Many Things](Інструменти%20ДМ/CLI/items/deck-of-many-things-xdmg.md).

```statblock
"name": "Avatar of Death (DMG)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "20"
"modifier": !!int "3"
"stats":
  - !!int "16"
  - !!int "16"
  - !!int "16"
  - !!int "16"
  - !!int "16"
  - !!int "16"
"speed": "60 ft., fly 60 ft. (hover)"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed),\
  \ [frightened](Інструменти%20ДМ/CLI/rules/conditions.md#Frightened), [paralyzed](І\
  нструменти%20ДМ/CLI/rules/conditions.md#Paralyzed), [petrified](Інструменти%20ДМ\
  /CLI/rules/conditions.md#Petrified), [poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned),\
  \ [unconscious](Інструменти%20ДМ/CLI/rules/conditions.md#Unconscious)"
"senses": "darkvision 60 ft., truesight 60 ft., passive Perception 13"
"languages": "all languages known to its summoner"
"traits":
  - "desc": "The avatar can move through other creatures and objects as if they were\
      \ difficult terrain. It takes 5 (d10) force damage if it ends its turn inside\
      \ an object."
    "name": "Incorporeal Movement"
  - "desc": "The avatar is immune to features that turn undead."
    "name": "Turn Immunity"
"actions":
  - "desc": "The avatar sweeps its spectral scythe through a creature within 5 feet\
      \ of it, dealing 7 (1d8 + 3) slashing damage plus 4 (d8) necrotic damage."
    "name": "Reaping Scythe"
"source":
  - "DMG"
  - "TCE"
"image": "Інструменти%20ДМ/CLI/bestiary/undead/token/avatar-of-death-dmg.webp"
```
^statblock