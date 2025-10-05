---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/16
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- Iron Golem
---
# [Iron Golem](Інструменти ДМ\CLI\bestiary\construct/iron-golem-xmm.md)
*Source: Monster Manual (2024) p. 181. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Iron Golem

*Guardian of That Which Must Endure*

- **Habitat.** Any  
- **Treasure.** Any  

Their magical cores protected by mighty armor, iron golems defend important sites and objects. These golems are forged in bipedal forms, the details of which are decided by their creators. Many resemble armored guardians or legendary heroes. Iron golems confront their foes with a combination of overwhelming physical force and eruptions from their magical core. These magical blasts take the form of fiery bolts and poisonous emissions.

Iron golems preserve and protect their charges for generations. Roll on or choose a result from the Iron Golem Orders table to inspire what commands an iron golem follows.

**Iron Golem Orders**

`dice: [](iron-golem-xmm.md#^iron-golem-orders)`

| dice: 1d4 | The Iron Golem Follows Orders To... |
|-----------|-------------------------------------|
| 1 | Block a door that has never been opened, moving only when a prophecy is fulfilled. |
| 2 | Exhale poison gas whenever it can, pausing only when someone speaks a passphrase. |
| 3 | Pose as a statue until a community's hour of greatest need. |
| 4 | Stand atop the resting place of a powerful magic item. |
^iron-golem-orders

```statblock
"name": "Iron Golem (XMM)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "20"
"hp": !!int "252"
"hit_dice": "24d10 + 120"
"modifier": !!int "9"
"stats":
  - !!int "24"
  - !!int "9"
  - !!int "20"
  - !!int "3"
  - !!int "11"
  - !!int "1"
"speed": "30 ft."
"damage_immunities": "fire, poison, psychic"
"condition_immunities": "[charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed),\
  \ [exhaustion](Інструменти%20ДМ/CLI/rules/conditions.md#Exhaustion), [frightened](І\
  нструменти%20ДМ/CLI/rules/conditions.md#Frightened), [paralyzed](Інструменти%20Д\
  М/CLI/rules/conditions.md#Paralyzed), [petrified](Інструменти%20ДМ/CLI/rules/conditions.md#Petrified),\
  \ [poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "understands Common plus two other languages but can't speak"
"cr": "16"
"traits":
  - "desc": "Whenever the golem is subjected to Fire damage, it regains a number of\
      \ [Hit Points](Інструменти%20ДМ/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ equal to the Fire damage dealt."
    "name": "Fire Absorption"
  - "desc": "The golem can't shape-shift."
    "name": "Immutable Form"
  - "desc": "The golem has [Advantage](Інструменти%20ДМ/CLI/rules/variant-rules/advantage-xphb.md)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The golem makes two attacks, using Bladed Arm or Fiery Bolt in any combination."
    "name": "Multiattack"
  - "desc": "Melee Attack Roll: dice:1d20+12|noform|noparens|text(+12), reach\
      \ 10 ft. Hit: dice:3d8+7|noform|noparens|avg|text(20) (3d8 + 7) Slashing\
      \ damage plus dice:3d6|noform|noparens|avg|text(10) (3d6) Fire damage."
    "name": "Bladed Arm"
  - "desc": "Ranged Attack Roll: dice:1d20+10|noform|noparens|text(+10), range\
      \ 120 ft. Hit: dice:8d8|noform|noparens|avg|text(36) (8d8) Fire damage."
    "name": "Fiery Bolt"
  - "desc": "Constitution Saving Throw: DC 18, each creature in a 60-foot [Cone](І\
      нструменти%20ДМ/CLI/rules/variant-rules/cone-area-of-effect-xphb.md). Failure:\
      \ dice:10d10|noform|noparens|avg|text(55) (10d10) Poison damage. Success:\
      \ Half damage."
    "name": "Poison Breath (Recharge 6)"
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/construct/token/iron-golem-xmm.webp"
```
^statblock

## Environment

any