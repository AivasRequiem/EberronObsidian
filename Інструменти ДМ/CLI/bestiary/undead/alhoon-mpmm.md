---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/mind-flayer
- ttrpg-cli/monster/type/undead/wizard
statblock: inline
statblock-link: "#^statblock"
aliases:
- Alhoon
---
# [Alhoon](Інструменти ДМ\CLI\bestiary\undead/alhoon-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 43*  

> [!quote] A quote from Mordenkainen  
> 
> There are many reasons to avoid the way of the lich. An impermanent solution is paradoxical. Take alhoons. They require souls to keep from shriveling. I fail to see the appeal.

Mind flayers that pursue arcane magic are exiled as deviants, and for them no everlasting communion with an elder brain is possible. The road to lichdom offers an alternative way to escape the permanency of death, but that path is long and fraught with barriers. Alhoons are mind flayers who have used a shortcut to attain a lichlike state.

Elder brains forbid mind flayers from pursuing magic power aside from psionics, but it isn't an interdiction they must often enforce. Illithids brook no masters but members of their own kind, so it isn't in their nature to bow to any god or otherworldly patron. However, wizardry remains a temptation. In the pages of a spellbook, an illithid sees a system to acquire authority. Through the writings of the wizard who penned it, the illithid perceives the workings of a highly intelligent mind. Most mind flayers who find a spellbook react with abhorrence or indifference, but for some, a spellbook is a gateway to a new way of thinking.

For a time, the study of such forbidden texts can be hidden from other illithids and even from an elder brain. Yet eventually, mind flayer arcanists determined to pursue wizardry must flee the colony for their own safety. Once they taste freedom from the colony, some prize their privacy, others seek to commune with similar minds, and still others seek to dominate a colony by elevating themselves to the position of leadership normally held by an elder brain. Regardless, all such arcanists face the same stark fact: when they die, they will not join the host of minds in the elder brain—deviant minds are never accepted as part of the collective. For them, death means oblivion.

Lichdom offers salvation and the prospect of being able to pursue knowledge indefinitely. Yet learning the secret of achieving lichdom requires an arcane spellcaster to be at the apex of power—a significant challenge for mind flayers, given the scarcity of available mentors and training.

Confronting this reality, a group of nine mind flayer arcanists used their arcane magic and psionics to weave a new truth. These nine called themselves the Alhoon, and those who follow in their footsteps are referred to by the same name.

## Collaborative Undeath

To become alhoons, mind flayer arcanists must cooperate in the creation of a periapt of mind trapping, a fist-sized container made of silver, emerald, and amethyst. The process requires at least three mind flayer arcanists and the sacrifice of an equal number of souls from living victims in a three-day-long ritual of spellcasting and psionic communion. Upon its completion, free-willed undeath is conferred on the mind flayers, turning them into alhoons.

Initially, an alhoon can be difficult to distinguish from a normal mind flayer. The most obvious difference is the lack of a mind flayer's ever-present mucus coating. Without that protection, an alhoon's skin becomes dry and cracked, and its eyes might appear shriveled and sunken. Both of these clues are easily missed by someone who hasn't seen a mind flayer. However, in short order, an alhoon's flesh withers away and its empty eye sockets gleam with cold pinpricks of light like those of other liches.

Unlike a true lich's phylactery, the periapt of mind trapping doesn't restore the alhoons to undeath if they are destroyed. Instead, a destroyed alhoon's mind is transferred to the periapt, where it remains in communion with any other trapped alhoon minds, as well as the souls of those sacrificed.

The undeath conferred by a periapt of mind trapping lasts only so long as the life of the living victim selected. Thus an alhoon who sacrificed a 200-year-old elf looks forward to a much longer existence than one that sacrificed a 35-year-old person. Alhoons can extend their existence by repeating the ritual with new victims, effectively resetting the clocks for themselves.

Destroying a periapt of mind trapping consigns those trapped within it to oblivion, and thus alhoons often work together to create elaborate protections for their periapt and their preferred ritual site. Sometimes a single alhoon is entrusted with the periapt of mind trapping, but this is a dangerous proposition. Anyone who holds the periapt gains advantage on attacks, saving throws, and checks against the alhoons associated with its creation, and those alhoons in turn suffer disadvantage on attacks, saving throws, and checks against the holder. In addition, the holder can telepathically communicate with any sacrificed soul trapped within, and alhoons within the periapt can speak telepathically with the holder. A creature carrying the periapt can't prevent communication from alhoons but can silence trapped souls.

```statblock
"name": "Alhoon (MPMM)"
"size": "Medium"
"type": "undead"
"subtype": "mind flayer, wizard"
"alignment": "Typically  Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "150"
"hit_dice": "20d8 + 60"
"modifier": !!int "1"
"stats":
  - !!int "11"
  - !!int "12"
  - !!int "16"
  - !!int "19"
  - !!int "17"
  - !!int "17"
"speed": "30 ft., fly 15 ft. (hover)"
"saves":
  - "constitution": "+7"
  - "intelligence": "+8"
  - "wisdom": "+7"
  - "charisma": "+7"
"skillsaves":
  - "name": "[Arcana](Інструменти%20ДМ/CLI/rules/skills.md#Arcana)"
    "desc": "+8"
  - "name": "[Deception](Інструменти%20ДМ/CLI/rules/skills.md#Deception)"
    "desc": "+7"
  - "name": "[History](Інструменти%20ДМ/CLI/rules/skills.md#History)"
    "desc": "+8"
  - "name": "[Insight](Інструменти%20ДМ/CLI/rules/skills.md#Insight)"
    "desc": "+7"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Stealth](Інструменти%20ДМ/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"damage_resistances": "cold, lightning, necrotic"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed),\
  \ [exhaustion](Інструменти%20ДМ/CLI/rules/conditions.md#Exhaustion), [frightened](І\
  нструменти%20ДМ/CLI/rules/conditions.md#Frightened), [paralyzed](Інструменти%20Д\
  М/CLI/rules/conditions.md#Paralyzed), [poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned)"
"senses": "truesight 120 ft., passive Perception 17"
"languages": "Deep Speech, Undercommon, telepathy 120 ft."
"cr": "10"
"traits":
  - "desc": "The alhoon has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "The alhoon has advantage on saving throws against any effect that turns\
      \ Undead."
    "name": "Turn Resistance"
"actions":
  - "desc": "The alhoon makes two Chilling Grasp or Arcane Bolt attacks."
    "name": "Multiattack"
  - "desc": "Melee Spell Attack: +8 to hit, reach 5 ft., one target. Hit: 14\
      \ (4d6) cold damage, and the alhoon regains 14 hit points."
    "name": "Chilling Grasp"
  - "desc": "Ranged Spell Attack: +8 to hit, range 120 ft., one target. Hit:\
      \ 28 (8d6) force damage."
    "name": "Arcane Bolt"
  - "desc": "The alhoon magically emits psychic energy in a 60-foot cone. Each creature\
      \ in that area must succeed on a DC 16 Intelligence saving throw or take 22\
      \ (4d8 + 4) psychic damage and be [stunned](Інструменти%20ДМ/CLI/rules/conditions.md#Stunned)\
      \ for 1 minute. A target can repeat the saving throw at the end of each of its\
      \ turns, ending the effect on itself on a success."
    "name": "Mind Blast (Recharge 5-6)"
  - "desc": "The alhoon casts one of the following spells, requiring no material components\
      \ and using Intelligence as the spellcasting ability (spell save DC 16):\n\n\
      At will: [dancing lights](Інструменти%20ДМ/CLI/spells/dancing-lights-xphb.md),\
      \ [detect magic](Інструменти%20ДМ/CLI/spells/detect-magic-xphb.md), [detect\
      \ thoughts](Інструменти%20ДМ/CLI/spells/detect-thoughts-xphb.md), [disguise\
      \ self](Інструменти%20ДМ/CLI/spells/disguise-self-xphb.md), [mage hand](Інст\
      рументи%20ДМ/CLI/spells/mage-hand-xphb.md), [prestidigitation](Інструменти%20Д\
      М/CLI/spells/prestidigitation-xphb.md)\n\n1/day each: [dominate monster](І\
      нструменти%20ДМ/CLI/spells/dominate-monster-xphb.md), [globe of invulnerability](І\
      нструменти%20ДМ/CLI/spells/globe-of-invulnerability-xphb.md), [invisibility](І\
      нструменти%20ДМ/CLI/spells/invisibility-xphb.md), [modify memory](Інструмент\
      и%20ДМ/CLI/spells/modify-memory-xphb.md), [plane shift](Інструменти%20ДМ/CLI/spells/plane-shift-xphb.md)\
      \ (self only), [wall of force](Інструменти%20ДМ/CLI/spells/wall-of-force-xphb.md)"
    "name": "Spellcasting"
"reactions":
  - "desc": "The alhoon targets one creature it can see within 60 feet of it that\
      \ is casting a spell. If the spell is 3rd level or lower, the spell fails, but\
      \ any spell slots or charges are not wasted."
    "name": "Negate Spell (3/Day)"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/undead/token/alhoon-mpmm.webp"
```
^statblock

## Environment

underdark