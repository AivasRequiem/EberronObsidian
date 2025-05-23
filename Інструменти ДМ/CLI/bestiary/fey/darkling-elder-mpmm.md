---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- Darkling Elder
---
# [Darkling Elder](Інструменти ДМ\CLI\bestiary\fey/darkling-elder-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 84*  

A wise and respected darkling can undergo a ritual to become an elder. Other elders mark the supplicant with glowing tattoos, channeling away some of the darkling's absorbed light. If the ritual succeeds, the darkling grows into a taller, elf-like form. The darkling perishes if the ritual fails.

## Darklings

Ancient legends speak of a seelie fey who betrayed the Summer Queen. In the Summer Queens' wrath, she cursed every member of his house. The seelie fey's true name has been stricken from history, but the stories call him Dubh Catha ("Dark Crow" in Common), and other Fey refer to the house's descendants as dubh sith—"darklings." Darklings dwell in secluded caverns and chambers beneath the towns of other species. From such enclaves, they quietly ply their trade as thieves and assassins.

```statblock
"name": "Darkling Elder (MPMM)"
"size": "Medium"
"type": "fey"
"alignment": "Typically  Chaotic Neutral"
"ac": !!int "15"
"ac_class": "[studded leather armor](Інструменти%20ДМ/CLI/items/studded-leather-armor-xphb.md)"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"modifier": !!int "3"
"stats":
  - !!int "13"
  - !!int "17"
  - !!int "12"
  - !!int "10"
  - !!int "14"
  - !!int "13"
"speed": "30 ft."
"skillsaves":
  - "name": "[Acrobatics](Інструменти%20ДМ/CLI/rules/skills.md#Acrobatics)"
    "desc": "+5"
  - "name": "[Deception](Інструменти%20ДМ/CLI/rules/skills.md#Deception)"
    "desc": "+3"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Stealth](Інструменти%20ДМ/CLI/rules/skills.md#Stealth)"
    "desc": "+7"
"senses": "blindsight 30 ft., darkvision 120 ft., passive Perception 16"
"languages": "Elvish, Sylvan"
"cr": "2"
"traits":
  - "desc": "When the darkling elder dies, magical light flashes out from it in a\
      \ 10-foot radius as its body and possessions, other than metal or magic objects,\
      \ burn to ash. Any creature in that area must make a DC 11 Constitution saving\
      \ throw. On a failed save, the creature takes 7 (2d6) radiant damage and is\
      \ [blinded](Інструменти%20ДМ/CLI/rules/conditions.md#Blinded) until the end\
      \ of its next turn. On a successful save, the creature takes half as much damage\
      \ and isn't [blinded](Інструменти%20ДМ/CLI/rules/conditions.md#Blinded)."
    "name": "Death Burn"
"actions":
  - "desc": "The darkling elder makes two Scimitar attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6\
      \ (1d6 + 3) slashing damage plus 7 (2d6) necrotic damage."
    "name": "Scimitar"
  - "desc": "The darkling elder casts [darkness](Інструменти%20ДМ/CLI/spells/darkness-xphb.md),\
      \ requiring no spell components and using Wisdom as the spellcasting ability.\n"
    "name": "Darkness (Recharges after a Short or Long Rest)"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/fey/token/darkling-elder-mpmm.webp"
```
^statblock

## Environment

forest, swamp, underdark, urban