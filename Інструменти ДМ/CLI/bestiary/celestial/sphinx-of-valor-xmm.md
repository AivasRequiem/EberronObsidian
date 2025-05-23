---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/17
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/environment/upper
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- Sphinx of Valor
---
# [Sphinx of Valor](Інструменти ДМ\CLI\bestiary\celestial/sphinx-of-valor-xmm.md)
*Source: Monster Manual (2024) p. 294. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

Sphinxes of valor guard world-changing or dangerous secrets—evidence of weird truths, deadly Artifacts, and things that shouldn't exist. They inhabit hidden, magical sites and hold their duty above mortal life. If threatened, a sphinx of valor defends its charge with its supernaturally empowered roar and fierce strikes.

## Sphinxes

*Collectors and Keepers of Secrets*

- **Habitat.** Desert, Planar (Upper Planes)  
- **Treasure.** Arcana  

Sphinxes protect the secrets of the multiverse. Formed from the spirits of sages and explorers, sphinxes know the power of truth and the importance of preserving it. They share their wisdom only with those who prove themselves wise or overcome tests of worthiness, such as riddles or battles with dangerous beasts. Through their existences, sphinxes might change form as they gain more nuanced understanding of cosmic enigmas.

### Sphinx Lairs

Sphinxes typically dwell in places that hold great knowledge or prophetic magic.

> [!quote]  
> 
> Round she is, yet flat as a board
> 
> Altar of the Lupine Lords
> 
> Jewel on black velvet, pearl in the sea
> 
> Unchanged but e'erchanging eternally

> [!note]
> Answer to the riddle of White Plume Mountain: The Moon.

```statblock
"name": "Sphinx of Valor (XMM)"
"size": "Large"
"type": "celestial"
"alignment": "Lawful Neutral"
"ac": !!int "17"
"hp": !!int "199"
"hit_dice": "19d10 + 95"
"modifier": !!int "12"
"stats":
  - !!int "22"
  - !!int "10"
  - !!int "20"
  - !!int "16"
  - !!int "23"
  - !!int "18"
"speed": "40 ft., fly 60 ft."
"saves":
  - "dexterity": "+6"
  - "constitution": "+11"
  - "intelligence": "+9"
  - "wisdom": "+12"
"skillsaves":
  - "name": "[Arcana](Інструменти%20ДМ/CLI/rules/skills.md#Arcana)"
    "desc": "+9"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+12"
  - "name": "[Religion](Інструменти%20ДМ/CLI/rules/skills.md#Religion)"
    "desc": "+15"
"damage_resistances": "necrotic, radiant"
"damage_immunities": "psychic"
"condition_immunities": "[charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed),\
  \ [frightened](Інструменти%20ДМ/CLI/rules/conditions.md#Frightened)"
"senses": "truesight 120 ft., passive Perception 22"
"languages": "Celestial, Common"
"cr": "17"
"traits":
  - "desc": "No magic can observe the sphinx remotely or detect its thoughts without\
      \ its permission. Wisdom ([Insight](Інструменти%20ДМ/CLI/rules/skills.md#Insight))\
      \ checks made to ascertain its intentions or sincerity are made with [Disadvantage](І\
      нструменти%20ДМ/CLI/rules/variant-rules/disadvantage-xphb.md)."
    "name": "Inscrutable"
  - "desc": "If the sphinx fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day, or 4/Day in Lair)"
"actions":
  - "desc": "The sphinx makes two Claw attacks and uses Roar."
    "name": "Multiattack"
  - "desc": "Melee Attack Roll: +12, reach 5 ft. Hit: 20 (4d6 + 6) Slashing\
      \ damage."
    "name": "Claw"
  - "desc": "The sphinx emits a magical roar. Whenever it roars, the roar has a different\
      \ effect, as detailed below (the sequence resets when it takes a [Long Rest](І\
      нструменти%20ДМ/CLI/rules/variant-rules/long-rest-xphb.md)):\n\n- First Roar.\
      \ Wisdom Saving Throw: DC 20, each enemy in a 500-foot [Emanation](Інструм\
      енти%20ДМ/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating\
      \ from the sphinx. Failure: The target has the [Frightened](Інструменти%20Д\
      М/CLI/rules/conditions.md#Frightened) condition for 1 minute.  \n- Second\
      \ Roar. Wisdom Saving Throw: DC 20, each enemy in a 500-foot [Emanation](І\
      нструменти%20ДМ/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating\
      \ from the sphinx. Failure: The target has the [Paralyzed](Інструменти%20Д\
      М/CLI/rules/conditions.md#Paralyzed) condition, and it repeats the save at the\
      \ end of each of its turns, ending the effect on itself on a success. After\
      \ 1 minute, it succeeds automatically.  \n- Third Roar. Constitution Saving\
      \ Throw: DC 20, each enemy in a 500-foot [Emanation](Інструменти%20ДМ/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from the sphinx. Failure: 44 (8d10) Thunder damage, and the\
      \ target has the [Prone](Інструменти%20ДМ/CLI/rules/conditions.md#Prone) condition.\
      \ Success: Half damage only.  "
    "name": "Roar (3/Day)"
  - "desc": "The sphinx casts one of the following spells, requiring no Material components\
      \ and using Wisdom as the spellcasting ability (spell save DC 20):\n\nAt will:\
      \ [Detect Evil and Good](Інструменти%20ДМ/CLI/spells/detect-evil-and-good-xphb.md),\
      \ [Thaumaturgy](Інструменти%20ДМ/CLI/spells/thaumaturgy-xphb.md)\n\n1/day\
      \ each: [Detect Magic](Інструменти%20ДМ/CLI/spells/detect-magic-xphb.md),\
      \ [Dispel Magic](Інструменти%20ДМ/CLI/spells/dispel-magic-xphb.md), [Greater\
      \ Restoration](Інструменти%20ДМ/CLI/spells/greater-restoration-xphb.md), [Heroes'\
      \ Feast](Інструменти%20ДМ/CLI/spells/heroes-feast-xphb.md), [Zone of Truth](І\
      нструменти%20ДМ/CLI/spells/zone-of-truth-xphb.md)"
    "name": "Spellcasting"
"legendary_actions":
  - "desc": "The sphinx can teleport up to 30 feet to an unoccupied space it can see,\
      \ and it makes one Claw attack."
    "name": "Arcane Prowl"
  - "desc": "Constitution Saving Throw: DC 16, one creature the sphinx can see within\
      \ 120 feet. Failure: The target gains 1 [Exhaustion](Інструменти%20ДМ/CLI/rules/conditions.md#Exhaustion)\
      \ level. While the target has any [Exhaustion](Інструменти%20ДМ/CLI/rules/conditions.md#Exhaustion)\
      \ levels, it appears 3d10 years older. Failure or Success: The sphinx can't\
      \ take this action again until the start of its next turn."
    "name": "Weight of Years"
"regional_effects":
  - "desc": "The region containing a sphinx of lore's or sphinx of valor's lair is\
      \ altered by its presence, creating the following effects:"
    "name": ""
  - "desc": "- Distant Sight. While in its lair, the sphinx can cast [Clairvoyance](І\
      нструменти%20ДМ/CLI/spells/clairvoyance-xphb.md), requiring no spell components\
      \ and using the same spellcasting ability as its Spellcasting action. When cast\
      \ this way, the spell's range is 1 mile.  \n- Infusion of Knowledge. Whenever\
      \ the sphinx or one of its allies takes a [Study](Інструменти%20ДМ/CLI/rules/actions.md#Study)\
      \ action while within 1 mile of the lair, it adds d6 to any ability check\
      \ it makes for that action.  "
    "name": ""
  - "desc": "If the sphinx dies or moves its lair elsewhere, these effects end immediately."
    "name": ""
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/celestial/token/sphinx-of-valor-xmm.webp"
```
^statblock

## Environment

desert, planar, upper