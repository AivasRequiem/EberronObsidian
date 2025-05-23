---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/16
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- Star Spawn Larva Mage
---
# [Star Spawn Larva Mage](Інструменти ДМ\CLI\bestiary\aberration/star-spawn-larva-mage-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 228*  

A larva mage is a nightmarish combination of a mortal body and otherworldly substance. When a powerful cultist of a wormlike entity such as Kyuss or Kezef—usually a warlock or other spellcaster—contacts the comet-borne emissary of an Elder Evil, the emissary can merge with a mortal consciousness to create a larva mage. None of the original cultist's personality survives the transformation; what emerges is wholly alien.

## Star Spawn

> [!quote] A quote from Mordenkainen  
> 
> Stars don't spawn these creatures.
> 
> Such beautiful lights shouldn't be blamed for such balefulness.

The Material Plane represents only one small part of the multiverse. Beyond the best-known planes of existence lie realms alien to mortal life. Some are so hostile that even a moment's contact is enough to break a mortal's mind. Yet beings do exist that are native to these realms: entities that are ever hungering, searching, warring, and sometimes dreaming. These Elder Evils are far older than most of the mortal peoples and always inimical to such creatures' minds.

However much they might desire to enter and dominate the Material Plane, the Elder Evils are unable or unwilling to leave their realms. Some are imprisoned in their dimensions by external forces, some are inextricably bound to their home realities, and others simply can't find any way out.

The creatures known as star spawn are the heralds, servants, and soldiers of the Elder Evils, capable of taking on forms that can journey to the Material Plane. They arrive most often in the wake of a comet—or perhaps this phenomenon merely signals that star spawn are in the vicinity and available for communication. When the signs are right, cultists gather together, read aloud their blasphemous texts, and conduct the mind-searing rituals that guide star spawn into the world.

### Elder Evil Blessings

Disciples of certain Elder Evils can bestow supernatural gifts on those who serve that cult, including star spawn. The following powers are unique to specific cults; typically a creature has only one.

- Cult of Atropus, the World Born Dead  
- Cult of Borem, of the Lake of Boiling Mud  
- Cult of Haask, the Voice of Hargut  
- Cult of Tharizdun, the Chained God  
- Cult of Tyranthraxus, the Flamed One  

```statblock
"name": "Star Spawn Larva Mage (MPMM)"
"size": "Medium"
"type": "aberration"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "168"
"hit_dice": "16d8 + 96"
"modifier": !!int "1"
"stats":
  - !!int "17"
  - !!int "12"
  - !!int "23"
  - !!int "18"
  - !!int "12"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "dexterity": "+6"
  - "wisdom": "+6"
  - "charisma": "+8"
"skillsaves":
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+6"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "psychic"
"condition_immunities": "[charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed),\
  \ [frightened](Інструменти%20ДМ/CLI/rules/conditions.md#Frightened), [paralyzed](І\
  нструменти%20ДМ/CLI/rules/conditions.md#Paralyzed), [petrified](Інструменти%20ДМ\
  /CLI/rules/conditions.md#Petrified), [poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned),\
  \ [restrained](Інструменти%20ДМ/CLI/rules/conditions.md#Restrained)"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": "Deep Speech"
"cr": "16"
"traits":
  - "desc": "When the mage is reduced to 0 hit points, it breaks apart into a [swarm\
      \ of insects](Інструменти%20ДМ/CLI/bestiary/beast/swarm-of-insects-xmm.md) in\
      \ the same space. Unless the swarm is destroyed, the mage reforms from it 24\
      \ hours later."
    "name": "Return to Worms"
"actions":
  - "desc": "The mage makes three Slam or Eldritch Bolt attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit:\
      \ 7 (1d8 + 3) bludgeoning damage, and the target must succeed on a DC 19 Constitution\
      \ saving throw or be [poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned)\
      \ until the end of its next turn."
    "name": "Slam"
  - "desc": "Ranged Spell Attack: +8 to hit, range 60 ft., one target. Hit:\
      \ 19 (3d10 + 3) force damage."
    "name": "Eldritch Bolt"
  - "desc": "Each creature other than a star spawn within 10 feet of the mage must\
      \ succeed on a DC 19 Dexterity saving throw or take 22 (5d8) necrotic damage\
      \ and be [blinded](Інструменти%20ДМ/CLI/rules/conditions.md#Blinded) and [restrained](І\
      нструменти%20ДМ/CLI/rules/conditions.md#Restrained) by masses of swarming worms.\
      \ The affected creature takes 22 (5d8) necrotic damage at the start of each\
      \ of the mage's turns. The creature can repeat the saving throw at the end of\
      \ each of its turns, ending the effect on itself on a success."
    "name": "Plague of Worms (Recharge 6)"
  - "desc": "The mage casts one of the following spells, requiring no material components\
      \ and using Charisma as the spellcasting ability (spell save DC 16):\n\nAt\
      \ will: [mage hand](Інструменти%20ДМ/CLI/spells/mage-hand-xphb.md), [message](І\
      нструменти%20ДМ/CLI/spells/message-xphb.md), [minor illusion](Інструменти%20Д\
      М/CLI/spells/minor-illusion-xphb.md)\n\n1/day: [dominate monster](Інстру\
      менти%20ДМ/CLI/spells/dominate-monster-xphb.md)"
    "name": "Spellcasting"
"reactions":
  - "desc": "When a creature within 20 feet of the mage fails a saving throw, the\
      \ mage gains 10 temporary hit points."
    "name": "Feed on Weakness"
"legendary_actions":
  - "desc": "The mage makes one Slam attack."
    "name": "Slam"
  - "desc": "The mage makes one Eldritch Bolt attack."
    "name": "Eldritch Bolt (Costs 2 Actions)"
  - "desc": "Each creature [restrained](Інструменти%20ДМ/CLI/rules/conditions.md#Restrained)\
      \ by the mage's Plague of Worms takes 13 (3d8) necrotic damage, and the mage\
      \ gains 6 temporary hit points."
    "name": "Feed (Costs 3 Actions)"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/aberration/token/star-spawn-larva-mage-mpmm.webp"
```
^statblock

## Environment

mountain