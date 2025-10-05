---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/environment/lower
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- Incubus
---
# [Incubus](Інструменти ДМ\CLI\bestiary\fiend/incubus-xmm.md)
*Source: Monster Manual (2024) p. 178. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Incubus

*Life-Leeching Dream Stalker*

- **Habitat.** Planar (Lower Planes)  
- **Treasure.** Any  

Incubi exploit the vulnerability of mortal dreams. Slipping into the homes of sleepers, incubi feed off dreams and replace them with terrifying nightmares. Incubi visit victims nightly until their prey expires. The incubi then hunt for new victims, preferring the loved ones of past targets.

Incubi can transform into succubi and vice versa, taking the forms they need to manipulate foes in dreams or in the flesh.

Those visited by an incubus have recurring nightmares. Roll on or choose a result from the Incubus Nightmares table to inspire these night terrors.

**Incubus Nightmares**

`dice: [](incubus-xmm.md#^incubus-nightmares)`

| dice: 1d8 | The Incubus's Victim Has Dreams Of... |
|-----------|---------------------------------------|
| 1 | An angry family member or authority figure. |
| 2 | Being chased through the wilderness. |
| 3 | Being devoured by animals or monsters. |
| 4 | [Falling](Інструменти%20ДМ/CLI/traps-hazards/falling-xphb.md), drowning, or suffocating. |
| 5 | A ruinous public embarrassment. |
| 6 | A shadowy intruder or monstrous silhouette. |
| 7 | A traumatic past event. |
| 8 | A visitor with an eerie or enigmatic message. |
^incubus-nightmares

```statblock
"name": "Incubus (XMM)"
"size": "Medium"
"type": "fiend"
"alignment": "Neutral Evil"
"ac": !!int "15"
"hp": !!int "66"
"hit_dice": "12d8 + 12"
"modifier": !!int "3"
"stats":
  - !!int "8"
  - !!int "17"
  - !!int "13"
  - !!int "15"
  - !!int "12"
  - !!int "20"
"speed": "30 ft., fly 60 ft."
"skillsaves":
  - "name": "[Deception](Інструменти%20ДМ/CLI/rules/skills.md#Deception)"
    "desc": "+9"
  - "name": "[Insight](Інструменти%20ДМ/CLI/rules/skills.md#Insight)"
    "desc": "+5"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Persuasion](Інструменти%20ДМ/CLI/rules/skills.md#Persuasion)"
    "desc": "+9"
  - "name": "[Stealth](Інструменти%20ДМ/CLI/rules/skills.md#Stealth)"
    "desc": "+7"
"damage_resistances": "cold, fire, poison, psychic"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Abyssal, Common, Infernal; telepathy 60 ft."
"cr": "4"
"traits":
  - "desc": "When the incubus finishes a [Long Rest](Інструменти%20ДМ/CLI/rules/variant-rules/long-rest-xphb.md),\
      \ it can shape-shift into a [Succubus](Інструменти%20ДМ/CLI/bestiary/fiend/succubus-xmm.md),\
      \ using that stat block instead of this one. Any equipment it's wearing or carrying\
      \ isn't transformed."
    "name": "Succubus Form"
"actions":
  - "desc": "The incubus makes two Restless Touch attacks."
    "name": "Multiattack"
  - "desc": "Melee Attack Roll: dice:1d20+7|noform|noparens|text(+7), reach 5\
      \ ft. Hit: dice:3d6+5|noform|noparens|avg|text(15) (3d6 + 5) Psychic damage,\
      \ and the target is cursed for 24 hours or until the incubus dies. Until the\
      \ curse ends, the target gains no benefit from finishing Short Rests."
    "name": "Restless Touch"
  - "desc": "The incubus casts one of the following spells, requiring no Material\
      \ components and using Charisma as the spellcasting ability (spell save DC 15):\n\
      \nAt will: [Disguise Self](Інструменти%20ДМ/CLI/spells/disguise-self-xphb.md),\
      \ [Etherealness](Інструменти%20ДМ/CLI/spells/etherealness-xphb.md)\n\n1/day\
      \ each: [Dream](Інструменти%20ДМ/CLI/spells/dream-xphb.md), [Hypnotic Pattern](І\
      нструменти%20ДМ/CLI/spells/hypnotic-pattern-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Wisdom Saving Throw: DC 15, one creature the incubus can see within\
      \ 60 feet. Failure: If the target has 20 [Hit Points](Інструменти%20ДМ/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ or fewer, it has the [Unconscious](Інструменти%20ДМ/CLI/rules/conditions.md#Unconscious)\
      \ condition for 1 hour, until it takes damage, or until a creature within 5\
      \ feet of it takes an action to wake it. Otherwise, the target takes dice:4d8|noform|noparens|avg|text(18)\
      \ (4d8) Psychic damage."
    "name": "Nightmare (Recharge 6)"
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/fiend/token/incubus-xmm.webp"
```
^statblock

## Environment

planar, lower, urban