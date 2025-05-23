---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/23
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/dragon/metallic
statblock: inline
statblock-link: "#^statblock"
aliases:
- Ancient Silver Dragon
---
# [Ancient Silver Dragon](Інструменти ДМ\CLI\bestiary\dragon/ancient-silver-dragon-xmm.md)
*Source: Monster Manual (2024) p. 280. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

Ancient silver dragons pursue world-wide change. They defend their communities and allies, encouraging them to perform deeds worthy of legend. Some set their sights on other worlds and planes of existence, creating extraplanar alliances or combating multiplanar threats. They might have guises in multiple societies and forge generation-spanning friendships with heroic families or valorous groups.

## Silver Dragons

*Dragons of Courage and Fairness*

- **Habitat.** Mountain, Urban  
- **Treasure.** Arcana  

Silver dragons work to preserve peace and encourage greatness. They try to live as examples of decency while remaining watchful against evil.

Silver dragons typically dwell amid snow-capped mountains, though aspirations and congeniality drive some to instead live among cosmopolitan societies. Disguised as humanoids, they ally with artists, historians, knights, and humble leaders who learn from the past to create better futures.

Silver dragons take inspiration from legendary heroes and have grand ambitions. Many collect treasures that reflect these interests, such as histories, ancient art, and the gear of famous champions.

### Silver Dragon Lairs

Silver dragons typically lair in picturesque mountain retreats or on sculpted cloud "islands."

```statblock
"name": "Ancient Silver Dragon (XMM)"
"size": "Gargantuan"
"type": "dragon"
"subtype": "metallic"
"alignment": "Lawful Good"
"ac": !!int "22"
"hp": !!int "468"
"hit_dice": "24d20 + 216"
"modifier": !!int "14"
"stats":
  - !!int "30"
  - !!int "10"
  - !!int "29"
  - !!int "18"
  - !!int "15"
  - !!int "26"
"speed": "40 ft., fly 80 ft."
"saves":
  - "dexterity": "+7"
  - "wisdom": "+9"
"skillsaves":
  - "name": "[History](Інструменти%20ДМ/CLI/rules/skills.md#History)"
    "desc": "+11"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+16"
  - "name": "[Stealth](Інструменти%20ДМ/CLI/rules/skills.md#Stealth)"
    "desc": "+7"
"damage_immunities": "cold"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 26"
"languages": "Common, Draconic"
"cr": "23"
"traits":
  - "desc": "If the dragon fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (4/Day, or 5/Day in Lair)"
"actions":
  - "desc": "The dragon makes three Rend attacks. It can replace one attack with a\
      \ use of (A) Paralyzing Breath or (B) Spellcasting to cast [Ice Knife](Інстр\
      ументи%20ДМ/CLI/spells/ice-knife-xphb.md) (level 2 version)."
    "name": "Multiattack"
  - "desc": "Melee Attack Roll: +17, reach 15 ft. Hit: 19 (2d8 + 10) Slashing\
      \ damage plus 9 (2d8) Cold damage."
    "name": "Rend"
  - "desc": "Constitution Saving Throw: DC 24, each creature in a 90-foot [Cone](І\
      нструменти%20ДМ/CLI/rules/variant-rules/cone-area-of-effect-xphb.md). Failure:\
      \ 67 (15d8) Cold damage. Success: Half damage."
    "name": "Cold Breath (Recharge 5-6)"
  - "desc": "Constitution Saving Throw: DC 24, each creature in a 90-foot [Cone](І\
      нструменти%20ДМ/CLI/rules/variant-rules/cone-area-of-effect-xphb.md). 1st Failure:\
      \ The target has the [Incapacitated](Інструменти%20ДМ/CLI/rules/conditions.md#Incapacitated)\
      \ condition until the end of its next turn, when it repeats the save. 2nd Failure:\
      \ The target has the [Paralyzed](Інструменти%20ДМ/CLI/rules/conditions.md#Paralyzed)\
      \ condition, and it repeats the save at the end of each of its turns, ending\
      \ the effect on itself on a success. After 1 minute, it succeeds automatically."
    "name": "Paralyzing Breath"
  - "desc": "The dragon casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 23, +15 to\
      \ hit with spell attacks):\n\nAt will: [Detect Magic](Інструменти%20ДМ/CLI/spells/detect-magic-xphb.md),\
      \ [Hold Monster](Інструменти%20ДМ/CLI/spells/hold-monster-xphb.md), [Ice Knife](І\
      нструменти%20ДМ/CLI/spells/ice-knife-xphb.md) (level 2 version), [Shapechange](І\
      нструменти%20ДМ/CLI/spells/shapechange-xphb.md) (Beast or Humanoid form only,\
      \ no [Temporary Hit Points](Інструменти%20ДМ/CLI/rules/variant-rules/temporary-hit-points-xphb.md)\
      \ gained from the spell, and no Concentration or [Temporary Hit Points](Інст\
      рументи%20ДМ/CLI/rules/variant-rules/temporary-hit-points-xphb.md) required\
      \ to maintain the spell)\n\n1/day each: [Control Weather](Інструменти%20Д\
      М/CLI/spells/control-weather-xphb.md), [Ice Storm](Інструменти%20ДМ/CLI/spells/ice-storm-xphb.md)\
      \ (level 7 version), [Teleport](Інструменти%20ДМ/CLI/spells/teleport-xphb.md),\
      \ [Zone of Truth](Інструменти%20ДМ/CLI/spells/zone-of-truth-xphb.md)"
    "name": "Spellcasting"
"legendary_actions":
  - "desc": "The dragon uses Spellcasting to cast [Hold Monster](Інструменти%20ДМ\
      /CLI/spells/hold-monster-xphb.md). The dragon can't take this action again until\
      \ the start of its next turn."
    "name": "Chill"
  - "desc": "Dexterity Saving Throw: DC 23, each creature in a 60-foot-long, 10-foot-wide\
      \ [Line](Інструменти%20ДМ/CLI/rules/variant-rules/line-area-of-effect-xphb.md).\
      \ Failure: 14 (4d6) Cold damage, and the target is pushed up to 30 feet\
      \ straight away from the dragon. Success: Half damage only. Failure or Success:\
      \ The dragon can't take this action again until the start of its next turn."
    "name": "Cold Gale"
  - "desc": "The dragon moves up to half its [Speed](Інструменти%20ДМ/CLI/rules/variant-rules/speed-xphb.md),\
      \ and it makes one Rend attack."
    "name": "Pounce"
"regional_effects":
  - "desc": "The region containing an adult or ancient silver dragon's lair is changed\
      \ by its magic, creating the following effects:"
    "name": ""
  - "desc": "- Gentle Gusts. Winds buoy creatures that fall within 1 mile of the\
      \ lair. Such creatures descend at a rate of 60 feet per round and take no damage\
      \ from falling.  \n- Sun and Storms. While in its lair, the dragon can cast\
      \ [Control Weather](Інструменти%20ДМ/CLI/spells/control-weather-xphb.md), requiring\
      \ no Material components and using the same spellcasting ability as its Spellcasting\
      \ action.  "
    "name": ""
  - "desc": "If the dragon dies or moves its lair elsewhere, these effects end immediately."
    "name": ""
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/dragon/token/ancient-silver-dragon-xmm.webp"
```
^statblock

## Environment

mountain, urban