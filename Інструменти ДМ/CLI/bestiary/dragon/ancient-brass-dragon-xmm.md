---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/20
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/dragon/metallic
statblock: inline
statblock-link: "#^statblock"
aliases:
- Ancient Brass Dragon
---
# [Ancient Brass Dragon](Інструменти ДМ\CLI\bestiary\dragon/ancient-brass-dragon-xmm.md)
*Source: Monster Manual (2024) p. 56. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

Ancient brass dragons create worlds-spanning networks. They combat forces of repression and misinformation, helping people learn from the mistakes of the past. Either personally or through webs of messengers, ancient brass dragons keep allies informed about challenges they can face together.

## Brass Dragons

*Dragons of Lore and Rapport*

- **Habitat.** Desert  
- **Treasure.** Arcana  

Gregarious and outgoing, brass dragons relish sharing knowledge and stories. Although these metallic dragons favor arid lands, they cheerfully journey considerable distances to visit friendly creatures, pass on what they've learned, and collect news. Though good natured, brass dragons don't shirk from combat when necessary, thwarting foes with magical sleep and searing them with flame.

Brass dragons favor warm climes, particularly steppes and rocky or sandy deserts, and they usually dwell near prominent crossroads or oases that regularly draw visitors. They enjoy adopting Humanoid forms, disguising themselves as traveling merchants, scholars, storytellers, or anyone else invested in others' stories.

Brass dragons collect eclectic objects. While such items might seem like knickknacks, each is part of a story—perhaps a nostalgic memento or evidence of a tale passed into myth. An old friend's hat and the crown of the last ruler of a forgotten dynasty could occupy the same shelf in a brass dragon's hoard.

### Brass Dragon Lairs

Brass dragons usually dwell in secret caves and canyons near well-traveled routes.

```statblock
"name": "Ancient Brass Dragon (XMM)"
"size": "Gargantuan"
"type": "dragon"
"subtype": "metallic"
"alignment": "Chaotic Good"
"ac": !!int "20"
"hp": !!int "332"
"hit_dice": "19d20 + 133"
"modifier": !!int "12"
"stats":
  - !!int "27"
  - !!int "10"
  - !!int "25"
  - !!int "16"
  - !!int "15"
  - !!int "22"
"speed": "40 ft., burrow 40 ft., fly 80 ft."
"saves":
  - "dexterity": "+6"
  - "wisdom": "+8"
"skillsaves":
  - "name": "[History](Інструменти%20ДМ/CLI/rules/skills.md#History)"
    "desc": "+9"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+14"
  - "name": "[Persuasion](Інструменти%20ДМ/CLI/rules/skills.md#Persuasion)"
    "desc": "+12"
  - "name": "[Stealth](Інструменти%20ДМ/CLI/rules/skills.md#Stealth)"
    "desc": "+6"
"damage_immunities": "fire"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 24"
"languages": "Common, Draconic"
"cr": "20"
"traits":
  - "desc": "If the dragon fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (4/Day, or 5/Day in Lair)"
"actions":
  - "desc": "The dragon makes three Rend attacks. It can replace one attack with a\
      \ use of (A) Sleep Breath or (B) Spellcasting to cast [Scorching Ray](Інстру\
      менти%20ДМ/CLI/spells/scorching-ray-xphb.md) (level 3 version)."
    "name": "Multiattack"
  - "desc": "Melee Attack Roll: +14, reach 15 ft. Hit: 19 (2d10 + 8) Slashing\
      \ damage plus 7 (2d6) Fire damage."
    "name": "Rend"
  - "desc": "Dexterity Saving Throw: DC 21, each creature in a 90-foot-long, 5-foot-wide\
      \ [Line](Інструменти%20ДМ/CLI/rules/variant-rules/line-area-of-effect-xphb.md).\
      \ Failure: 58 (13d8) Fire damage. Success: Half damage."
    "name": "Fire Breath (Recharge 5-6)"
  - "desc": "Constitution Saving Throw: DC 21, each creature in a 90-foot [Cone](І\
      нструменти%20ДМ/CLI/rules/variant-rules/cone-area-of-effect-xphb.md). Failure:\
      \ The target has the [Incapacitated](Інструменти%20ДМ/CLI/rules/conditions.md#Incapacitated)\
      \ condition until the end of its next turn, at which point it repeats the save.\
      \ 2nd Failure: The target has the [Unconscious](Інструменти%20ДМ/CLI/rules/conditions.md#Unconscious)\
      \ condition for 10 minutes. This effect ends for the target if it takes damage\
      \ or a creature within 5 feet of it takes an action to wake it."
    "name": "Sleep Breath"
  - "desc": "The dragon casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 20):\n\nAt\
      \ will: [Detect Magic](Інструменти%20ДМ/CLI/spells/detect-magic-xphb.md),\
      \ [Minor Illusion](Інструменти%20ДМ/CLI/spells/minor-illusion-xphb.md), [Scorching\
      \ Ray](Інструменти%20ДМ/CLI/spells/scorching-ray-xphb.md) (level 3 version),\
      \ [Shapechange](Інструменти%20ДМ/CLI/spells/shapechange-xphb.md) (Beast or Humanoid\
      \ form only, no [Temporary Hit Points](Інструменти%20ДМ/CLI/rules/variant-rules/temporary-hit-points-xphb.md)\
      \ gained from the spell, and no Concentration or [Temporary Hit Points](Інст\
      рументи%20ДМ/CLI/rules/variant-rules/temporary-hit-points-xphb.md) required\
      \ to maintain the spell), [Speak with Animals](Інструменти%20ДМ/CLI/spells/speak-with-animals-xphb.md)\n\
      \n1/day each: [Control Weather](Інструменти%20ДМ/CLI/spells/control-weather-xphb.md),\
      \ [Detect Thoughts](Інструменти%20ДМ/CLI/spells/detect-thoughts-xphb.md)"
    "name": "Spellcasting"
"legendary_actions":
  - "desc": "The dragon uses Spellcasting to cast [Scorching Ray](Інструменти%20ДМ\
      /CLI/spells/scorching-ray-xphb.md) (level 3 version)."
    "name": "Blazing Light"
  - "desc": "The dragon moves up to half its [Speed](Інструменти%20ДМ/CLI/rules/variant-rules/speed-xphb.md),\
      \ and it makes one Rend attack."
    "name": "Pounce"
  - "desc": "Dexterity Saving Throw: DC 20, one creature the dragon can see within\
      \ 120 feet. Failure: 36 (8d8) Fire damage, and the target's [Speed](Інст\
      рументи%20ДМ/CLI/rules/variant-rules/speed-xphb.md) is halved until the end\
      \ of its next turn. Failure or Success: The dragon can't take this action\
      \ again until the start of its next turn."
    "name": "Scorching Sands"
"regional_effects":
  - "desc": "The area containing an adult or ancient brass dragon's lair is altered\
      \ by its presence, creating the following effects:"
    "name": ""
  - "desc": "- Mirages. While in its lair, the dragon can cast [Major Image](І\
      нструменти%20ДМ/CLI/spells/major-image-xphb.md), requiring no Material components\
      \ and using the same spellcasting ability as its Spellcasting action. When casting\
      \ the spell this way, the spell's range is 1 mile, and the dragon doesn't need\
      \ to see the spot where the illusion appears.  \n- Refreshing Water. Water\
      \ within 1 mile of the lair is magically refreshing. A creature that drinks\
      \ such water gains 2d4 [Temporary Hit Points](Інструменти%20ДМ/CLI/rules/variant-rules/temporary-hit-points-xphb.md),\
      \ and the dragon is immediately aware of the creature's presence.  "
    "name": ""
  - "desc": "If the dragon dies or moves its lair elsewhere, these effects end immediately."
    "name": ""
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/dragon/token/ancient-brass-dragon-xmm.webp"
```
^statblock

## Environment

desert