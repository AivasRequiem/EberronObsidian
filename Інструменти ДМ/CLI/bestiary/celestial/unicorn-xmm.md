---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/environment/feywild
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- Unicorn
---
# [Unicorn](Інструменти ДМ\CLI\bestiary\celestial/unicorn-xmm.md)
*Source: Monster Manual (2024). Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Unicorn

*Majestic and Magical Forest Master*

- **Habitat.** Forest, Planar (Feywild)  
- **Treasure.** Any  

Unicorns are majestic defenders of forests. They are revered by many Fey and other forest dwellers, and they do whatever they can to ensure the peace and health of those who shelter in their wooded realms.

### Unicorn Lairs

Unicorns dwell in unspoiled forests, particularly where benevolent Fey creatures live.

```statblock
"name": "Unicorn (XMM)"
"size": "Large"
"type": "celestial"
"alignment": "Lawful Good"
"ac": !!int "12"
"hp": !!int "97"
"hit_dice": "13d10 + 26"
"modifier": !!int "8"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "15"
  - !!int "11"
  - !!int "17"
  - !!int "16"
"speed": "50 ft."
"damage_immunities": "poison"
"condition_immunities": "[charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed),\
  \ [paralyzed](Інструменти%20ДМ/CLI/rules/conditions.md#Paralyzed), [poisoned](Ін\
  струменти%20ДМ/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Celestial, Elvish, Sylvan; telepathy 120 ft."
"cr": "5"
"traits":
  - "desc": "If the unicorn fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "The unicorn has [Advantage](Інструменти%20ДМ/CLI/rules/variant-rules/advantage-xphb.md)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The unicorn makes one Hooves attack and one Radiant Horn attack."
    "name": "Multiattack"
  - "desc": "Melee Attack Roll: +7, reach 5 ft. Hit: 11 (2d6 + 4) Bludgeoning\
      \ damage."
    "name": "Hooves"
  - "desc": "Melee Attack Roll: +7, reach 5 ft. Hit: 9 (1d10 + 4) Radiant\
      \ damage."
    "name": "Radiant Horn"
  - "desc": "The unicorn casts one of the following spells, requiring no spell components\
      \ and using Charisma as the spellcasting ability (spell save DC 14):\n\nAt\
      \ will: [Detect Evil and Good](Інструменти%20ДМ/CLI/spells/detect-evil-and-good-xphb.md),\
      \ [Druidcraft](Інструменти%20ДМ/CLI/spells/druidcraft-xphb.md)\n\n1/day each:\
      \ [Calm Emotions](Інструменти%20ДМ/CLI/spells/calm-emotions-xphb.md), [Dispel\
      \ Evil and Good](Інструменти%20ДМ/CLI/spells/dispel-evil-and-good-xphb.md),\
      \ [Entangle](Інструменти%20ДМ/CLI/spells/entangle-xphb.md), [Pass without Trace](І\
      нструменти%20ДМ/CLI/spells/pass-without-trace-xphb.md), [Word of Recall](Інс\
      трументи%20ДМ/CLI/spells/word-of-recall-xphb.md)"
    "name": "Spellcasting"
  - "desc": "The unicorn touches another creature with its horn and casts [Cure Wounds](І\
      нструменти%20ДМ/CLI/spells/cure-wounds-xphb.md) or [Lesser Restoration](Інст\
      рументи%20ДМ/CLI/spells/lesser-restoration-xphb.md) on that creature, using\
      \ the same spellcasting ability as Spellcasting.\n"
    "name": "Unicorn's Blessing (3/Day)"
"bonus_actions":
  - "desc": "The unicorn casts one of the following spells, requiring no spell components\
      \ and using Charisma as the spellcasting ability (spell save DC 14):\n\nAt\
      \ will: [Detect Evil and Good](Інструменти%20ДМ/CLI/spells/detect-evil-and-good-xphb.md),\
      \ [Druidcraft](Інструменти%20ДМ/CLI/spells/druidcraft-xphb.md)\n\n1/day each:\
      \ [Calm Emotions](Інструменти%20ДМ/CLI/spells/calm-emotions-xphb.md), [Dispel\
      \ Evil and Good](Інструменти%20ДМ/CLI/spells/dispel-evil-and-good-xphb.md),\
      \ [Entangle](Інструменти%20ДМ/CLI/spells/entangle-xphb.md), [Pass without Trace](І\
      нструменти%20ДМ/CLI/spells/pass-without-trace-xphb.md), [Word of Recall](Інс\
      трументи%20ДМ/CLI/spells/word-of-recall-xphb.md)"
    "name": "Spellcasting"
  - "desc": "The unicorn touches another creature with its horn and casts [Cure Wounds](І\
      нструменти%20ДМ/CLI/spells/cure-wounds-xphb.md) or [Lesser Restoration](Інст\
      рументи%20ДМ/CLI/spells/lesser-restoration-xphb.md) on that creature, using\
      \ the same spellcasting ability as Spellcasting.\n"
    "name": "Unicorn's Blessing (3/Day)"
"legendary_actions":
  - "desc": "The unicorn moves up to half its [Speed](Інструменти%20ДМ/CLI/rules/variant-rules/speed-xphb.md)\
      \ without provoking Opportunity Attacks, and it makes one Radiant Horn attack."
    "name": "Charging Horn"
  - "desc": "The unicorn targets itself or one creature it can see within 60 feet\
      \ of itself. The target gains 10 (3d6) [Temporary Hit Points](Інструменти\
      %20ДМ/CLI/rules/variant-rules/temporary-hit-points-xphb.md), and its AC increases\
      \ by 2 until the end of the unicorn's next turn. The unicorn can't take this\
      \ action again until the start of its next turn."
    "name": "Shimmering Shield"
"regional_effects":
  - "desc": "The region containing a unicorn's lair is changed by its presence, creating\
      \ the following effects:"
    "name": ""
  - "desc": "- Obscuring Foliage. The unicorn and its allies have [Advantage](І\
      нструменти%20ДМ/CLI/rules/variant-rules/advantage-xphb.md) on Dexterity ([Stealth](І\
      нструменти%20ДМ/CLI/rules/skills.md#Stealth)) checks while within 1 mile of\
      \ the lair.  \n- Positive Energy. Whenever a creature within 1 mile of the\
      \ lair regains [Hit Points](Інструменти%20ДМ/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ from a spell, it regains the maximum number of [Hit Points](Інструменти%20Д\
      М/CLI/rules/variant-rules/hit-points-xphb.md) possible. Additionally, the effects\
      \ of curses are suppressed within 1 mile of the lair.  "
    "name": ""
  - "desc": "If the unicorn dies or moves its lair elsewhere, these effects end immediately."
    "name": ""
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/celestial/token/unicorn-xmm.webp"
```
^statblock

## Environment

forest, planar, feywild