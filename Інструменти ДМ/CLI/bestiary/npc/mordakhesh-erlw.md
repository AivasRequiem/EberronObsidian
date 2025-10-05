---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/erlw
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- Mordakhesh
---
# [Mordakhesh](Інструменти ДМ\CLI\bestiary\npc/mordakhesh-erlw.md)
*Source: Eberron: Rising from the Last War p. 301*  

In the age when fiends and dragons waged war across Eberron, rakshasas served the fiendish lords as strategists and generals. A rakshasa named Mordakhesh rose up through the ranks to become one of the greatest commanders of his age, and a dragon-slaying specialist. For this, he earned the nickname Shadowsword, along with a legendary reputation for leaving death in his wake.

Mordakhesh serves as the prakhutu or "speaker" of his imprisoned master, Rak Tulkhesh, and he seeks to free his lord by bathing the world in blood. Like a spider with multiple webs, he has agents and pawns (which he calls his "claws") established in armies across Khorvaire. The most significant of those is the barbarian horde he amasses in the Demon Wastes—warriors who threaten to sweep into Aundair on a tide of blood.

Many of the horrors of the Last War were instigated—or at least encouraged—by Mordakhesh's operatives, and his claws are known to have perpetrated some of the most brutal massacres of that conflict. No one knows how far the Shadowsword's reach extends, or which commanders in the armies of Khorvaire serve him.

```statblock
"name": "Mordakhesh (ERLW)"
"size": "Medium"
"type": "fiend"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "[plate armor](Інструменти%20ДМ/CLI/items/plate-armor-xphb.md)"
"hp": !!int "170"
"hit_dice": "20d8 + 80"
"modifier": !!int "3"
"stats":
  - !!int "20"
  - !!int "16"
  - !!int "18"
  - !!int "15"
  - !!int "17"
  - !!int "20"
"speed": "40 ft."
"saves":
  - "strength": !!int "10"
  - "constitution": !!int "9"
  - "wisdom": !!int "8"
  - "charisma": !!int "10"
"skillsaves":
  - "name": "[Athletics](Інструменти%20ДМ/CLI/rules/skills.md#Athletics)"
    "desc": "+10"
  - "name": "[Insight](Інструменти%20ДМ/CLI/rules/skills.md#Insight)"
    "desc": "+8"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+8"
  - "name": "[Persuasion](Інструменти%20ДМ/CLI/rules/skills.md#Persuasion)"
    "desc": "+10"
"damage_vulnerabilities": "piercing from magic weapons wielded by good creatures"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks that\
  \ aren't silvered"
"senses": "darkvision 60 ft., passive Perception 18"
"languages": "Common, Infernal"
"cr": "15"
"traits":
  - "desc": "Mordakhesh's spellcasting ability is Charisma (spell save DC 18, +10\
      \ to hit with spell attacks). Mordakhesh can innately cast the following spells,\
      \ requiring no material components:\n\nAt will: [chromatic orb](Інструме\
      нти%20ДМ/CLI/spells/chromatic-orb-xphb.md) (see \"Actions\" below), [detect\
      \ thoughts](Інструменти%20ДМ/CLI/spells/detect-thoughts-xphb.md), [disguise\
      \ self](Інструменти%20ДМ/CLI/spells/disguise-self-xphb.md)\n\n1/day each:\
      \ [banishing smite](Інструменти%20ДМ/CLI/spells/banishing-smite-xphb.md), [destructive\
      \ wave](Інструменти%20ДМ/CLI/spells/destructive-wave-xphb.md), [fly](Інструм\
      енти%20ДМ/CLI/spells/fly-xphb.md), [mass suggestion](Інструменти%20ДМ/CLI/spells/mass-suggestion-xphb.md),\
      \ [staggering smite](Інструменти%20ДМ/CLI/spells/staggering-smite-xphb.md),\
      \ [suggestion](Інструменти%20ДМ/CLI/spells/suggestion-xphb.md), [true seeing](І\
      нструменти%20ДМ/CLI/spells/true-seeing-xphb.md)"
    "name": "Innate Spellcasting"
  - "desc": "Mordakhesh can't be affected or detected by spells of 6th level or lower\
      \ unless he wishes to be. Mordakhesh has advantage on saving throws against\
      \ all other spells and magical effects."
    "name": "Limited Magic Immunity"
"actions":
  - "desc": "Mordakhesh makes three greatsword attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit:\
      \ 12 (2d6 + 5) slashing damage plus 5 (d10) force damage."
    "name": "Greatsword"
  - "desc": "Ranged Spell Attack: +10 to hit, range 120 ft., one creature. Hit:\
      \ 13 (3d8) damage of a type chosen by Mordakhesh: acid, cold, fire, lightning,\
      \ poison, or thunder."
    "name": "Chromatic Orb"
"legendary_actions":
  - "desc": "Mordakhesh makes one weapon attack or casts [chromatic orb](Інструмен\
      ти%20ДМ/CLI/spells/chromatic-orb-xphb.md)."
    "name": "Attack"
  - "desc": "Modakhesh gains resistance to one damage type of his choice—acid, cold,\
      \ fire, lightning, poison, or thunder—until the start of his next turn."
    "name": "Chromatic Resistance"
  - "desc": "Mordakhesh targets up to two allies that he can see within 30 feet of\
      \ him. If a target can see and hear him, the target can make one weapon attack\
      \ as a reaction and gains advantage on the attack roll."
    "name": "Warlord's Command (Costs 2 Actions)"
"source":
  - "ERLW"
"image": "Інструменти%20ДМ/CLI/bestiary/npc/token/mordakhesh-erlw.webp"
```
^statblock