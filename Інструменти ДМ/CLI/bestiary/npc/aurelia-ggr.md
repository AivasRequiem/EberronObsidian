---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/23
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/celestial/angel
statblock: inline
statblock-link: "#^statblock"
aliases:
- Aurelia
---
# [Aurelia](Інструменти ДМ\CLI\bestiary\npc/aurelia-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 230*  

The angel Aurelia leads the Boros Legion. During the years of her leadership, she has shown a strong appreciation for the ordinary citizens who are often caught in the middle of interguild violence.

True justice, Aurelia argues, isn't merely the enforcement of the letter of existing laws (let the Azorius fret over that), but the establishment of equitable and compassionate relationships among all of Ravnica's people. That means protecting the weak from the depredations of the strong, sheltering the innocents who are threatened by war, and ensuring that enforcement of the law doesn't become oppressive. Aurelia actively supports efforts to establish a lasting peace among the guilds in the absence of the Guildpact.

Aurelia prefers to lead the Boros Legion from the front. She brings swift and unrelenting punishment to the wicked, and her temper is legendary.

## Immortal Nature

Aurelia doesn't require food, drink, or sleep.

```statblock
"name": "Aurelia (GGR)"
"size": "Medium"
"type": "celestial"
"subtype": "angel"
"alignment": "Lawful Good"
"ac": !!int "22"
"ac_class": "natural armor"
"hp": !!int "287"
"hit_dice": "25d8 + 175"
"modifier": !!int "7"
"stats":
  - !!int "26"
  - !!int "24"
  - !!int "25"
  - !!int "17"
  - !!int "25"
  - !!int "30"
"speed": "50 ft., fly 150 ft."
"saves":
  - "dexterity": !!int "14"
  - "constitution": !!int "14"
  - "charisma": !!int "17"
"skillsaves":
  - "name": "[Insight](Інструменти%20ДМ/CLI/rules/skills.md#Insight)"
    "desc": "+14"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+14"
"damage_resistances": "necrotic; radiant; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed),\
  \ [exhaustion](Інструменти%20ДМ/CLI/rules/conditions.md#Exhaustion), [frightened](І\
  нструменти%20ДМ/CLI/rules/conditions.md#Frightened), [paralyzed](Інструменти%20Д\
  М/CLI/rules/conditions.md#Paralyzed), [poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned)"
"senses": "truesight 120 ft., passive Perception 24"
"languages": "all"
"cr": "23"
"traits":
  - "desc": "If Aurelia fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Aurelia has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Aurelia makes three longsword attacks and uses Leadership."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: dice:1d20+15|noform|noparens|text(+15) to hit,\
      \ reach 5 ft., one target. Hit: dice:1d8+8|noform|noparens|avg|text(12)\
      \ (1d8 + 8) slashing damage, or dice:1d10+8|noform|noparens|avg|text(13)\
      \ (1d10 + 8) slashing damage when used with two hands, plus dice:6d8|noform|noparens|avg|text(27)\
      \ (6d8) radiant damage."
    "name": "Longsword"
  - "desc": "Aurelia utters a few inspiring words to one creature she can see within\
      \ 30 feet of her. If the creature can hear her, it can add a dice:d10|noform|noparens|avg\
      \ (d10) to one attack roll or saving throw it makes before the start of Aurelia's\
      \ next turn."
    "name": "Leadership"
  - "desc": "Ranged Spell Attack: dice:1d20+17|noform|noparens|text(+17) to hit,\
      \ range 60 ft., one creature. Hit: dice:12d8|noform|noparens|avg|text(54)\
      \ (12d8) radiant damage, and Aurelia can choose another creature she can see\
      \ within 10 feet of the target. The second creature regains dice:6d8|noform|noparens|avg|text(27)\
      \ (6d8) hit points."
    "name": "Warleader's Helix (Recharge 5-6)"
"reactions":
  - "desc": "Aurelia adds 7 to her AC against one melee attack that would hit her.\
      \ To do so, Aurelia must see the attacker and be wielding a melee weapon."
    "name": "Parry"
  - "desc": "When Aurelia is subjected to an effect that would move her, knock her\
      \ [prone](Інструменти%20ДМ/CLI/rules/conditions.md#Prone), or both, she can\
      \ use her reaction to be neither moved nor knocked [prone](Інструменти%20ДМ\
      /CLI/rules/conditions.md#Prone)."
    "name": "Unyielding"
"legendary_actions":
  - "desc": "Aurelia chooses up to three creatures she can see within 30 feet of her.\
      \ If a chosen creature can see or hear Aurelia, it can immediately use its reaction\
      \ to make one weapon attack, with advantage on the attack roll."
    "name": "Command Allies"
  - "desc": "Aurelia makes one longsword attack."
    "name": "Longsword Attack (Costs 2 Actions)"
  - "desc": "Aurelia targets up to five creatures she can see within 30 feet of her.\
      \ Each target must succeed on a DC 25 Wisdom saving throw or be [frightened](І\
      нструменти%20ДМ/CLI/rules/conditions.md#Frightened) of her until the end of\
      \ her next turn. Any target within 5 feet of Aurelia has disadvantage on the\
      \ saving throw."
    "name": "Frighten Foes (Costs 3 Actions)"
"source":
  - "GGR"
"image": "Інструменти%20ДМ/CLI/bestiary/npc/token/aurelia-ggr.webp"
```
^statblock