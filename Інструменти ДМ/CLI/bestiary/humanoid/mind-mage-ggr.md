---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- Mind Mage
---
# [Mind Mage](Інструменти ДМ\CLI\bestiary\humanoid/mind-mage-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 233*  

Dimir mind mages are among the most feared spellcasters in Ravnica, thanks in large part to the aura of mystery that shrouds them and their work. Their ability to read and alter memories commands respect from the other members of House Dimir and makes them useful in the full spectrum of the guild's activities. Many mind mages lead cells of their own.

```statblock
"name": "Mind Mage (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](Інструменти%20ДМ/CLI/spells/mage-armor-xphb.md)"
"hp": !!int "49"
"hit_dice": "11d8"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "10"
  - !!int "20"
  - !!int "15"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "intelligence": "+8"
  - "wisdom": "+5"
"skillsaves":
  - "name": "[Arcana](Інструменти%20ДМ/CLI/rules/skills.md#Arcana)"
    "desc": "+8"
  - "name": "[Deception](Інструменти%20ДМ/CLI/rules/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Insight](Інструменти%20ДМ/CLI/rules/skills.md#Insight)"
    "desc": "+5"
  - "name": "[Persuasion](Інструменти%20ДМ/CLI/rules/skills.md#Persuasion)"
    "desc": "+6"
"senses": "passive Perception 12"
"languages": "Common plus any four languages"
"cr": "5"
"traits":
  - "desc": "The mage's spellcasting ability is Intelligence (spell save DC 16). It\
      \ can innately cast the following spells, requiring no components:\n\nAt will:\
      \ [encode thoughts](Інструменти%20ДМ/CLI/spells/encode-thoughts-ggr.md) (see\
      \ chapter 2), [friends](Інструменти%20ДМ/CLI/spells/friends-xphb.md)\n\n3/day\
      \ each: [charm person](Інструменти%20ДМ/CLI/spells/charm-person-xphb.md),\
      \ [detect thoughts](Інструменти%20ДМ/CLI/spells/detect-thoughts-xphb.md), [mage\
      \ armor](Інструменти%20ДМ/CLI/spells/mage-armor-xphb.md), [sleep](Інструмент\
      и%20ДМ/CLI/spells/sleep-xphb.md), [suggestion](Інструменти%20ДМ/CLI/spells/suggestion-xphb.md)\n\
      \n1/day each: [dominate person](Інструменти%20ДМ/CLI/spells/dominate-person-xphb.md),\
      \ [mass suggestion](Інструменти%20ДМ/CLI/spells/mass-suggestion-xphb.md), [modify\
      \ memory](Інструменти%20ДМ/CLI/spells/modify-memory-xphb.md)"
    "name": "Innate Spellcasting (Psionics)"
  - "desc": "The mage wears a [spies' murmur](Інструменти%20ДМ/CLI/items/spies-murmur-ggr.md)\
      \ (see chapter 5)."
    "name": "Special Equipment"
"actions":
  - "desc": "Melee  or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. Hit: 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
"source":
  - "GGR"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/mind-mage-ggr.webp"
```
^statblock