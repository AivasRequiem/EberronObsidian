---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant
statblock: inline
statblock-link: "#^statblock"
aliases:
- Bloodfray Giant
---
# [Bloodfray Giant](Інструменти ДМ\CLI\bestiary\giant/bloodfray-giant-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 200*  

Giants in the Cult of Rakdos act as enforcers, bouncers, and sometimes even pillars, holding the mobile platforms that serve as stages for Rakdos performances. Like other members of the cult, giants thrill to the violence of those shows. Though they can seem entranced by the horror unfolding on the stage, they react quickly and brutally to any interruption of the performance.

## Giants

Giants use their tremendous size and strength to advance the cause of no less than four guilds. In the Boros Legion and the Orzhov Syndicate, they are cunning soldiers. The giants of the Cult of Rakdos and the Gruul Clans are no less effective but lack discipline.

```statblock
"name": "Bloodfray Giant (GGR)"
"size": "Huge"
"type": "giant"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "103"
"hit_dice": "9d12 + 45"
"modifier": !!int "-1"
"stats":
  - !!int "23"
  - !!int "9"
  - !!int "20"
  - !!int "7"
  - !!int "8"
  - !!int "9"
"speed": "40 ft."
"saves":
  - "strength": "+9"
  - "constitution": "+8"
  - "wisdom": "+2"
"skillsaves":
  - "name": "[Athletics](Інструменти%20ДМ/CLI/rules/skills.md#Athletics)"
    "desc": "+9"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+2"
"senses": "passive Perception 12"
"languages": "Giant"
"cr": "6"
"actions":
  - "desc": "Melee Weapon Attack: +9 to hit, reach 20 ft., one target. Hit:\
      \ 16 (3d6 + 6) bludgeoning damage. If the target is a creature, it is [grappled](І\
      нструменти%20ДМ/CLI/rules/conditions.md#Grappled) (escape DC 17). Until the\
      \ grapple ends, the target is [restrained](Інструменти%20ДМ/CLI/rules/conditions.md#Restrained),\
      \ and the giant can't use this attack on anyone else."
    "name": "Chain"
  - "desc": "Ranged Weapon Attack: +9 to hit, range 60/240 ft., one target. Hit:\
      \ 16 (3d6 + 6) bludgeoning damage."
    "name": "Rock"
"reactions":
  - "desc": "After a creature the giant can see is dealt damage by a foe within 20\
      \ feet of the giant, the giant makes a chain attack against that foe."
    "name": "Furious Defense"
"source":
  - "GGR"
"image": "Інструменти%20ДМ/CLI/bestiary/giant/token/bloodfray-giant-ggr.webp"
```
^statblock