---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/warlock
statblock: inline
statblock-link: "#^statblock"
aliases:
- Deathlock Mastermind
---
# [Deathlock Mastermind](Інструменти ДМ\CLI\bestiary\undead/deathlock-mastermind-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 87*  

Though deathlocks exist to serve their patrons, they retain some freedom when it comes to devising tactics and carrying out plans. Powerful deathlocks recruit lesser creatures to help them carry out their missions, becoming the masterminds behind vast conspiracies and intrigues that culminate in the accomplishment of great acts of evil.

## Deathlocks

The forging of a pact between a warlock and a patron is no minor occasion—at least not for the warlock. The consequences of breaking that pact can be dire and, in some cases, lethal. A warlock who fails to live up to a bargain with an evil patron runs the risk of rising from the dead as a deathlock, a foul Undead driven to serve its otherworldly patron.

An powerful necromancer might also discover the wicked methods of creating a deathlock and then subjugate it, acting as the deathlock's patron.

```statblock
"name": "Deathlock Mastermind (MPMM)"
"size": "Medium"
"type": "undead"
"subtype": "warlock"
"alignment": "Typically  Neutral Evil"
"ac": !!int "13"
"hp": !!int "110"
"hit_dice": "20d8 + 20"
"modifier": !!int "3"
"stats":
  - !!int "11"
  - !!int "16"
  - !!int "12"
  - !!int "15"
  - !!int "12"
  - !!int "17"
"speed": "30 ft."
"saves":
  - "intelligence": "+5"
  - "charisma": "+6"
"skillsaves":
  - "name": "[Arcana](Інструменти%20ДМ/CLI/rules/skills.md#Arcana)"
    "desc": "+5"
  - "name": "[History](Інструменти%20ДМ/CLI/rules/skills.md#History)"
    "desc": "+5"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+4"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](Інструменти%20ДМ/CLI/rules/conditions.md#Exhaustion),\
  \ [poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 14"
"languages": "the languages it knew in life"
"cr": "8"
"traits":
  - "desc": "Magical darkness doesn't impede the deathlock's [darkvision](Інструме\
      нти%20ДМ/CLI/rules/senses.md#Darkvision)."
    "name": "Devil's Sight"
  - "desc": "The deathlock has advantage on saving throws against any effect that\
      \ turns Undead."
    "name": "Turn Resistance"
  - "desc": "The deathlock doesn't require air, food, drink, or sleep."
    "name": "Unusual Nature"
"actions":
  - "desc": "The deathlock makes two Deathly Claw or Grave Bolt attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 13\
      \ (3d6 + 3 necrotic damage)."
    "name": "Deathly Claw"
  - "desc": "Ranged Spell Attack: +6 to hit, range 120 ft., one target. Hit:\
      \ 13 (3d8) necrotic damage. If the target is Large or smaller, it must succeed\
      \ on a DC 16 Strength saving throw or become [restrained](Інструменти%20ДМ/CLI/rules/conditions.md#Restrained)\
      \ as shadowy tendrils wrap around it for 1 minute. A [restrained](Інструмент\
      и%20ДМ/CLI/rules/conditions.md#Restrained) target can use its action to repeat\
      \ the saving throw, ending the effect on itself on a success."
    "name": "Grave Bolt"
  - "desc": "The deathlock casts one of the following spells, using Charisma as the\
      \ spellcasting ability (spell save DC 14):\n\nAt will: [detect magic](Ін\
      струменти%20ДМ/CLI/spells/detect-magic-xphb.md), [disguise self](Інструменти\
      %20ДМ/CLI/spells/disguise-self-xphb.md), [mage armor](Інструменти%20ДМ/CLI/spells/mage-armor-xphb.md),\
      \ [minor illusion](Інструменти%20ДМ/CLI/spells/minor-illusion-xphb.md)\n\n1/day\
      \ each: [darkness](Інструменти%20ДМ/CLI/spells/darkness-xphb.md), [dimension\
      \ door](Інструменти%20ДМ/CLI/spells/dimension-door-xphb.md), [dispel magic](І\
      нструменти%20ДМ/CLI/spells/dispel-magic-xphb.md), [fly](Інструменти%20ДМ/CLI/spells/fly-xphb.md),\
      \ [invisibility](Інструменти%20ДМ/CLI/spells/invisibility-xphb.md)"
    "name": "Spellcasting"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/undead/token/deathlock-mastermind-mpmm.webp"
```
^statblock

## Environment

urban