---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/erlw
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- Bone Knight
---
# [Bone Knight](Інструменти ДМ\CLI\bestiary\humanoid/bone-knight-erlw.md)
*Source: Eberron: Rising from the Last War p. 316*  

Bone knights are the champions of the Order of the Emerald Claw. Clad in distinctive bonecraft armor—heavy armor adorned with the bones of fallen enemies—these fearsome warriors command squads of undead soldiers as they pursue the sinister goals of Lady Illmarrow.

## Karrnathi Patriots

Early in the Last War, Karrnath turned to the necromancers of the Blood of Vol to bolster the nation's army with undead forces. The skeletons and zombies created by the necromancers were mindless creatures that required guidance. The first bone knights were appointed to provide this control.

Devoted paladins of the Blood of Vol were fused into suits of bonecraft armor, whose magic focused their divine gifts, allowing them to command units of mindless undead. Bonecraft armor can't be removed without killing the knight who wears it, and when donning it, each bone knight understood that their former life was over.

## The Fall of the Emerald Claw

During the Last War, many bone knights took service with the Order of the Emerald Claw, helping that name strike fear into the enemies of Karrnath. In the last decade, King Kaius III of Karrnath has done much to ensure a peaceful end to the Last War. Under the terms of the Treaty of Thronehold, Kaius sealed most of Karrnath's undead in deep vaults, and the Order of the Emerald Claw was disbanded. A few bone knights remained in service to the crown, but most were cast aside—still bound to their bonecraft armor and still convinced of Karrnathi supremacy. These bone knights felt that Kaius had betrayed both them and their nation, leading their once-proud order to find a new purpose in the service of Lady Illmarrow.

```statblock
"name": "Bone Knight (ERLW)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any Non-Good alignment"
"ac": !!int "20"
"ac_class": "bonecraft armor"
"hp": !!int "84"
"hit_dice": "13d8 + 26"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "13"
  - !!int "14"
  - !!int "12"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "5"
  - "charisma": !!int "6"
"skillsaves":
  - "name": "[Athletics](Інструменти%20ДМ/CLI/rules/skills.md#Athletics)"
    "desc": "+7"
  - "name": "[Deception](Інструменти%20ДМ/CLI/rules/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Intimidation](Інструменти%20ДМ/CLI/rules/skills.md#Intimidation)"
    "desc": "+6"
"damage_resistances": "necrotic, poison"
"senses": "passive Perception 12"
"languages": "any one language (usually Common)"
"cr": "5"
"traits":
  - "desc": "The knight is an 8th-level spellcaster. Its spellcasting ability is Charisma\
      \ (spell save DC 14, dice:1d20+6|noform|noparens|text(+6) to hit with spell\
      \ attacks). It has the following paladin spells prepared:\n\n1st level (4\
      \ slots): [command](Інструменти%20ДМ/CLI/spells/command-xphb.md), [compelled\
      \ duel](Інструменти%20ДМ/CLI/spells/compelled-duel-xphb.md), [hellish rebuke](І\
      нструменти%20ДМ/CLI/spells/hellish-rebuke-xphb.md), [wrathful smite](Інструм\
      енти%20ДМ/CLI/spells/wrathful-smite-xphb.md)\n\n2nd level (3 slots): [branding\
      \ smite](Інструменти%20ДМ/CLI/spells/shining-smite-xphb.md), [crown of madness](І\
      нструменти%20ДМ/CLI/spells/crown-of-madness-xphb.md), [darkness](Інструменти\
      %20ДМ/CLI/spells/darkness-xphb.md), [find steed](Інструменти%20ДМ/CLI/spells/find-steed-xphb.md),\
      \ [magic weapon](Інструменти%20ДМ/CLI/spells/magic-weapon-xphb.md)"
    "name": "Spellcasting"
  - "desc": "As a bonus action, the knight can target one skeleton or zombie it can\
      \ see within 30 feet of it. The target must make a DC 14 Wisdom saving throw.\
      \ On a failed save, the target must obey the knight's commands until the knight\
      \ dies or until the knight releases it as a bonus action. The knight can command\
      \ up to twelve undead at a time this way."
    "name": "Commander of Bones"
  - "desc": "While within 60 feet of the knight, any undead ally of the knight has\
      \ advantage on saving throws against any effect that turns undead."
    "name": "Master of the Pallid Banner"
"actions":
  - "desc": "The knight attacks twice with one of its weapons."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: dice:1d20+7|noform|noparens|text(+7) to hit,\
      \ reach 5 ft., one target. Hit: dice:2d6+4|noform|noparens|avg|text(11)\
      \ (2d6 + 4) slashing damage."
    "name": "Greatsword"
  - "desc": "Ranged Weapon Attack: dice:1d20+4|noform|noparens|text(+4) to hit,\
      \ range 150/600 ft., one target. Hit: dice:1d8+1|noform|noparens|avg|text(5)\
      \ (1d8 + 1) piercing damage."
    "name": "Longbow"
"source":
  - "ERLW"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/bone-knight-erlw.webp"
```
^statblock