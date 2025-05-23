---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/yugoloth
statblock: inline
statblock-link: "#^statblock"
aliases:
- Hydroloth
---
# [Hydroloth](Інструменти ДМ\CLI\bestiary\fiend/hydroloth-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 158*  

Like the thought-stealing waters of the River Styx they inhabit, hydroloths filch the memories of creatures they attack, stealing away thoughts for delivery to whatever master they happen to serve. Hydroloths also savor finding lost things, especially those that have been swallowed up in the deeps.

For amphibious assaults or underwater conflicts, hydroloths have no equal among yugoloths. They sometimes hire themselves out to attack and scuttle ships and raid coastal settlements.

```statblock
"name": "Hydroloth (MPMM)"
"size": "Medium"
"type": "fiend"
"subtype": "yugoloth"
"alignment": "Typically  Neutral Evil"
"ac": !!int "15"
"hp": !!int "135"
"hit_dice": "18d8 + 54"
"modifier": !!int "5"
"stats":
  - !!int "12"
  - !!int "21"
  - !!int "16"
  - !!int "19"
  - !!int "10"
  - !!int "14"
"speed": "20 ft., swim 40 ft."
"skillsaves":
  - "name": "[Insight](Інструменти%20ДМ/CLI/rules/skills.md#Insight)"
    "desc": "+4"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+4"
"damage_vulnerabilities": "fire"
"damage_resistances": "cold; lightning; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "acid, poison"
"condition_immunities": "[poisoned](Інструменти%20ДМ/CLI/rules/conditions.md#Poisoned)"
"senses": "blindsight 60 ft., darkvision 60 ft., passive Perception 14"
"languages": "Abyssal, Infernal, telepathy 60 ft."
"cr": "9"
"traits":
  - "desc": "The hydroloth can breathe air and water."
    "name": "Amphibious"
  - "desc": "The hydroloth has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "The hydroloth is immune to the waters of the River Styx, as well as any\
      \ effect that would steal or modify its memories or detect or read its thoughts."
    "name": "Secure Memory"
  - "desc": "While submerged in liquid, the hydroloth has advantage on attack rolls."
    "name": "Watery Advantage"
"actions":
  - "desc": "The hydroloth makes two Bite or Claw attacks. It can replace one attack\
      \ with a use of Spellcasting."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 16\
      \ (2d10 + 5) force damage plus 9 (2d10) psychic damage."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target.  Hit:\
      \ 14 (2d8 + 5) force damage plus 9 (2d10) psychic damage."
    "name": "Claw"
  - "desc": "The hydroloth targets one creature it can see within 60 feet of it. The\
      \ target takes 14 (4d6) psychic damage, and it must make a DC 16 Intelligence\
      \ saving throw. On a successful save, the target becomes immune to this hydroloth's\
      \ Steal Memory for 24 hours. On a failed save, the target loses all proficiencies;\
      \ it can't cast spells; it can't understand language; and if its Intelligence\
      \ and Charisma scores are higher than 5, they become 5. Each time the target\
      \ finishes a long rest, it can repeat the saving throw, ending the effect on\
      \ itself on a success. A [greater restoration](Інструменти%20ДМ/CLI/spells/greater-restoration-xphb.md)\
      \ or [remove curse](Інструменти%20ДМ/CLI/spells/remove-curse-xphb.md) spell\
      \ cast on the target ends this effect early."
    "name": "Steal Memory (1/Day)"
  - "desc": "The hydroloth teleports, along with any equipment it is wearing or carrying,\
      \ up to 60 feet to an unoccupied space it can see."
    "name": "Teleport"
  - "desc": "The hydroloth casts one of the following spells, requiring no material\
      \ components and using Intelligence as the spellcasting ability (spell save\
      \ DC 16):\n\nAt will: [darkness](Інструменти%20ДМ/CLI/spells/darkness-xphb.md),\
      \ [detect magic](Інструменти%20ДМ/CLI/spells/detect-magic-xphb.md), [dispel\
      \ magic](Інструменти%20ДМ/CLI/spells/dispel-magic-xphb.md), [invisibility](І\
      нструменти%20ДМ/CLI/spells/invisibility-xphb.md) (self only)\n\n3/day each:\
      \ [control water](Інструменти%20ДМ/CLI/spells/control-water-xphb.md), [crown\
      \ of madness](Інструменти%20ДМ/CLI/spells/crown-of-madness-xphb.md), [fear](І\
      нструменти%20ДМ/CLI/spells/fear-xphb.md), [suggestion](Інструменти%20ДМ/CLI/spells/suggestion-xphb.md)"
    "name": "Spellcasting"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/fiend/token/hydroloth-mpmm.webp"
```
^statblock