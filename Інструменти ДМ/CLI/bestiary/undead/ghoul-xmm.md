---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Ghoul
---
# [Ghoul](Інструменти ДМ\CLI\bestiary\undead/ghoul-xmm.md)
*Source: Monster Manual (2024) p. 132. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

Ghouls rise from the bodies of cannibals and villains with depraved hungers. They form packs out of shared voracity.

## Ghouls

*Eaters of the Dead*

- **Habitat.** Swamp, Underdark, Urban  
- **Treasure.** Any  

Packs of ghouls haunt the rotten corners of the world, ravenously hunting for corpses and those soon to be corpses. These gaunt, animate cadavers with unnaturally long tongues dwell in catacombs and ruins where they devour the contents of graves and paralyze foes with vicious claws.

> [!quote]  
> 
> On a plain of teeth, in a temple of filth, the starving king wastes no morsel. Every coffin a banquet. Every slab a platter. Now is the time of feasting!


```statblock
"name": "Ghoul (XMM)"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"hp": !!int "22"
"hit_dice": "5d8"
"modifier": !!int "2"
"stats":
  - !!int "13"
  - !!int "15"
  - !!int "10"
  - !!int "7"
  - !!int "10"
  - !!int "6"
"speed": "30 ft."
"damage_immunities": "poison"
"condition_immunities": "[charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed),\
  \ [exhaustion](Інструменти%20ДМ/CLI/rules/conditions.md#Exhaustion), [poisoned](І\
  нструменти%20ДМ/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common"
"cr": "1"
"actions":
  - "desc": "The ghoul makes two Bite attacks."
    "name": "Multiattack"
  - "desc": "Melee Attack Roll: dice:1d20+4|noform|noparens|text(+4), reach 5\
      \ ft. Hit: dice:1d6+2|noform|noparens|avg|text(5) (1d6 + 2) Piercing damage\
      \ plus dice:1d6|noform|noparens|avg|text(3) (d6) Necrotic damage."
    "name": "Bite"
  - "desc": "Melee Attack Roll: dice:1d20+4|noform|noparens|text(+4), reach 5\
      \ ft. Hit: dice:1d4+2|noform|noparens|avg|text(4) (1d4 + 2) Slashing damage.\
      \ If the target is a creature that isn't an Undead or elf, it is subjected to\
      \ the following effect. Constitution Saving Throw: DC 10. Failure: The target\
      \ has the [Paralyzed](Інструменти%20ДМ/CLI/rules/conditions.md#Paralyzed) condition\
      \ until the end of its next turn."
    "name": "Claw"
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/undead/token/ghoul-xmm.webp"
```
^statblock

## Environment

swamp, underdark, urban