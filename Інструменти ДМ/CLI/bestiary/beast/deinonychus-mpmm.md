---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/beast/dinosaur
statblock: inline
statblock-link: "#^statblock"
aliases:
- Deinonychus
---
# [Deinonychus](Інструменти ДМ\CLI\bestiary\beast/deinonychus-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 95*  

This larger cousin of the velociraptor kills by gripping its target with its claws and feeding.

```statblock
"name": "Deinonychus (MPMM)"
"size": "Medium"
"type": "beast"
"subtype": "dinosaur"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "26"
"hit_dice": "4d8 + 8"
"modifier": !!int "2"
"stats":
  - !!int "15"
  - !!int "15"
  - !!int "14"
  - !!int "4"
  - !!int "12"
  - !!int "6"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+3"
"senses": "passive Perception 13"
"languages": ""
"cr": "1"
"traits":
  - "desc": "If the deinonychus moves at least 20 feet straight toward a creature\
      \ and then hits it with a Claw attack on the same turn, that target must succeed\
      \ on a DC 12 Strength saving throw or be knocked [prone](Інструменти%20ДМ/CLI/rules/conditions.md#Prone).\
      \ If the target is [prone](Інструменти%20ДМ/CLI/rules/conditions.md#Prone),\
      \ the deinonychus can make one Bite attack against it as a bonus action."
    "name": "Pounce"
"actions":
  - "desc": "The deinonychus makes one Bite attack and two Claw attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6\
      \ (1d8 + 2) piercing damage."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6\
      \ (1d8 + 2) slashing damage."
    "name": "Claw"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/beast/token/deinonychus-mpmm.webp"
```
^statblock

## Environment

forest, grassland, hill