---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bam
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- Mercane
---
# [Mercane](Інструменти ДМ\CLI\bestiary\celestial/mercane-bam.md)
*Source: Boo's Astral Menagerie p. 37, Light of Xaryxis*  

Mercanes are the mysterious, magical creations of one or more deities whose portfolios revolve around fair commerce. Standing 12 feet tall, they are lanky blue beings who dress in elegant robes and have elongated heads and long, spindly fingers.

Mercanes conduct most of their business in Wildspace and the Astral Sea. To a mercane, commerce can take many forms, from the trading of goods and services to the trading of ideas and information. Mercanes are best known, however, for procuring and selling magic items, including artifacts and spelljamming helms. It's rare to see more than one mercane at a time, though it's common for a mercane to be accompanied by underlings or bodyguards.

Mercanes will conduct business with anyone, fairly and reliably, provided the other party has neither harmed nor swindled another mercane in the past. Mercanes have a special form of telepathy that enables them to communicate with one another across the multiverse. A mercane often uses this ability to warn another mercanes about individuals who are dangerous or unreliable. Once a mercane has been offended by someone, getting back into their good graces is next to impossible.

```statblock
"name": "Mercane (BAM)"
"size": "Large"
"type": "celestial"
"alignment": "typically  Lawful Neutral"
"ac": !!int "13"
"ac_class": "[mage armor](Інструменти%20ДМ/CLI/spells/mage-armor-xphb.md)"
"hp": !!int "75"
"hit_dice": "10d10 + 20"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "15"
  - !!int "18"
  - !!int "16"
  - !!int "15"
"speed": "30 ft."
"saves":
  - "intelligence": "+7"
  - "wisdom": "+6"
  - "charisma": "+5"
"skillsaves":
  - "name": "[Insight](Інструменти%20ДМ/CLI/rules/skills.md#Insight)"
    "desc": "+9"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Persuasion](Інструменти%20ДМ/CLI/rules/skills.md#Persuasion)"
    "desc": "+5"
"senses": "passive Perception 16"
"languages": "Common, Giant, telepathy 60 ft. (see also Mercane telepathy)"
"cr": "5"
"traits":
  - "desc": "The mercane can communicate telepathically with any other mercane it\
      \ knows, regardless of the distance between them."
    "name": "Mercane Telepathy"
"actions":
  - "desc": "The mercane makes three Psi-Imbued Blade attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 10\
      \ (2d6 + 3) slashing damage, and if the target is a creature, it must succeed\
      \ on a DC 15 Wisdom saving throw or be [frightened](Інструменти%20ДМ/CLI/rules/conditions.md#Frightened)\
      \ of the mercane until the end of the target's next turn."
    "name": "Psi-Imbued Blade"
  - "desc": "The mercane casts one of the following spells, requiring no spell components\
      \ and using Intelligence as the spellcasting ability (spell save DC 15):\n\n\
      At will: [detect magic](Інструменти%20ДМ/CLI/spells/detect-magic-xphb.md),\
      \ [light](Інструменти%20ДМ/CLI/spells/light-xphb.md)\n\n1/day each: [dimension\
      \ door](Інструменти%20ДМ/CLI/spells/dimension-door-xphb.md), [invisibility](І\
      нструменти%20ДМ/CLI/spells/invisibility-xphb.md), [mage armor](Інструменти%20Д\
      М/CLI/spells/mage-armor-xphb.md) (self only)"
    "name": "Spellcasting (Psionics)"
"source":
  - "BAM"
  - "LoX"
"image": "Інструменти%20ДМ/CLI/bestiary/celestial/token/mercane-bam.webp"
```
^statblock