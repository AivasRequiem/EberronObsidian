---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
statblock-link: "#^statblock"
aliases:
- Green Abishai
---
# [Green Abishai](Інструменти ДМ\CLI\bestiary\fiend/green-abishai-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 40*  

Green abishais are adept at discovering secrets and other sensitive information, while their diplomatic skills and their magic ensure they can manipulate even the shrewdest opponents.

## Abishais

Each abishai was once a mortal who somehow won Tiamat's favor before death and, as a reward, found its soul transformed into a draconic devil to serve at her pleasure in the Nine Hells. Each type of abishai is associated with one of Tiamat's five dragon heads: black, blue, green, red, and white.

Tiamat deploys abishais as her agents, sending them forth to represent her interests in the Hells and across the multiverse. Some have simple tasks, such as delivering a message to cultists. Others have greater responsibilities, such as leading large groups, assassinating targets, and serving in armies. In all cases, abishais are fanatically loyal to Tiamat, ready to lay down their lives if needed.

Abishais stand outside the normal hierarchy of the Nine Hells, having their own chain of command and ultimately answering to Tiamat (and Asmodeus, when he chooses to use them). Other archdevils can command abishais to work for them, but most archdevils do so rarely, since it is never clear whether an abishai follows Tiamat's orders or Asmodeus's. There is inherent risk in countermanding an order given by Tiamat, but interfering with Asmodeus's plans invites certain destruction.

```statblock
"name": "Green Abishai (MPMM)"
"size": "Medium"
"type": "fiend"
"subtype": "devil"
"alignment": "Typically  Lawful Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "195"
"hit_dice": "26d8 + 78"
"modifier": !!int "3"
"stats":
  - !!int "12"
  - !!int "17"
  - !!int "16"
  - !!int "17"
  - !!int "12"
  - !!int "19"
"speed": "30 ft., fly 40 ft."
"saves":
  - "intelligence": "+8"
  - "charisma": "+9"
"skillsaves":
  - "name": "[Deception](Інструменти%20ДМ/CLI/rules/skills.md#Deception)"
    "desc": "+9"
  - "name": "[Insight](Інструменти%20ДМ/CLI/rules/skills.md#Insight)"
    "desc": "+6"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Persuasion](Інструменти%20ДМ/CLI/rules/skills.md#Persuasion)"
    "desc": "+9"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "[poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 16"
"languages": "Draconic, Infernal, telepathy 120 ft."
"cr": "15"
"traits":
  - "desc": "Magical darkness doesn't impede the abishai's [darkvision](Інструмент\
      и%20ДМ/CLI/rules/senses.md#Darkvision)."
    "name": "Devil's Sight"
  - "desc": "The abishai has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The abishai makes two Fiendish Claw attacks, or it makes one Fiendish\
      \ Claw attack and uses Spellcasting."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 12\
      \ (2d8 + 3) force damage. If the target is a creature, it must succeed on\
      \ a DC 16 Constitution saving throw or take 16 (3d10) poison damage and become\
      \ [poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned) for 1 minute.\
      \ The [poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned) target can\
      \ repeat the saving throw at the end of each of its turns, ending the effect\
      \ on itself on a success."
    "name": "Fiendish Claw"
  - "desc": "The abishai casts one of the following spells, requiring no material\
      \ components and using Charisma as the spellcasting ability (spell save DC 17):\n\
      \nAt will: [alter self](Інструменти%20ДМ/CLI/spells/alter-self-xphb.md),\
      \ [major image](Інструменти%20ДМ/CLI/spells/major-image-xphb.md)\n\n3/day\
      \ each: [charm person](Інструменти%20ДМ/CLI/spells/charm-person-xphb.md),\
      \ [detect thoughts](Інструменти%20ДМ/CLI/spells/detect-thoughts-xphb.md), [fear](І\
      нструменти%20ДМ/CLI/spells/fear-xphb.md)\n\n1/day each: [confusion](Інст\
      рументи%20ДМ/CLI/spells/confusion-xphb.md), [dominate person](Інструменти%20Д\
      М/CLI/spells/dominate-person-xphb.md), [mass suggestion](Інструменти%20ДМ/CLI/spells/mass-suggestion-xphb.md)"
    "name": "Spellcasting"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/fiend/token/green-abishai-mpmm.webp"
```
^statblock

## Environment

urban