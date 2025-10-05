---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- Counterflux Blastseeker
---
# [Counterflux Blastseeker](Інструменти ДМ\CLI\bestiary\humanoid/counterflux-blastseeker-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 242*  

While chemisters focus on inventing new tools, weapons, and other devices for the guild to use, the role of a blastseeker is to put those devices to work. Despite the name, not all such devices produce explosions, but all the most interesting ones (from the Izzet perspective) do.

```statblock
"name": "Counterflux Blastseeker (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Neutral"
"ac": !!int "13"
"ac_class": "16 with [mage armor](Інструменти%20ДМ/CLI/spells/mage-armor-xphb.md)"
"hp": !!int "39"
"hit_dice": "6d8 + 12"
"modifier": !!int "3"
"stats":
  - !!int "13"
  - !!int "16"
  - !!int "15"
  - !!int "18"
  - !!int "11"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "constitution": !!int "4"
  - "wisdom": !!int "2"
"skillsaves":
  - "name": "[Arcana](Інструменти%20ДМ/CLI/rules/skills.md#Arcana)"
    "desc": "+6"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+2"
"senses": "passive Perception 12"
"languages": "Common plus any one language"
"cr": "2"
"traits":
  - "desc": "The blastseeker's innate spellcasting ability is Intelligence (spell\
      \ save DC 14, +6 to hit with spell attacks). The blastseeker can innately\
      \ cast the following spells, requiring no components other than its Izzet gear,\
      \ which doesn't function for others:\n\n3/day each: [enlarge/reduce](Інс\
      трументи%20ДМ/CLI/spells/enlarge-reduce-xphb.md), [mage armor](Інструменти%20Д\
      М/CLI/spells/mage-armor-xphb.md) (self only), [scorching ray](Інструменти%20Д\
      М/CLI/spells/scorching-ray-xphb.md)\n\n1/day each: [counterspell](Інстру\
      менти%20ДМ/CLI/spells/counterspell-xphb.md), [dispel magic](Інструменти%20ДМ\
      /CLI/spells/dispel-magic-xphb.md), [protection from energy](Інструменти%20ДМ\
      /CLI/spells/protection-from-energy-xphb.md)"
    "name": "Innate Spellcasting"
  - "desc": "The blastseeker can create an additional effect immediately after casting\
      \ a spell. Roll a d6 to determine the effect:\n\n- 1–3.. The blastseeker\
      \ creates a 15-foot-radius [invisible](Інструменти%20ДМ/CLI/rules/conditions.md#Invisible)\
      \ sphere centered on itself that lasts until the end of its next turn. Creatures\
      \ in the sphere have disadvantage on saving throws against spells and other\
      \ magical effects.  \n- 4–6.. The blastseeker creates a 15-foot-radius [invisible](І\
      нструменти%20ДМ/CLI/rules/conditions.md#Invisible) sphere centered on itself\
      \ that lasts until the end of its next turn. Creatures in the sphere have advantage\
      \ on saving throws against spells and other magical effects.  "
    "name": "Counterflux Overcast (Recharge 5-6)"
"actions":
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7\
      \ (1d8 + 3) piercing damage."
    "name": "Rapier"
"source":
  - "GGR"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/counterflux-blastseeker-ggr.webp"
```
^statblock