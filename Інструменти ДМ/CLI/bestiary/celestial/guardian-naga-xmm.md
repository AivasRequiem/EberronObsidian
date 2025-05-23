---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/environment/upper
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- Guardian Naga
---
# [Guardian Naga](Інструменти ДМ\CLI\bestiary\celestial/guardian-naga-xmm.md)
*Source: Monster Manual (2024) p. 161. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Guardian Naga

*Enduring Serpentine Lore Keeper*

- **Habitat.** Desert, Forest, Planar (Upper Planes)  
- **Treasure.** Relics  

Guardian nagas are immortal, serpentine scholars that possess perfect memories. They collect the histories and lore of those they live among, guarding cultures' stories and passing them on to new generations with infallible accuracy. Guardian nagas that outlive their host civilizations might linger in whatever ruins remain, preserving the civilizations' stories so their lost people might live on.

Roll on or choose a result from the Guardian Naga Lore table to inspire what a naga knows.

**Guardian Naga Lore**

`dice: [](guardian-naga-xmm.md#^guardian-naga-lore)`

| dice: 1d8 | The Guardian Naga Recalls... |
|-----------|------------------------------|
| 1 | The last words of an ancient sage or leader. |
| 2 | The location of a hidden city or continent. |
| 3 | A magic word, password, or riddle's answer. |
| 4 | The names of all who have told it stories. |
| 5 | An otherwise forgotten ritual or spell. |
| 6 | Recipes using regional ingredients. |
| 7 | Stories of forgotten gods and local spirits. |
| 8 | The vulnerabilities of a legendary monster. |
^guardian-naga-lore

```statblock
"name": "Guardian Naga (XMM)"
"size": "Large"
"type": "celestial"
"alignment": "Lawful Good"
"ac": !!int "18"
"hp": !!int "136"
"hit_dice": "16d10 + 48"
"modifier": !!int "4"
"stats":
  - !!int "19"
  - !!int "18"
  - !!int "16"
  - !!int "16"
  - !!int "19"
  - !!int "18"
"speed": "40 ft., climb 40 ft., swim 40 ft."
"saves":
  - "dexterity": "+8"
  - "constitution": "+7"
  - "intelligence": "+7"
  - "wisdom": "+8"
  - "charisma": "+8"
"skillsaves":
  - "name": "[Arcana](Інструменти%20ДМ/CLI/rules/skills.md#Arcana)"
    "desc": "+11"
  - "name": "[History](Інструменти%20ДМ/CLI/rules/skills.md#History)"
    "desc": "+11"
  - "name": "[Religion](Інструменти%20ДМ/CLI/rules/skills.md#Religion)"
    "desc": "+11"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed),\
  \ [paralyzed](Інструменти%20ДМ/CLI/rules/conditions.md#Paralyzed), [poisoned](Ін\
  струменти%20ДМ/CLI/rules/conditions.md#Poisoned), [restrained](Інструменти%20ДМ\
  /CLI/rules/conditions.md#Restrained)"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Celestial, Common"
"cr": "10"
"traits":
  - "desc": "If the naga dies, it returns to life in d6 days and regains all its\
      \ [Hit Points](Інструменти%20ДМ/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ unless [Dispel Evil and Good](Інструменти%20ДМ/CLI/spells/dispel-evil-and-good-xphb.md)\
      \ is cast on its remains."
    "name": "Celestial Restoration"
"actions":
  - "desc": "The naga makes two Bite attacks. It can replace any attack with a use\
      \ of Poisonous Spittle."
    "name": "Multiattack"
  - "desc": "Melee Attack Roll: +8, reach 10 ft. Hit: 17 (2d12 + 4) Piercing\
      \ damage plus 22 (4d10) Poison damage."
    "name": "Bite"
  - "desc": "Constitution Saving Throw: DC 16, one creature the naga can see within\
      \ 60 feet. Failure: 31 (7d8) Poison damage, and the target has the [Blinded](І\
      нструменти%20ДМ/CLI/rules/conditions.md#Blinded) condition until the start of\
      \ the naga's next turn. Success: Half damage only."
    "name": "Poisonous Spittle"
  - "desc": "The naga casts one of the following spells, requiring no Somatic or Material\
      \ components and using Wisdom as the spellcasting ability (spell save DC 16):\n\
      \nAt will: [Thaumaturgy](Інструменти%20ДМ/CLI/spells/thaumaturgy-xphb.md)\n\
      \n1/day each: [Clairvoyance](Інструменти%20ДМ/CLI/spells/clairvoyance-xphb.md),\
      \ [Cure Wounds](Інструменти%20ДМ/CLI/spells/cure-wounds-xphb.md) (level 6 version),\
      \ [Flame Strike](Інструменти%20ДМ/CLI/spells/flame-strike-xphb.md) (level 6\
      \ version), [Geas](Інструменти%20ДМ/CLI/spells/geas-xphb.md), [True Seeing](І\
      нструменти%20ДМ/CLI/spells/true-seeing-xphb.md)"
    "name": "Spellcasting"
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/celestial/token/guardian-naga-xmm.webp"
```
^statblock

## Environment

desert, forest, planar, upper