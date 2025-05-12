---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/14
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Devkarin Lich
---
# [Devkarin Lich](Інструменти ДМ\CLI\bestiary\undead/devkarin-lich-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 198*  

Powerful spellcasters of the Devkarin elves, steeped in Golgari magic, can transcend death to become liches. For them, life and death don't merely chase each other in an inevitable cycle; the two can intersect, and at that nexus the liches find immense power, which commands the awe, envy, and fear of other Golgari.

Unlike the shambling zombies they command, liches retain their memories, their personalities, and especially their ambition. They also retain the grace and stature of living elves, but their bodies are in a constant state of slow decay. Various forms of fungus grow in and over the rotting flesh to hold the body together.

## Undead Nature

The lich doesn't require air, food, drink, or sleep.

```statblock
"name": "Devkarin Lich (GGR)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "97"
"hit_dice": "15d8 + 30"
"modifier": !!int "3"
"stats":
  - !!int "11"
  - !!int "16"
  - !!int "14"
  - !!int "19"
  - !!int "16"
  - !!int "15"
"speed": "30 ft."
"saves":
  - "constitution": "+7"
  - "intelligence": "+9"
  - "wisdom": "+8"
"skillsaves":
  - "name": "[Arcana](Інструменти%20ДМ/CLI/rules/skills.md#Arcana)"
    "desc": "+14"
  - "name": "[Insight](Інструменти%20ДМ/CLI/rules/skills.md#Insight)"
    "desc": "+8"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+8"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed),\
  \ [exhaustion](Інструменти%20ДМ/CLI/rules/conditions.md#Exhaustion), [frightened](І\
  нструменти%20ДМ/CLI/rules/conditions.md#Frightened), [paralyzed](Інструменти%20Д\
  М/CLI/rules/conditions.md#Paralyzed), [poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned)"
"senses": "truesight 120 ft., passive Perception 18"
"languages": "Common, Elvish, Kraul"
"cr": "14"
"traits":
  - "desc": "The lich is a 14th-level Golgari spellcaster. Its spellcasting ability\
      \ is Intelligence (spell save DC 17, +9 to hit with spell attacks). The lich\
      \ has the following wizard spells prepared:\n\nCantrips (at will): [acid\
      \ splash](Інструменти%20ДМ/CLI/spells/acid-splash-xphb.md), [chill touch](Ін\
      струменти%20ДМ/CLI/spells/chill-touch-xphb.md), [mage hand](Інструменти%20ДМ\
      /CLI/spells/mage-hand-xphb.md), [poison spray](Інструменти%20ДМ/CLI/spells/poison-spray-xphb.md),\
      \ [prestidigitation](Інструменти%20ДМ/CLI/spells/prestidigitation-xphb.md)\n\
      \n1st level (4 slots): [chromatic orb](Інструменти%20ДМ/CLI/spells/chromatic-orb-xphb.md),\
      \ [magic missile](Інструменти%20ДМ/CLI/spells/magic-missile-xphb.md), [ray of\
      \ sickness](Інструменти%20ДМ/CLI/spells/ray-of-sickness-xphb.md)\n\n2nd level\
      \ (3 slots): [Melf's acid arrow](Інструменти%20ДМ/CLI/spells/melfs-acid-arrow-xphb.md),\
      \ [ray of enfeeblement](Інструменти%20ДМ/CLI/spells/ray-of-enfeeblement-xphb.md),\
      \ [spider climb](Інструменти%20ДМ/CLI/spells/spider-climb-xphb.md), [web](Ін\
      струменти%20ДМ/CLI/spells/web-xphb.md)\n\n3rd level (3 slots): [animate\
      \ dead](Інструменти%20ДМ/CLI/spells/animate-dead-xphb.md), [bestow curse](Ін\
      струменти%20ДМ/CLI/spells/bestow-curse-xphb.md), [fear](Інструменти%20ДМ/CLI/spells/fear-xphb.md),\
      \ [vampiric touch](Інструменти%20ДМ/CLI/spells/vampiric-touch-xphb.md)\n\n4th\
      \ level (3 slots): [blight](Інструменти%20ДМ/CLI/spells/blight-xphb.md), [Evard's\
      \ black tentacles](Інструменти%20ДМ/CLI/spells/evards-black-tentacles-xphb.md)\n\
      \n5th level (2 slots): [cloudkill](Інструменти%20ДМ/CLI/spells/cloudkill-xphb.md),\
      \ [insect plague](Інструменти%20ДМ/CLI/spells/insect-plague-xphb.md)\n\n6th\
      \ level (1 slots): [circle of death](Інструменти%20ДМ/CLI/spells/circle-of-death-xphb.md),\
      \ [create undead](Інструменти%20ДМ/CLI/spells/create-undead-xphb.md)\n\n7th\
      \ level (1 slots): [finger of death](Інструменти%20ДМ/CLI/spells/finger-of-death-xphb.md)"
    "name": "Spellcasting"
  - "desc": "If the lich fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "The lich regains 10 hit points at the start of its turn. If the lich\
      \ takes fire or radiant damage, this trait doesn't function at the start of\
      \ the lich's next turn. The lich dies only if it starts its turn with 0 hit\
      \ points and doesn't regenerate."
    "name": "Regeneration"
  - "desc": "The lich has advantage on saving throws against any effect that turns\
      \ undead."
    "name": "Turn Resistance"
  - "desc": "If damage reduces the lich to 0 hit points, it must make a Constitution\
      \ saving throw with a DC of 5 + the damage taken, unless the damage is radiant\
      \ or from a critical hit. On a success, the lich drops to 1 hit point instead."
    "name": "Undead Fortitude"
"actions":
  - "desc": "Melee Spell Attack: +9 to hit, reach 5 ft., one creature. Hit:\
      \ 14 (4d6) poison damage, and the target must succeed on a DC 17 Constitution\
      \ saving throw or be [poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned)\
      \ for 1 minute. The [poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned)\
      \ target can repeat the saving throw at the end of each of its turns, ending\
      \ the effect on itself on a success."
    "name": "Noxious Touch"
"legendary_actions":
  - "desc": "The lich casts one of its cantrips."
    "name": "Cantrip"
  - "desc": "The lich uses Noxious Touch."
    "name": "Noxious Touch (Costs 2 Actions)"
  - "desc": "Each creature within 30 feet of the lich must make a DC 17 Constitution\
      \ saving throw, taking 21 (6d6) necrotic damage on a failed save, or half\
      \ as much damage on a successful one."
    "name": "Disrupt Life (Costs 3 Actions)"
"source":
  - "GGR"
"image": "Інструменти%20ДМ/CLI/bestiary/undead/token/devkarin-lich-ggr.webp"
```
^statblock