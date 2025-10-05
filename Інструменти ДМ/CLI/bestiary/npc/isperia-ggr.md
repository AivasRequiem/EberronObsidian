---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/21
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- Isperia
---
# [Isperia](Інструменти ДМ\CLI\bestiary\npc/isperia-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 227*  

Isperia is the current guildmaster of the Azorius Senate. As a sphinx, she is aloof and values solitude above all. However, she has been forced to give up her privacy to deal with the increased crime and chaos on Ravnica.

Isperia is devoted to her guild's belief that law is the ultimate bulwark against chaos, and it is her steady hand that guides the Azorius through these uncertain times. As guildmaster, Isperia serves as the supreme judge, a role that takes advantage of her encyclopedic knowledge of Ravnica's labyrinthine legal system.

If an encounter turns violent, Isperia refrains from using lethal force if possible, preferring to subdue a wrongdoing so that the legal system can mete out justice.

```statblock
"name": "Isperia (GGR)"
"size": "Gargantuan"
"type": "monstrosity"
"alignment": "Lawful Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "261"
"hit_dice": "18d20 + 72"
"modifier": !!int "2"
"stats":
  - !!int "20"
  - !!int "14"
  - !!int "18"
  - !!int "23"
  - !!int "26"
  - !!int "20"
"speed": "40 ft., fly 60 ft."
"saves":
  - "dexterity": !!int "9"
  - "constitution": !!int "11"
  - "intelligence": !!int "13"
  - "wisdom": !!int "15"
"skillsaves":
  - "name": "[Arcana](Інструменти%20ДМ/CLI/rules/skills.md#Arcana)"
    "desc": "+13"
  - "name": "[History](Інструменти%20ДМ/CLI/rules/skills.md#History)"
    "desc": "+13"
  - "name": "[Insight](Інструменти%20ДМ/CLI/rules/skills.md#Insight)"
    "desc": "+15"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+15"
"damage_immunities": "psychic; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed),\
  \ [frightened](Інструменти%20ДМ/CLI/rules/conditions.md#Frightened)"
"senses": "truesight 120 ft., passive Perception 25"
"languages": "Common, Sphinx"
"cr": "21"
"traits":
  - "desc": "Isperia is a 15th-level Azorius spellcaster. Her spellcasting ability\
      \ is Wisdom (spell save DC 23, +14 to hit with spell attacks). Isperia has\
      \ the following cleric spells prepared:\n\nCantrips (at will): [guidance](І\
      нструменти%20ДМ/CLI/spells/guidance-xphb.md), [light](Інструменти%20ДМ/CLI/spells/light-xphb.md),\
      \ [resistance](Інструменти%20ДМ/CLI/spells/resistance-xphb.md), [sacred flame](І\
      нструменти%20ДМ/CLI/spells/sacred-flame-xphb.md), [thaumaturgy](Інструменти\
      %20ДМ/CLI/spells/thaumaturgy-xphb.md)\n\n1st level (4 slots): [command](І\
      нструменти%20ДМ/CLI/spells/command-xphb.md), [detect evil and good](Інструме\
      нти%20ДМ/CLI/spells/detect-evil-and-good-xphb.md), [ensnaring strike](Інстру\
      менти%20ДМ/CLI/spells/ensnaring-strike-xphb.md), [sanctuary](Інструменти%20Д\
      М/CLI/spells/sanctuary-xphb.md), [shield of faith](Інструменти%20ДМ/CLI/spells/shield-of-faith-xphb.md)\n\
      \n2nd level (3 slots): [arcane lock](Інструменти%20ДМ/CLI/spells/arcane-lock-xphb.md),\
      \ [augury](Інструменти%20ДМ/CLI/spells/augury-xphb.md), [calm emotions](Інст\
      рументи%20ДМ/CLI/spells/calm-emotions-xphb.md), [hold person](Інструменти%20Д\
      М/CLI/spells/hold-person-xphb.md), [silence](Інструменти%20ДМ/CLI/spells/silence-xphb.md),\
      \ [zone of truth](Інструменти%20ДМ/CLI/spells/zone-of-truth-xphb.md)\n\n3rd\
      \ level (3 slots): [bestow curse](Інструменти%20ДМ/CLI/spells/bestow-curse-xphb.md),\
      \ [clairvoyance](Інструменти%20ДМ/CLI/spells/clairvoyance-xphb.md), [counterspell](І\
      нструменти%20ДМ/CLI/spells/counterspell-xphb.md), [dispel magic](Інструменти\
      %20ДМ/CLI/spells/dispel-magic-xphb.md), [tongues](Інструменти%20ДМ/CLI/spells/tongues-xphb.md)\n\
      \n4th level (3 slots): [divination](Інструменти%20ДМ/CLI/spells/divination-xphb.md),\
      \ [locate creature](Інструменти%20ДМ/CLI/spells/locate-creature-xphb.md)\n\n\
      5th level (2 slots): [dispel evil and good](Інструменти%20ДМ/CLI/spells/dispel-evil-and-good-xphb.md),\
      \ [scrying](Інструменти%20ДМ/CLI/spells/scrying-xphb.md)\n\n6th level (1 slots):\
      \ [word of recall](Інструменти%20ДМ/CLI/spells/word-of-recall-xphb.md)\n\n7th\
      \ level (1 slots): [divine word](Інструменти%20ДМ/CLI/spells/divine-word-xphb.md)\n\
      \n8th level (1 slots): [antimagic field](Інструменти%20ДМ/CLI/spells/antimagic-field-xphb.md)"
    "name": "Spellcasting"
  - "desc": "Isperia's innate spellcasting ability is Wisdom (spell save DC 23). Isperia\
      \ can innately cast [imprisonment](Інструменти%20ДМ/CLI/spells/imprisonment-xphb.md)\
      \ twice per day, requiring no material components.\n"
    "name": "Innate Spellcasting"
  - "desc": "Isperia is immune to any effect that would sense her emotions or read\
      \ her thoughts, as well as any divination spell that she refuses. Wisdom ([Insight](І\
      нструменти%20ДМ/CLI/rules/skills.md#Insight)) checks made to ascertain her intentions\
      \ or sincerity have disadvantage."
    "name": "Inscrutable"
  - "desc": "If Isperia fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Isperia has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Isperia makes two claw attacks. She can cast a spell with a casting time\
      \ of 1 action in place of one claw attack."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +12 to hit, reach 5 ft., one target. Hit:\
      \ 21 (3d10 + 5) slashing damage. If the target is a creature, it must succeed\
      \ on a DC 23 Wisdom saving throw or take 14 (4d6) psychic damage after each\
      \ attack it makes against Isperia before the start of her next turn."
    "name": "Claw"
  - "desc": "Isperia chooses up to three creatures she can see within 90 feet of her.\
      \ Each target must succeed on a DC 23 Intelligence saving throw or Isperia chooses\
      \ an action for that target: Attack, Cast a Spell, Dash, Disengage, Dodge, Help,\
      \ Hide, Ready, Search, or Use an Object. The affected target can't take that\
      \ action for 1 minute. At the end of each of the target's turns, it can end\
      \ the effect on itself with a successful DC 23 Intelligence saving throw. A\
      \ target that succeeds on the saving throw becomes immune to Isperia's Supreme\
      \ Legal Authority for 24 hours."
    "name": "Supreme Legal Authority"
"legendary_actions":
  - "desc": "Isperia makes one claw attack."
    "name": "Claw Attack"
  - "desc": "Isperia casts a spell of 3rd level or lower from her list of prepared\
      \ spells, using a spell slot as normal."
    "name": "Cast a Spell (Costs 2 Actions)"
  - "desc": "Isperia uses Supreme Legal Authority."
    "name": "Supreme Legal Authority (Costs 3 Actions)"
"source":
  - "GGR"
"image": "Інструменти%20ДМ/CLI/bestiary/npc/token/isperia-ggr.webp"
```
^statblock