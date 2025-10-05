---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- Firefist
---
# [Firefist](Інструменти ДМ\CLI\bestiary\humanoid/firefist-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 231*  

Boros firefists combine potent magic with peerless fighting ability, inspiring all who serve alongside them. They often act as the point of contact between the Boros Legion and the angelic leaders.

```statblock
"name": "Firefist (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Good"
"ac": !!int "18"
"ac_class": "[plate armor](Інструменти%20ДМ/CLI/items/plate-armor-xphb.md)"
"hp": !!int "117"
"hit_dice": "18d8 + 36"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "14"
  - !!int "11"
  - !!int "17"
  - !!int "13"
"speed": "30 ft."
"saves":
  - "constitution": !!int "5"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Intimidation](Інструменти%20ДМ/CLI/rules/skills.md#Intimidation)"
    "desc": "+4"
  - "name": "[Religion](Інструменти%20ДМ/CLI/rules/skills.md#Religion)"
    "desc": "+3"
"senses": "passive Perception 13"
"languages": "any one language (usually Common)"
"cr": "7"
"traits":
  - "desc": "The firefist is a 9th-level Boros spellcaster. Its spellcasting ability\
      \ is Wisdom (spell save DC 14, dice:1d20+6|noform|noparens|text(+6) to hit\
      \ with spell attacks). It has the following cleric spells prepared:\n\nCantrips\
      \ (at will): [fire bolt](Інструменти%20ДМ/CLI/spells/fire-bolt-xphb.md), [light](І\
      нструменти%20ДМ/CLI/spells/light-xphb.md), [sacred flame](Інструменти%20ДМ/CLI/spells/sacred-flame-xphb.md),\
      \ [spare the dying](Інструменти%20ДМ/CLI/spells/spare-the-dying-xphb.md)\n\n\
      1st level (4 slots): [guiding bolt](Інструменти%20ДМ/CLI/spells/guiding-bolt-xphb.md),\
      \ [healing word](Інструменти%20ДМ/CLI/spells/healing-word-xphb.md), [heroism](І\
      нструменти%20ДМ/CLI/spells/heroism-xphb.md), [shield of faith](Інструменти%20Д\
      М/CLI/spells/shield-of-faith-xphb.md)\n\n2nd level (3 slots): [lesser restoration](І\
      нструменти%20ДМ/CLI/spells/lesser-restoration-xphb.md), [scorching ray](Інст\
      рументи%20ДМ/CLI/spells/scorching-ray-xphb.md)\n\n3rd level (3 slots): [blinding\
      \ smite](Інструменти%20ДМ/CLI/spells/blinding-smite-xphb.md), [crusader's mantle](І\
      нструменти%20ДМ/CLI/spells/crusaders-mantle-xphb.md), [revivify](Інструменти\
      %20ДМ/CLI/spells/revivify-xphb.md)\n\n4th level (3 slots): [banishment](І\
      нструменти%20ДМ/CLI/spells/banishment-xphb.md), [wall of fire](Інструменти%20Д\
      М/CLI/spells/wall-of-fire-xphb.md)\n\n5th level (1 slots): [flame strike](І\
      нструменти%20ДМ/CLI/spells/flame-strike-xphb.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "The firefist makes two greatsword attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: dice:1d20+6|noform|noparens|text(+6) to hit,\
      \ reach 5 ft., one target. Hit: dice:2d6+3|noform|noparens|avg|text(10)\
      \ (2d6 + 3) slashing damage."
    "name": "Greatsword"
"reactions":
  - "desc": "When the firefist or one creature it can see within 30 feet of it makes\
      \ an attack roll, the firefist grants a +10 bonus to that roll."
    "name": "Guided Attack (Recharges after a Short or Long Rest)"
"source":
  - "GGR"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/firefist-ggr.webp"
```
^statblock