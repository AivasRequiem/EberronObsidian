---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/17
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity/shapechanger
statblock: inline
statblock-link: "#^statblock"
aliases:
- Lazav
---
# [Lazav](Інструменти ДМ\CLI\bestiary\npc/lazav-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 232*  

Lazav is uniquely qualified to be the Dimir guildmaster: he is a shapechanger whose mysterious genius is informed by agents from the entire Dimir network. He takes on a tremendous variety of guises as his needs and plans require. He might step out into the Ravnican streets as an elderly widow to eavesdrop at the bazaar, become a vedalken hussar of the Azorius Senate to sidestep a checkpoint, or transform into a Tin Street merchant to deceive a passing noble. His true form might be that of a doppelganger or some other creature; no one has ever seen it.

```statblock
"name": "Lazav (GGR)"
"size": "Medium"
"type": "monstrosity"
"subtype": "shapechanger"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "204"
"hit_dice": "24d8 + 96"
"modifier": !!int "7"
"stats":
  - !!int "16"
  - !!int "24"
  - !!int "18"
  - !!int "22"
  - !!int "20"
  - !!int "22"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "13"
  - "intelligence": !!int "12"
  - "wisdom": !!int "11"
  - "charisma": !!int "12"
"skillsaves":
  - "name": "[Deception](Інструменти%20ДМ/CLI/rules/skills.md#Deception)"
    "desc": "+18"
  - "name": "[Insight](Інструменти%20ДМ/CLI/rules/skills.md#Insight)"
    "desc": "+11"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+11"
  - "name": "[Stealth](Інструменти%20ДМ/CLI/rules/skills.md#Stealth)"
    "desc": "+19"
"damage_resistances": "necrotic, psychic"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed),\
  \ [frightened](Інструменти%20ДМ/CLI/rules/conditions.md#Frightened), [poisoned](І\
  нструменти%20ДМ/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 21"
"languages": "Common, Thieves' cant"
"cr": "17"
"traits":
  - "desc": "Lazav's innate spellcasting ability is Intelligence (spell save DC 20).\
      \ He can innately cast the following spells, requiring no material components:\n\
      \nAt will: [detect thoughts](Інструменти%20ДМ/CLI/spells/detect-thoughts-xphb.md),\
      \ [encode thoughts](Інструменти%20ДМ/CLI/spells/encode-thoughts-ggr.md) (see\
      \ chapter 2), [freedom of movement](Інструменти%20ДМ/CLI/spells/freedom-of-movement-xphb.md),\
      \ [vicious mockery](Інструменти%20ДМ/CLI/spells/vicious-mockery-xphb.md) (dice:4d4|noform|noparens|avg\
      \ (4d4) psychic damage)\n\n3/day each: [blur](Інструменти%20ДМ/CLI/spells/blur-xphb.md),\
      \ [confusion](Інструменти%20ДМ/CLI/spells/confusion-xphb.md), [mirror image](І\
      нструменти%20ДМ/CLI/spells/mirror-image-xphb.md)\n\n1/day each: [modify\
      \ memory](Інструменти%20ДМ/CLI/spells/modify-memory-xphb.md), [Rary's telepathic\
      \ bond](Інструменти%20ДМ/CLI/spells/rarys-telepathic-bond-xphb.md)"
    "name": "Innate Spellcasting"
  - "desc": "No attack roll has advantage against Lazav unless he is [incapacitated](І\
      нструменти%20ДМ/CLI/rules/conditions.md#Incapacitated)."
    "name": "Elusive"
  - "desc": "If Lazav fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Lazav can use a bonus action to polymorph into a Small or Medium humanoid\
      \ he has seen. His statistics, other than his size, are the same in each form.\
      \ Any equipment he is wearing or carrying isn't transformed."
    "name": "Shapechanger Savant"
  - "desc": "Unless Lazav is [incapacitated](Інструменти%20ДМ/CLI/rules/conditions.md#Incapacitated),\
      \ he is immune to magic that allows other creatures to read his thoughts, determine\
      \ whether he is lying, know his alignment, or know his creature type. Creatures\
      \ can telepathically communicate with Lazav only if he allows it."
    "name": "Psychic Defenses"
"actions":
  - "desc": "Lazav makes three shortsword attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: dice:1d20+13|noform|noparens|text(+13) to hit,\
      \ reach 5 ft., one target. Hit: dice:1d6+7|noform|noparens|avg|text(10)\
      \ (1d6 + 7) piercing damage plus dice:3d6|noform|noparens|avg|text(10) (3d6)\
      \ psychic damage, and the target has disadvantage on the next attack roll it\
      \ makes before Lazav's next turn."
    "name": "Shortsword"
"legendary_actions":
  - "desc": "Lazav makes a weapon attack."
    "name": "Attack"
  - "desc": "Lazav casts one of his innate spells."
    "name": "Cast a Spell (Costs 2 Actions)"
  - "desc": "Lazav rapidly takes the form of several nightmarish creatures, lashing\
      \ out at all nearby. Each creature within 10 feet of Lazav must succeed on a\
      \ DC 21 Dexterity saving throw or take dice:4d8|noform|noparens|avg|text(18)\
      \ (4d8) damage of a type chosen by Lazav: acid, cold, fire, lightning, or\
      \ necrotic."
    "name": "Shifting Nightmare (Costs 3 Actions)"
"source":
  - "GGR"
"image": "Інструменти%20ДМ/CLI/bestiary/npc/token/lazav-ggr.webp"
```
^statblock