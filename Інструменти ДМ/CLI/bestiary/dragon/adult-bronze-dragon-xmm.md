---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/dragon/metallic
statblock: inline
statblock-link: "#^statblock"
aliases:
- Adult Bronze Dragon
---
# [Adult Bronze Dragon](Інструменти ДМ\CLI\bestiary\dragon/adult-bronze-dragon-xmm.md)
*Source: Monster Manual (2024) p. 59. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

Adult bronze dragons often dwell near places they defend or where they help others work toward goals. They might become patrons of whole cities, advising leaders and helping generations flourish.

## Bronze Dragons

*Dragons of Potential and Preservation*

- **Habitat.** Coastal  
- **Treasure.** Implements  

Where bronze dragons dwell, wonders flourish. Imaginative yet mindful, these metallic dragons work toward greatness and help others achieve all they can. They strive to preserve innovations, from the works of past civilizations to new discoveries, and they share such works widely. When dealing with shorter-lived beings, bronze dragons prefer to win them over through conversation and cultivation, but they don't shy from battle when villains keep others from achieving their potential.

Bronze dragons enjoy the power and endless possibilities of the sea, and they often make their lairs in places of natural beauty or communities they wish to preserve. Within their dwellings, bronze dragons hoard things they believe will be useful one day. They salvage treasure lost to the sea, reclaiming wealth or sunken ships.

### Bronze Dragon Lairs

Bronze dragons usually make their homes near or under the sea.

```statblock
"name": "Adult Bronze Dragon (XMM)"
"size": "Huge"
"type": "dragon"
"subtype": "metallic"
"alignment": "Lawful Good"
"ac": !!int "18"
"hp": !!int "212"
"hit_dice": "17d12 + 102"
"modifier": !!int "10"
"stats":
  - !!int "25"
  - !!int "10"
  - !!int "23"
  - !!int "16"
  - !!int "15"
  - !!int "20"
"speed": "40 ft., fly 80 ft., swim 40 ft."
"saves":
  - "dexterity": "+5"
  - "wisdom": "+7"
"skillsaves":
  - "name": "[Insight](Інструменти%20ДМ/CLI/rules/skills.md#Insight)"
    "desc": "+7"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+12"
  - "name": "[Stealth](Інструменти%20ДМ/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"damage_immunities": "lightning"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 22"
"languages": "Common, Draconic"
"cr": "15"
"traits":
  - "desc": "The dragon can breathe air and water."
    "name": "Amphibious"
  - "desc": "If the dragon fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day, or 4/Day in Lair)"
"actions":
  - "desc": "The dragon makes three Rend attacks. It can replace one attack with a\
      \ use of (A) Repulsion Breath or (B) Spellcasting to cast [Guiding Bolt](Інс\
      трументи%20ДМ/CLI/spells/guiding-bolt-xphb.md) (level 2 version)."
    "name": "Multiattack"
  - "desc": "Melee Attack Roll: +12, reach 10 ft. Hit: 16 (2d8 + 7) Slashing\
      \ damage plus 5 (d10) Lightning damage."
    "name": "Rend"
  - "desc": "Dexterity Saving Throw: DC 19, each creature in a 90-foot-long, 5-foot-wide\
      \ [Line](Інструменти%20ДМ/CLI/rules/variant-rules/line-area-of-effect-xphb.md).\
      \ Failure: 55 (10d10) Lightning damage. Success: Half damage."
    "name": "Lightning Breath (Recharge 5-6)"
  - "desc": "Strength Saving Throw: DC 19, each creature in a 30-foot [Cone](Інс\
      трументи%20ДМ/CLI/rules/variant-rules/cone-area-of-effect-xphb.md). Failure:\
      \ The target is pushed up to 60 feet straight away from the dragon and has the\
      \ [Prone](Інструменти%20ДМ/CLI/rules/conditions.md#Prone) condition."
    "name": "Repulsion Breath"
  - "desc": "The dragon casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 17, +10 to\
      \ hit with spell attacks):\n\nAt will: [Detect Magic](Інструменти%20ДМ/CLI/spells/detect-magic-xphb.md),\
      \ [Guiding Bolt](Інструменти%20ДМ/CLI/spells/guiding-bolt-xphb.md) (level 2\
      \ version), [Shapechange](Інструменти%20ДМ/CLI/spells/shapechange-xphb.md) (Beast\
      \ or Humanoid form only, no [Temporary Hit Points](Інструменти%20ДМ/CLI/rules/variant-rules/temporary-hit-points-xphb.md)\
      \ gained from the spell, and no Concentration or [Temporary Hit Points](Інст\
      рументи%20ДМ/CLI/rules/variant-rules/temporary-hit-points-xphb.md) required\
      \ to maintain the spell), [Speak with Animals](Інструменти%20ДМ/CLI/spells/speak-with-animals-xphb.md),\
      \ [Thaumaturgy](Інструменти%20ДМ/CLI/spells/thaumaturgy-xphb.md)\n\n1/day\
      \ each: [Detect Thoughts](Інструменти%20ДМ/CLI/spells/detect-thoughts-xphb.md),\
      \ [Water Breathing](Інструменти%20ДМ/CLI/spells/water-breathing-xphb.md)"
    "name": "Spellcasting"
"legendary_actions":
  - "desc": "The dragon uses Spellcasting to cast [Guiding Bolt](Інструменти%20ДМ\
      /CLI/spells/guiding-bolt-xphb.md) (level 2 version)."
    "name": "Guiding Light"
  - "desc": "The dragon moves up to half its [Speed](Інструменти%20ДМ/CLI/rules/variant-rules/speed-xphb.md),\
      \ and it makes one Rend attack."
    "name": "Pounce"
  - "desc": "Constitution Saving Throw: DC 17, each creature in a 20-foot-radius\
      \ [Sphere](Інструменти%20ДМ/CLI/rules/variant-rules/sphere-area-of-effect-xphb.md)\
      \ centered on a point the dragon can see within 90 feet. Failure: 10 (3d6)\
      \ Thunder damage, and the target has the [Deafened](Інструменти%20ДМ/CLI/rules/conditions.md#Deafened)\
      \ condition until the end of its next turn."
    "name": "Thunderclap"
"regional_effects":
  - "desc": "The region containing an adult or ancient bronze dragon's lair is changed\
      \ by its presence, creating the following effects:"
    "name": ""
  - "desc": "- Buoying Currents. Creatures within 1 mile of the lair that lack\
      \ a [Swim Speed](Інструменти%20ДМ/CLI/rules/variant-rules/swim-speed-xphb.md)\
      \ ignore the extra cost of movement while swimming.  \n- Sun and Storms.\
      \ While in its lair, the dragon can cast [Control Weather](Інструменти%20ДМ\
      /CLI/spells/control-weather-xphb.md), requiring no Material components and using\
      \ the same spellcasting ability as its Spellcasting action. When casting the\
      \ spell this way, the dragon can control the weather within 1 mile of its lair,\
      \ regardless if the dragon is inside or outside.  "
    "name": ""
  - "desc": "If the dragon dies or moves its lair elsewhere, these effects end immediately."
    "name": ""
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/dragon/token/adult-bronze-dragon-xmm.webp"
```
^statblock

## Environment

coastal