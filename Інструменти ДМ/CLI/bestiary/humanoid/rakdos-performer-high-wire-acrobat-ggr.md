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
- Rakdos Performer, High-Wire Acrobat
---
# [Rakdos Performer, High-Wire Acrobat](Інструменти ДМ\CLI\bestiary\humanoid/rakdos-performer-high-wire-acrobat-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 249*  

By offering a place for those of many different talents, the Cult of Rakdos has seen its numbers swell with performing artists, including blade jugglers, fire eaters, and high wire acrobats. Performers carry the message of Rakdos out into the streets: cut loose, free yourself from the bonds of society's mores and expectations, and indulge your desires.

```statblock
"name": "Rakdos Performer, High-Wire Acrobat (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"modifier": !!int "3"
"stats":
  - !!int "13"
  - !!int "17"
  - !!int "12"
  - !!int "10"
  - !!int "8"
  - !!int "15"
"speed": "40 ft., climb 30 ft."
"saves":
  - "dexterity": "+5"
  - "charisma": "+4"
"skillsaves":
  - "name": "[Acrobatics](Інструменти%20ДМ/CLI/rules/skills.md#Acrobatics)"
    "desc": "+7"
  - "name": "[Performance](Інструменти%20ДМ/CLI/rules/skills.md#Performance)"
    "desc": "+4"
"senses": "passive Perception 9"
"languages": "any one language (usually Common)"
"cr": "1"
"traits":
  - "desc": "The performer can take the Disengage action as a bonus action on each\
      \ of its turns."
    "name": "Nimble"
"actions":
  - "desc": "The acrobat makes two attacks with its barbed pole."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7\
      \ (1d8 + 3) piercing damage, and the acrobat can jump up to 20 feet. This\
      \ movement doesn't provoke opportunity attacks."
    "name": "Barbed Pole"
"source":
  - "GGR"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/rakdos-performer-high-wire-acrobat-ggr.webp"
```
^statblock