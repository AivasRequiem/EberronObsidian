---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- Reckoner
---
# [Reckoner](Інструменти ДМ\CLI\bestiary\humanoid/reckoner-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 231*  

Boros reckoners combine physical power and magical prowess, serving as the shock troops of the legion. They are adept at breaking up mobs and organized lines of defense. Sometimes described as living thunderstorms, reckoners charge their bodies with lightning that bursts forth in their spells and lashes out at enemies who harm them. Many reckoners are minotaurs.

```statblock
"name": "Reckoner (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Neutral"
"ac": !!int "18"
"ac_class": "[plate armor](Інструменти%20ДМ/CLI/items/plate-armor-xphb.md)"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "1"
"stats":
  - !!int "16"
  - !!int "12"
  - !!int "15"
  - !!int "15"
  - !!int "12"
  - !!int "10"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](Інструменти%20ДМ/CLI/rules/skills.md#Arcana)"
    "desc": "+4"
  - "name": "[Intimidation](Інструменти%20ДМ/CLI/rules/skills.md#Intimidation)"
    "desc": "+2"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+3"
"senses": "passive Perception 13"
"languages": "Common plus any one language"
"cr": "4"
"traits":
  - "desc": "The reckoner is a 5th-level Boros spellcaster. Its spellcasting ability\
      \ is Intelligence (spell save DC 12, +4 to hit with spell attacks). The reckoner\
      \ has the following wizard spells prepared:\n\n**Cantrips (at will):** [blade\
      \ ward](Інструменти%20ДМ/CLI/spells/blade-ward-xphb.md), [light](Інструменти\
      %20ДМ/CLI/spells/light-xphb.md), [message](Інструменти%20ДМ/CLI/spells/message-xphb.md),\
      \ [shocking grasp](Інструменти%20ДМ/CLI/spells/shocking-grasp-xphb.md)\n\n**1st\
      \ level (4 slots):** [guiding bolt](Інструменти%20ДМ/CLI/spells/guiding-bolt-xphb.md),\
      \ [shield](Інструменти%20ДМ/CLI/spells/shield-xphb.md), [thunderwave](Інстру\
      менти%20ДМ/CLI/spells/thunderwave-xphb.md), [witch bolt](Інструменти%20ДМ/CLI/spells/witch-bolt-xphb.md)\n\
      \n**2nd level (3 slots):** [blur](Інструменти%20ДМ/CLI/spells/blur-xphb.md),\
      \ [levitate](Інструменти%20ДМ/CLI/spells/levitate-xphb.md)\n\n**3rd level (2\
      \ slots):** [lightning bolt](Інструменти%20ДМ/CLI/spells/lightning-bolt-xphb.md)"
    "name": "Spellcasting"
  - "desc": "The reckoner has advantage on initiative rolls."
    "name": "First Strike"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d8 + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with\
      \ two hands."
    "name": "Longsword"
"reactions":
  - "desc": "When a creature hits the reckoner with an attack, the attacker takes\
      \ lightning damage equal to half the damage dealt by the attack."
    "name": "Lightning Backlash (Recharge 5-6)"
"source":
  - "GGR"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/reckoner-ggr.webp"
```
^statblock