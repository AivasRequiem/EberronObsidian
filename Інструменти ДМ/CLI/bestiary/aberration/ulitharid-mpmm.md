---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/aberration/mind-flayer
statblock: inline
statblock-link: "#^statblock"
aliases:
- Ulitharid
---
# [Ulitharid](Інструменти ДМ\CLI\bestiary\aberration/ulitharid-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 249*  

Very rarely, when a tadpole from the brine pool of an [elder brain](Інструменти%20ДМ/CLI/bestiary/aberration/elder-brain-mpmm.md) is implanted into a creature, that creature transforms into an ulitharid: a larger and more potent [mind flayer](Інструменти%20ДМ/CLI/bestiary/aberration/mind-flayer-xmm.md) with six tentacles. Illithids innately recognize that an ulitharid's survival is more important than their own. An [elder brain's](Інструменти%20ДМ/CLI/bestiary/aberration/elder-brain-mpmm.md) reaction to the rise of an ulitharid varies. In most colonies, the ulitharid becomes an elder brain's most favored servant, invested with power and authority. In others, the [elder brain](Інструменти%20ДМ/CLI/bestiary/aberration/elder-brain-mpmm.md) perceives an ulitharid as a potential rival and manipulates or quashes the ulitharid's ambitions accordingly.

When an ulitharid finds sharing leadership with an [elder brain](Інструменти%20ДМ/CLI/bestiary/aberration/elder-brain-mpmm.md) insufferable, it breaks off from the colony, taking a group of [mind flayers](Інструменти%20ДМ/CLI/bestiary/aberration/mind-flayer-xmm.md) with it, and moves to another location to form a new colony. After the death of the ulitharid's body, a special process transforms its brain into a new [elder brain](Інструменти%20ДМ/CLI/bestiary/aberration/elder-brain-mpmm.md) for the colony.

This process doesn't work on the brain of an ulitharid that dies a natural death, as such brains are too decrepit to be used. Instead, each ulitharid carries a psionically enhanced staff; when the ulitharid is ready to give up its life, it attaches the staff to the back of its head, and the staff cracks open its skull, enabling its brain to be extracted. The brain and the staff are then planted in the ulitharid's corpse, causing it to dissolve into ichor. This psionically potent slime helps to fuel the transformation of the area into a brine pool for the embryonic [elder brain](Інструменти%20ДМ/CLI/bestiary/aberration/elder-brain-mpmm.md).

```statblock
"name": "Ulitharid (MPMM)"
"size": "Large"
"type": "aberration"
"subtype": "mind flayer"
"alignment": "Typically  Lawful Evil"
"ac": !!int "15"
"ac_class": "[breastplate](Інструменти%20ДМ/CLI/items/breastplate-xphb.md)"
"hp": !!int "127"
"hit_dice": "17d10 + 14"
"modifier": !!int "1"
"stats":
  - !!int "15"
  - !!int "12"
  - !!int "15"
  - !!int "21"
  - !!int "19"
  - !!int "21"
"speed": "30 ft."
"saves":
  - "intelligence": "+9"
  - "wisdom": "+8"
  - "charisma": "+9"
"skillsaves":
  - "name": "[Arcana](Інструменти%20ДМ/CLI/rules/skills.md#Arcana)"
    "desc": "+9"
  - "name": "[Insight](Інструменти%20ДМ/CLI/rules/skills.md#Insight)"
    "desc": "+8"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+8"
  - "name": "[Stealth](Інструменти%20ДМ/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"senses": "darkvision 120 ft., passive Perception 18"
"languages": "Deep Speech, Undercommon, telepathy 2 miles"
"cr": "9"
"traits":
  - "desc": "The ulitharid is aware of the presence of creatures within 2 miles of\
      \ it that have an Intelligence score of 4 or higher. It knows the distance and\
      \ direction to each creature, as well as each creature's intelligence score,\
      \ but can't sense anything else about it. A creature protected by a [mind blank](І\
      нструменти%20ДМ/CLI/spells/mind-blank-xphb.md) spell, a [nondetection](Інстр\
      ументи%20ДМ/CLI/spells/nondetection-xphb.md) spell, or similar magic can't be\
      \ perceived in this manner."
    "name": "Creature Sense"
  - "desc": "The ulitharid has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "If an elder brain establishes a psychic link with the ulitharid, the\
      \ elder brain can form a psychic link with any other creature the ulitharid\
      \ can detect using its Creature Sense. Any such link ends if the creature falls\
      \ outside the telepathy ranges of both the ulitharid and the elder brain. The\
      \ ulitharid can maintain its psychic link with the elder brain regardless of\
      \ the distance between them, so long as they are both on the same plane of existence.\
      \ If the ulitharid is more than 5 miles away from the elder brain, it can end\
      \ the psychic link at any time (no action required)."
    "name": "Psionic Hub"
"actions":
  - "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one creature. Hit:\
      \ 27 (4d10 + 5) psychic damage. If the target is Large or smaller, it is [grappled](І\
      нструменти%20ДМ/CLI/rules/conditions.md#Grappled) (escape DC 14) and must succeed\
      \ on a DC 17 Intelligence saving throw or be [stunned](Інструменти%20ДМ/CLI/rules/conditions.md#Stunned)\
      \ until this grapple ends."
    "name": "Tentacles"
  - "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one [incapacitated](І\
      нструменти%20ДМ/CLI/rules/conditions.md#Incapacitated) Humanoid [grappled](І\
      нструменти%20ДМ/CLI/rules/conditions.md#Grappled) by the ulitharid. Hit: 55\
      \ (10d10) piercing damage. If this damage reduces the target to 0 hit points,\
      \ the ulitharid kills the target by extracting and devouring its brain."
    "name": "Extract Brain"
  - "desc": "The ulitharid magically emits psychic energy in a 60-foot cone. Each\
      \ creature in that area must succeed on a DC 17 Intelligence saving throw or\
      \ take 31 (4d12 + 5) psychic damage and be [stunned](Інструменти%20ДМ/CLI/rules/conditions.md#Stunned)\
      \ for 1 minute. A target can repeat the saving throw at the end of each of its\
      \ turns, ending the effect on itself on a success."
    "name": "Mind Blast (Recharge 5-6)"
  - "desc": "The ulitharid casts one of the following spells, requiring no spell components\
      \ and using Intelligence as the spellcasting ability (spell save DC 17):\n\n\
      At will: [detect thoughts](Інструменти%20ДМ/CLI/spells/detect-thoughts-xphb.md),\
      \ [levitate](Інструменти%20ДМ/CLI/spells/levitate-xphb.md)\n\n1/day each:\
      \ [dominate monster](Інструменти%20ДМ/CLI/spells/dominate-monster-xphb.md),\
      \ [feeblemind](Інструменти%20ДМ/CLI/spells/befuddlement-xphb.md), [mass suggestion](І\
      нструменти%20ДМ/CLI/spells/mass-suggestion-xphb.md), [plane shift](Інструмен\
      ти%20ДМ/CLI/spells/plane-shift-xphb.md) (self only), [project image](Інструм\
      енти%20ДМ/CLI/spells/project-image-xphb.md), [scrying](Інструменти%20ДМ/CLI/spells/scrying-xphb.md),\
      \ [telekinesis](Інструменти%20ДМ/CLI/spells/telekinesis-xphb.md)"
    "name": "Spellcasting (Psionics)"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/aberration/token/ulitharid-mpmm.webp"
```
^statblock

## Environment

underdark