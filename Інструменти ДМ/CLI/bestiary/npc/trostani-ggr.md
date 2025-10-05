---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/18
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- Trostani
---
# [Trostani](Інструменти ДМ\CLI\bestiary\npc/trostani-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 252*  

The Selesnya guildmaster is an amalgamation of three dryads in body, will, and soul. Each dryad's body extends from a central trunk, so while they possess independent minds, they share a single name-Trostani and a single life force. Usually Trostani communicates the will of the Worldsoul with one voice, but she retains three distinct personalities that embody the three parts of the Selesnyan ideal: order, life, and harmony. In the midst of increasing tensions on Ravnica, the three personalities have recently been at odds over how best to navigate the conclave through such difficult times.

Trostani spends most of her time in the towering tree of Vitu-Ghazi, the Selesnya guildhall. There she communes with Mat'Selesnya and with the dryads who lead individual Selesnya communities across Ravnica.

```statblock
"name": "Trostani (GGR)"
"size": "Large"
"type": "fey"
"alignment": "Neutral Good"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "252"
"hit_dice": "24d10 + 120"
"modifier": !!int "2"
"stats":
  - !!int "19"
  - !!int "14"
  - !!int "20"
  - !!int "16"
  - !!int "30"
  - !!int "25"
"speed": "30 ft."
"saves":
  - "constitution": !!int "11"
  - "wisdom": !!int "16"
  - "charisma": !!int "13"
"skillsaves":
  - "name": "[Arcana](Інструменти%20ДМ/CLI/rules/skills.md#Arcana)"
    "desc": "+9"
  - "name": "[Insight](Інструменти%20ДМ/CLI/rules/skills.md#Insight)"
    "desc": "+16"
  - "name": "[Nature](Інструменти%20ДМ/CLI/rules/skills.md#Nature)"
    "desc": "+9"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+16"
  - "name": "[Persuasion](Інструменти%20ДМ/CLI/rules/skills.md#Persuasion)"
    "desc": "+13"
"condition_immunities": "[charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed),\
  \ [grappled](Інструменти%20ДМ/CLI/rules/conditions.md#Grappled)"
"senses": "darkvision 120 ft., passive Perception 26"
"languages": "Common, Druidic, Elvish, Sylvan"
"cr": "18"
"traits":
  - "desc": "Trostani's innate spellcasting ability is Wisdom (spell save DC 24).\
      \ She can innately cast the following spells, requiring no material components:\n\
      \nAt will: [dispel magic](Інструменти%20ДМ/CLI/spells/dispel-magic-xphb.md),\
      \ [druidcraft](Інструменти%20ДМ/CLI/spells/druidcraft-xphb.md)\n\n3/day each:\
      \ [bless](Інструменти%20ДМ/CLI/spells/bless-xphb.md), [conjure animals](Інст\
      рументи%20ДМ/CLI/spells/conjure-animals-xphb.md), [giant insect](Інструменти\
      %20ДМ/CLI/spells/giant-insect-xphb.md), [moonbeam](Інструменти%20ДМ/CLI/spells/moonbeam-xphb.md),\
      \ [plant growth](Інструменти%20ДМ/CLI/spells/plant-growth-xphb.md), [spike growth](І\
      нструменти%20ДМ/CLI/spells/spike-growth-xphb.md), [suggestion](Інструменти%20Д\
      М/CLI/spells/suggestion-xphb.md)\n\n1/day each: [conjure fey](Інструмент\
      и%20ДМ/CLI/spells/conjure-fey-xphb.md), [mass cure wounds](Інструменти%20ДМ\
      /CLI/spells/mass-cure-wounds-xphb.md)"
    "name": "Innate Spellcasting"
  - "desc": "If Trostani fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Trostani has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "Trostani's weapon attacks are magical."
    "name": "Magic Weapons"
  - "desc": "Trostani can communicate with beasts and plants as if they shared a language."
    "name": "Speak with Beasts and Plants"
  - "desc": "Once on her turn, Trostani can use 10 feet of her movement to step magically\
      \ into one living tree within her reach and emerge from a second living tree\
      \ within 60 feet of the first tree, appearing in an unoccupied space within\
      \ 5 feet of the second tree. Both trees must be Large or bigger."
    "name": "Tree Stride"
"actions":
  - "desc": "Trostani takes three actions: she uses Constrict and Touch of Order,\
      \ and she casts a spell with a casting time of 1 action."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: dice:1d20+11|noform|noparens|text(+11) to hit,\
      \ reach 5 ft., one creature. Hit: dice:3d6+5|noform|noparens|avg|text(15)\
      \ (3d6 + 5) bludgeoning damage, and the target is [grappled](Інструменти%20Д\
      М/CLI/rules/conditions.md#Grappled) (escape DC 19). Until this grapple ends,\
      \ the target is [restrained](Інструменти%20ДМ/CLI/rules/conditions.md#Restrained).\
      \ Trostani can grapple no more than three targets at a time."
    "name": "Constrict"
  - "desc": "Melee Spell Attack: dice:1d20+16|noform|noparens|text(+16) to hit,\
      \ reach 5 ft., one creature. Hit: dice:3d8+10|noform|noparens|avg|text(23)\
      \ (3d8 + 10) radiant damage, and Trostani can choose one magic item she can\
      \ see in the target's possession. Unless it's an artifact, the item's magic\
      \ is suppressed until the start of Trostani's next turn."
    "name": "Touch of Order"
  - "desc": "Trostani conjures a momentary whirl of branches and vines at a point\
      \ she can see within 60 feet of her. Each creature in a 30-foot cube on that\
      \ point must make a DC 24 Dexterity saving throw, taking dice:6d6|noform|noparens|avg|text(21)\
      \ (6d6) bludgeoning damage and dice:6d6|noform|noparens|avg|text(21) (6d6)\
      \ slashing damage on a failed save, or half as much damage on a successful one."
    "name": "Wrath of Mat'Selesnya (Recharge 5-6)"
"legendary_actions":
  - "desc": "Trostani makes one melee attack, with advantage on the attack roll."
    "name": "Voice of Harmony"
  - "desc": "Trostani bestows 20 temporary hit points on another creature she can\
      \ see within 120 feet of her."
    "name": "Voice of Life"
  - "desc": "Trostani casts [dispel magic](Інструменти%20ДМ/CLI/spells/dispel-magic-xphb.md)."
    "name": "Voice of Order"
  - "desc": "Trostani casts [suggestion](Інструменти%20ДМ/CLI/spells/suggestion-xphb.md).\
      \ This counts as one of her daily uses of the spell."
    "name": "Chorus of the Conclave (Costs 2 Actions)"
  - "desc": "Trostani animates one or two trees she can see within 120 feet of her,\
      \ causing them to uproot themselves and become awakened trees (see the Monster\
      \ Manual for their stat blocks) for 1 minute or until Trostani uses a bonus\
      \ action to end the effect. These trees understand Druidic and obey Trostani's\
      \ spoken commands, but can't speak. If she issues no commands to them, the trees\
      \ do nothing but follow her and take the Dodge action."
    "name": "Awaken Grove Guardians (Costs 3 Actions)"
"source":
  - "GGR"
"image": "Інструменти%20ДМ/CLI/bestiary/npc/token/trostani-ggr.webp"
```
^statblock