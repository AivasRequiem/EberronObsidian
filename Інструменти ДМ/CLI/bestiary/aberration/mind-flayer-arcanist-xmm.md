---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- Mind Flayer Arcanist
---
# [Mind Flayer Arcanist](Інструменти ДМ\CLI\bestiary\aberration/mind-flayer-arcanist-xmm.md)
*Source: Monster Manual (2024) p. 214*  

Mind flayer arcanists enhance their psionic abilities with magic. Other mind flayers view those that undertake such experiments with disgust and fear.

## Mind Flayers

*Brain-Eating Underdark Tyrants*

- **Habitat.** Underdark  
- **Treasure.** Arcana  

Scattered survivors of a world-ruining, multiversal empire, mind flayers lurk in secret conclaves hidden deep within Material Plane worlds. Within their alien sanctuaries, these wicked masterminds—also known as illithids—reshape the Underdark and its inhabitants to serve their unfathomable whims. Mind flayers are feared for their psionic powers, which allow them to stun and control other creatures, and for their horrific method of feeding: using their four slimy tentacles to extract the brains of their victims.

Mind flayers are infamous plotters and manipulators, concocting plans that reach beyond their subterranean realms. Aside from using their psionic powers to control others, mind flayers often experiment with their own bizarre life cycles, implanting other creatures with illithid young to create unnatural servants. Creatures such as grimlocks and intellect devourers result from mind flayers' biological tampering, while other Underdark-dwelling monsters—including kuo-toa, quaggoths, and troglodytes—often serve illithid masters. Githyanki and githzerai have a long adversarial history with mind flayers and bear the scars of illithid manipulation.

### Mind Flayer Colonies

Mind flayers work as lone schemers, in mysterious cabals, or as part of worlds-spanning illithid conspiracies. In groups, mind flayers work toward bizarre agendas organized by an elder brain—a massive, brain-like being with incredible psionic powers. Without such a leader, groups of mind flayers fall to self-destructive squabbling. Roll on or choose a result from the Mind Flayer Machinations table to inspire an illithid conclave's plots.

**Mind Flayer Machinations**

`dice: [](mind-flayer-arcanist-xmm.md#^mind-flayer-machinations)`

| dice: 1d6 | The Mind Flayer Colony Seeks To... |
|-----------|------------------------------------|
| 1 | Blot out the sun so their Underdark-dwelling servants can invade the surface. |
| 2 | Create a new monstrous fusion between mind flayers and a legendary monster. |
| 3 | Forge a psionic network uniting illithid colonies. |
| 4 | Replace world leaders with intellect devourers. |
| 5 | Restore a vessel to travel through Wildspace. |
| 6 | Sacrifice the mental energy of a planet's populace to take control of a githyanki bastion. |
^mind-flayer-machinations

```statblock
"name": "Mind Flayer Arcanist (XMM)"
"size": "Medium"
"type": "aberration"
"alignment": "Lawful Evil"
"ac": !!int "16"
"hp": !!int "143"
"hit_dice": "26d8 + 26"
"modifier": !!int "6"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "13"
  - !!int "20"
  - !!int "17"
  - !!int "17"
"speed": "30 ft., fly 30 ft. (hover)"
"saves":
  - "dexterity": "+6"
  - "intelligence": "+9"
  - "wisdom": "+7"
  - "charisma": "+7"
"skillsaves":
  - "name": "[Arcana](Інструменти%20ДМ/CLI/rules/skills.md#Arcana)"
    "desc": "+13"
  - "name": "[Insight](Інструменти%20ДМ/CLI/rules/skills.md#Insight)"
    "desc": "+7"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Stealth](Інструменти%20ДМ/CLI/rules/skills.md#Stealth)"
    "desc": "+6"
"damage_immunities": "psychic"
"condition_immunities": "[charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed),\
  \ [frightened](Інструменти%20ДМ/CLI/rules/conditions.md#Frightened)"
"senses": "darkvision 120 ft., passive Perception 17"
"languages": "Deep Speech, Undercommon; telepathy 120 ft."
"cr": "11"
"traits":
  - "desc": "The mind flayer has [Advantage](Інструменти%20ДМ/CLI/rules/variant-rules/advantage-xphb.md)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The mind flayer makes three Arcane Tentacles attacks."
    "name": "Multiattack"
  - "desc": "Melee  or Ranged Attack Roll: +9, reach 5 ft. or range 120 ft. Hit:\
      \ 27 (4d10 + 5) Psychic damage, and the mind flayer can teleport the target\
      \ up to 30 feet to an unoccupied space the mind flayer can see on a surface\
      \ or liquid large enough to support the target. If this damage reduces the target\
      \ to 0 [Hit Points](Інструменти%20ДМ/CLI/rules/variant-rules/hit-points-xphb.md),\
      \ the mind flayer kills it and magically devours its brain."
    "name": "Arcane Tentacles"
  - "desc": "Intelligence Saving Throw: DC 17, each creature in a 40-foot [Emanation](І\
      нструменти%20ДМ/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating\
      \ from the mind flayer. Failure: 41 (8d8 + 5) Psychic damage, and the target\
      \ has the [Stunned](Інструменти%20ДМ/CLI/rules/conditions.md#Stunned) condition\
      \ until the end of the mind flayer's next turn. Success: Half damage only."
    "name": "Mind Burst (Recharge 5-6)"
  - "desc": "The mind flayer casts one of the following spells, requiring no spell\
      \ components and using Intelligence as the spellcasting ability (spell save\
      \ DC 17):\n\nAt will: [Detect Magic](Інструменти%20ДМ/CLI/spells/detect-magic-xphb.md),\
      \ [Detect Thoughts](Інструменти%20ДМ/CLI/spells/detect-thoughts-xphb.md), [Disguise\
      \ Self](Інструменти%20ДМ/CLI/spells/disguise-self-xphb.md), [Mage Hand](Інст\
      рументи%20ДМ/CLI/spells/mage-hand-xphb.md) (the hand is Invisible)\n\n1/day\
      \ each: [Clairvoyance](Інструменти%20ДМ/CLI/spells/clairvoyance-xphb.md),\
      \ [Dimension Door](Інструменти%20ДМ/CLI/spells/dimension-door-xphb.md), [Fireball](І\
      нструменти%20ДМ/CLI/spells/fireball-xphb.md) (level 5 version), [Lightning Bolt](І\
      нструменти%20ДМ/CLI/spells/lightning-bolt-xphb.md) (level 5 version), [Plane\
      \ Shift](Інструменти%20ДМ/CLI/spells/plane-shift-xphb.md) (self only), [Sending](І\
      нструменти%20ДМ/CLI/spells/sending-xphb.md)"
    "name": "Spellcasting"
  - "desc": "The mind flayer casts [Shield](Інструменти%20ДМ/CLI/spells/shield-xphb.md)\
      \ in response to that spell's trigger, using the same spellcasting ability as\
      \ Spellcasting.\n"
    "name": "Shield (2/Day)"
"reactions":
  - "desc": "The mind flayer casts one of the following spells, requiring no spell\
      \ components and using Intelligence as the spellcasting ability (spell save\
      \ DC 17):\n\nAt will: [Detect Magic](Інструменти%20ДМ/CLI/spells/detect-magic-xphb.md),\
      \ [Detect Thoughts](Інструменти%20ДМ/CLI/spells/detect-thoughts-xphb.md), [Disguise\
      \ Self](Інструменти%20ДМ/CLI/spells/disguise-self-xphb.md), [Mage Hand](Інст\
      рументи%20ДМ/CLI/spells/mage-hand-xphb.md) (the hand is Invisible)\n\n1/day\
      \ each: [Clairvoyance](Інструменти%20ДМ/CLI/spells/clairvoyance-xphb.md),\
      \ [Dimension Door](Інструменти%20ДМ/CLI/spells/dimension-door-xphb.md), [Fireball](І\
      нструменти%20ДМ/CLI/spells/fireball-xphb.md) (level 5 version), [Lightning Bolt](І\
      нструменти%20ДМ/CLI/spells/lightning-bolt-xphb.md) (level 5 version), [Plane\
      \ Shift](Інструменти%20ДМ/CLI/spells/plane-shift-xphb.md) (self only), [Sending](І\
      нструменти%20ДМ/CLI/spells/sending-xphb.md)"
    "name": "Spellcasting"
  - "desc": "The mind flayer casts [Shield](Інструменти%20ДМ/CLI/spells/shield-xphb.md)\
      \ in response to that spell's trigger, using the same spellcasting ability as\
      \ Spellcasting.\n"
    "name": "Shield (2/Day)"
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/aberration/token/mind-flayer-arcanist-xmm.webp"
```
^statblock

## Environment

underdark