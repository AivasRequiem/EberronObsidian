---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
- Sire of Insanity
---
# [Sire of Insanity](Інструменти ДМ\CLI\bestiary\fiend/sire-of-insanity-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 197*  

Rakdos nightclubs, where visitors can indulge any dark desire and revel in sadistic spectacle, are the favored haunts of the demons known as sires of insanity. Lurking in an underground vault beneath a Rakdos operation, a sire of insanity feasts on the violence, torment, and depravity unfolding above. Occasionally, cultists bring would-be recruits to the demon's presence, and—true to its name—the sire of insanity breaks the new cultist's mind.

A sire of insanity is a bloated demon resembling a bipedal lizard. It stands some thirty feet tall and weighs many thousands of pounds, so it tends to keep hidden away in its subterranean lair, working its evil from the shadows.

## Demons

Just as angels are incarnations of the ideals of justice, demons embody depraved impulses: selfishness, cruelty, hatred, greed, and lust for power. Demons are strongly associated with the Cult of Rakdos; in fact, the demons of Ravnica might have been created by Rakdos in the same way that angels were created by the Boros Legion's founder. As a demon lord who has chosen to live in Ravnica, Rakdos claims authority over all the demons of this world-even if some of them, ambitious and headstrong as demons are, rebel against his authority.

Demons are agents of destruction that work their acts of terror in plain sight under the auspices of the Cult of Rakdos. They exhibit their cruelty in dramatic performances that leave the audience members blood-soaked but ecstatic. They incite mob riots that raze entire city blocks. The only thing demons fear is Rakdos himself, who doesn't tolerate rivals and hates to be upstaged.

### Demonic "Devils"

The creatures called "devils" in Ravnica are minor demons akin to [quasits](Інструменти%20ДМ/CLI/bestiary/fiend/quasit-xmm.md). While the larger demons embody evil qualities such as blood lust and torment, these lesser demons reflect the whimsical and chaotic side of Rakdos and his cult. Their mischievous antics cause disorder and destruction out of proportion to the demons' small size.

### Diabolic Demons

Many of the demons of Ravnica are monstrous, winged creatures of human-like form. They are best represented by the statistics of the [nalfeshnee](Інструменти%20ДМ/CLI/bestiary/fiend/nalfeshnee-xmm.md), the [shadow demon](Інструменти%20ДМ/CLI/bestiary/fiend/shadow-demon-xmm.md), or the [vrock](Інструменти%20ДМ/CLI/bestiary/fiend/vrock-xmm.md) in the Monster Manual. Demons associated with the Cult of Rakdos often have fiery attacks that make them similar to barbed devils or horned devils, except that they are demons. (They are chaotic evil, they speak Abyssal and not Infernal, and they lack Devil's Sight.)

```statblock
"name": "Sire of Insanity (GGR)"
"size": "Huge"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "157"
"hit_dice": "15d12 + 60"
"modifier": !!int "-2"
"stats":
  - !!int "23"
  - !!int "6"
  - !!int "19"
  - !!int "14"
  - !!int "19"
  - !!int "22"
"speed": "40 ft."
"saves":
  - "constitution": !!int "8"
  - "intelligence": !!int "6"
  - "wisdom": !!int "8"
  - "charisma": !!int "10"
"skillsaves":
  - "name": "[Deception](Інструменти%20ДМ/CLI/rules/skills.md#Deception)"
    "desc": "+10"
  - "name": "[Intimidation](Інструменти%20ДМ/CLI/rules/skills.md#Intimidation)"
    "desc": "+10"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned)"
"senses": "truesight 120 ft., passive Perception 14"
"languages": "Abyssal, Common, telepathy 120 ft."
"cr": "12"
"traits":
  - "desc": "The sire's innate spellcasting ability is Charisma (spell save DC 18,\
      \ dice:1d20+10|noform|noparens|text(+10) to hit with spell attacks). The sire\
      \ can innately cast the following spells, requiring no material components:\n\
      \nAt will: [clairvoyance](Інструменти%20ДМ/CLI/spells/clairvoyance-xphb.md),\
      \ [crown of madness](Інструменти%20ДМ/CLI/spells/crown-of-madness-xphb.md),\
      \ [major image](Інструменти%20ДМ/CLI/spells/major-image-xphb.md), [suggestion](І\
      нструменти%20ДМ/CLI/spells/suggestion-xphb.md)\n\n1/day each: [confusion](І\
      нструменти%20ДМ/CLI/spells/confusion-xphb.md), [mass suggestion](Інструменти\
      %20ДМ/CLI/spells/mass-suggestion-xphb.md)"
    "name": "Innate Spellcasting"
  - "desc": "Any creature that starts its turn within 30 feet of the sire must make\
      \ a DC 18 Wisdom saving throw. On a successful save, the creature is immune\
      \ to this aura for the next 24 hours. On a failed save, the creature has disadvantage\
      \ for 1 minute on Wisdom and Charisma checks and on Wisdom and Charisma saves.\
      \ At the start of each of its turns, the sire can suppress this aura until the\
      \ start of its next turn."
    "name": "Aura of Mind Erosion"
  - "desc": "The sire has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The sire makes two attacks: one with its bite and one with its claws."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: dice:1d20+10|noform|noparens|text(+10) to hit,\
      \ reach 5 ft., one creature. Hit: dice:3d12+6|noform|noparens|avg|text(25)\
      \ (3d12 + 6) piercing damage plus dice:3d10|noform|noparens|avg|text(16)\
      \ (3d10) psychic damage."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: dice:1d20+10|noform|noparens|text(+10) to hit,\
      \ reach 10 ft., one target. Hit: dice:1d8+6|noform|noparens|avg|text(10)\
      \ (1d8 + 6) slashing damage plus dice:2d8|noform|noparens|avg|text(9) (2d8)\
      \ psychic damage."
    "name": "Claws"
"source":
  - "GGR"
"image": "Інструменти%20ДМ/CLI/bestiary/fiend/token/sire-of-insanity-ggr.webp"
```
^statblock