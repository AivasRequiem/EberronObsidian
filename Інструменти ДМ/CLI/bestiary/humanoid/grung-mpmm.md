---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Grung
---
# [Grung](Інструменти ДМ\CLI\bestiary\humanoid/grung-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 149*  

The grung stat block represents a typical grung warrior or hunter, met either in a grung community or traveling elsewhere as a mercenary, game warden, guard, or bandit.

## Grungs

Grungs are frog-like folk found in rain forests and tropical jungles. These amphibians prefer shade and live in trees, but they maintain hatcheries for their offspring in well-guarded ground-level pools. About three months after hatching, a grung tadpole takes on the shape of an adult, and after another six months, the grung reaches maturity.

Born in a wide range of colors, grungs most often appear in shades of green, blue, purple, red, orange, and gold. All grungs secrete a substance that is harmless to them but poisonous to other creatures, and sometimes that substance has a special effect based on the grung's color (see "Variant: Grung Poison"). They also use this venom to poison their weapons.

```statblock
"name": "Grung (MPMM)"
"size": "Small"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "12"
"hp": !!int "11"
"hit_dice": "2d6 + 4"
"modifier": !!int "2"
"stats":
  - !!int "7"
  - !!int "14"
  - !!int "15"
  - !!int "10"
  - !!int "11"
  - !!int "10"
"speed": "25 ft., climb 25 ft."
"saves":
  - "dexterity": "+4"
"skillsaves":
  - "name": "[Athletics](Інструменти%20ДМ/CLI/rules/skills.md#Athletics)"
    "desc": "+2"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Stealth](Інструменти%20ДМ/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
  - "name": "[Survival](Інструменти%20ДМ/CLI/rules/skills.md#Survival)"
    "desc": "+2"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned)"
"senses": "passive Perception 12"
"languages": "Grung"
"cr": "1/4"
"traits":
  - "desc": "The grung can breathe air and water."
    "name": "Amphibious"
  - "desc": "Any creature that grapples the grung or otherwise comes into direct contact\
      \ with the grung's skin must succeed on a DC 12 Constitution saving throw or\
      \ become [poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned) for 1\
      \ minute. A [poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned) creature\
      \ no longer in direct contact with the grung can repeat the saving throw at\
      \ the end of each of its turns, ending the effect on itself on a success."
    "name": "Poisonous Skin"
  - "desc": "The grung's long jump is up to 25 feet and its high jump is up to 15\
      \ feet, with or without a running start."
    "name": "Standing Leap"
  - "desc": "If the grung isn't immersed in water for at least 1 hour during a day,\
      \ it suffers 1 level of [exhaustion](Інструменти%20ДМ/CLI/rules/conditions.md#Exhaustion)\
      \ at the end of that day. The grung can recover from this [exhaustion](Інстр\
      ументи%20ДМ/CLI/rules/conditions.md#Exhaustion) only through magic or by immersing\
      \ itself in water for at least 1 hour."
    "name": "Water Dependency"
"actions":
  - "desc": "Melee  or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. Hit: 4 (1d4 + 2) piercing damage plus 5 (2d4) poison\
      \ damage."
    "name": "Dagger"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/grung-mpmm.webp"
```
^statblock

## Environment

forest