---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/19
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
statblock-link: "#^statblock"
aliases:
- Bael
---
# [Bael](Інструменти ДМ\CLI\bestiary\npc/bael-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 54*  

With the Blood War between devils and demons raging for eons and no end in sight, opportunities abound for ambitious archdevils to win fame, glory, and power in the ongoing struggle. Duke Bael, one of Mammon's most important vassals, has won fame and acclaim for his victories. Charged with leading sixty-six companies of [barbed devils](Інструменти%20ДМ/CLI/bestiary/fiend/barbed-devil-xmm.md), Bael has proven to be a tactical genius, earning esteem for himself and his master as a result of victory after victory over the abyssal host. Mammon relies on Bael to safeguard his holdings because of Bael's battle acumen. During a time when so many other archdevils have lost their positions, Mammon has never been ousted, which is a testament to Bael's skill on the battlefield.

For his accomplishments, Bael has been granted the title of Bronze General. His accolades notwithstanding, he has had a difficult time navigating the quagmire of infernal politics. His critics call him naive, though never to his face. His primary interest has always been leading soldiers in battle, so he finds it frustrating to have his ambitions of ascending to a higher rank constantly stymied by politically shrewd rivals.

Bael prefers to make servants out of his adversaries, and mortals bound to his service earn their wretched place by falling victim to his superior stratagems. Bael gladly spares the lives of those he defeats—if they pledge their souls and service to him. Demons are an exception; although he is willing to corrupt almost any other foes, he always destroys demons he defeats.

Bael also welcomes mortals into his service if they can provide him with an advantage in his politicking. He recruits savvy individuals and relies on them to represent his interests at Mammon's court, which leaves him free to pursue his battle lust.

Despite his lack of interest in affairs outside battle, or perhaps because of it, Bael has gained a small following of cultists. Those who worship at his altar call him the King of Hell, and the most deluded believe that he is the lord of all devils. In arcane circles, certain writings, such as the dreaded Book of Fire, say that Bael revealed the invisibility spell to the world, though some scholars of magic hotly refute such claims. Bael is sometimes depicted as a toad, a cat, a human, or some combination of these forms.

```statblock
"name": "Bael (MPMM)"
"size": "Large"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "[plate](Інструменти%20ДМ/CLI/items/plate-armor-xphb.md)"
"hp": !!int "189"
"hit_dice": "18d10 + 90"
"modifier": !!int "3"
"stats":
  - !!int "24"
  - !!int "17"
  - !!int "20"
  - !!int "21"
  - !!int "24"
  - !!int "24"
"speed": "30 ft."
"saves":
  - "dexterity": "+9"
  - "constitution": "+11"
  - "intelligence": "+11"
  - "charisma": "+13"
"skillsaves":
  - "name": "[Intimidation](Інструменти%20ДМ/CLI/rules/skills.md#Intimidation)"
    "desc": "+13"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+13"
  - "name": "[Persuasion](Інструменти%20ДМ/CLI/rules/skills.md#Persuasion)"
    "desc": "+13"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "[charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed),\
  \ [exhaustion](Інструменти%20ДМ/CLI/rules/conditions.md#Exhaustion), [frightened](І\
  нструменти%20ДМ/CLI/rules/conditions.md#Frightened), [poisoned](Інструменти%20ДМ\
  /CLI/rules/conditions.md#Poisoned)"
"senses": "truesight 120 ft., passive Perception 23"
"languages": "all, telepathy 120 ft."
"cr": "19"
"traits":
  - "desc": "Any creature, other than a devil, that starts its turn within 10 feet\
      \ of Bael must succeed on a DC 22 Wisdom saving throw or be [frightened](Інс\
      трументи%20ДМ/CLI/rules/conditions.md#Frightened) of him until the start of\
      \ its next turn. A creature succeeds on this saving throw automatically if Bael\
      \ wishes it or if he is [incapacitated](Інструменти%20ДМ/CLI/rules/conditions.md#Incapacitated)."
    "name": "Dread"
  - "desc": "If Bael fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Bael have advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "Bael regains 20 hit points at the start of his turn. If he takes cold\
      \ or radiant damage, this trait doesn't function at the start of his next turn.\
      \ Bael dies only if he starts his turn with 0 hit points and doesn't regenerate."
    "name": "Regeneration"
"actions":
  - "desc": "Bael makes two Hellish Morningstar attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +13 to hit, reach 20 ft., one target. Hit:\
      \ 16 (2d8 + 7) force damage plus 9 (2d8) necrotic damage."
    "name": "Hellish Morningstar"
  - "desc": "Each of Bael's allies within 60 feet of him can't be [charmed](Інстру\
      менти%20ДМ/CLI/rules/conditions.md#Charmed) or [frightened](Інструменти%20ДМ\
      /CLI/rules/conditions.md#Frightened) until the end of his next turn."
    "name": "Infernal Command"
  - "desc": "Bael teleports, along with any equipment he is wearing or carrying, up\
      \ to 120 feet to an unoccupied space he can see."
    "name": "Teleport"
  - "desc": "Bael casts one of the following spells, requiring no material components\
      \ and using Charisma as the spellcasting ability (spell save DC 21):\n\nAt\
      \ will: [alter self](Інструменти%20ДМ/CLI/spells/alter-self-xphb.md) (can\
      \ become Medium), [charm person](Інструменти%20ДМ/CLI/spells/charm-person-xphb.md),\
      \ [detect magic](Інструменти%20ДМ/CLI/spells/detect-magic-xphb.md), [invisibility](І\
      нструменти%20ДМ/CLI/spells/invisibility-xphb.md), [major image](Інструменти\
      %20ДМ/CLI/spells/major-image-xphb.md)\n\n3/day each: [dispel magic](Інст\
      рументи%20ДМ/CLI/spells/dispel-magic-xphb.md), [fly](Інструменти%20ДМ/CLI/spells/fly-xphb.md),\
      \ [suggestion](Інструменти%20ДМ/CLI/spells/suggestion-xphb.md), [wall of fire](І\
      нструменти%20ДМ/CLI/spells/wall-of-fire-xphb.md)\n\n1/day: [dominate monster](І\
      нструменти%20ДМ/CLI/spells/dominate-monster-xphb.md)"
    "name": "Spellcasting"
"legendary_actions":
  - "desc": "Bael uses Spellcasting or Teleport."
    "name": "Fiendish Magic"
  - "desc": "Bael uses Infernal Command."
    "name": "Infernal Command"
  - "desc": "Bael makes one Hellish Morningstar attack."
    "name": "Attack (Costs 2 Actions)"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/npc/token/bael-mpmm.webp"
```
^statblock