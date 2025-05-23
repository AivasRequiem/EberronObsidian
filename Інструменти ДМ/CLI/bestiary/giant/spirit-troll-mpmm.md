---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/giant
statblock: inline
statblock-link: "#^statblock"
aliases:
- Spirit Troll
---
# [Spirit Troll](Інструменти ДМ\CLI\bestiary\giant/spirit-troll-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 247*  

A troll blasted with psychic energy can take a non physical form upon regenerating. The troll's psyche survives, but the body is as insubstantial as shadow. The troll might be unaware of the transition—the creature still moves and attacks with teeth and claws as ever—but now the troll strikes at victims' minds.

## Trolls

Trolls that are nearly obliterated but survive and regenerate from mere scraps of flesh can display bizarre features. Radically transformed trolls like the rot trolls, spirit trolls, and venom trolls that follow are especially likely to arise when trolls regenerate in the presence of magical emanations, planar energy, disease, or death on a vast scale, or if their bodies were damaged by elemental forces. These unusual forms can also be produced and shaped by the ritual magic of evil spellcasters or by trolls' own practices, as is the case for dire trolls.

### Vaprak the Destroyer

Although trolls are rarely devout and seldom ponder spiritual questions, some fear and venerate the entity known as Vaprak the Destroyer. Vaprak's true nature is something of a mystery, but Vaprak is always portrayed as a horrid, misshapen, greenish creature strongly resembling a troll. Vaprak is given to fits of mindless destruction and uncontrollably fears the plots and ambitions of other deities.

Vaprak's troll worshipers believe this god devours the souls of those who have been cooked or digested (slain by fire or acid). Otherwise, the god spits the soul back into the world to regenerate a new body.

```statblock
"name": "Spirit Troll (MPMM)"
"size": "Large"
"type": "giant"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "130"
"hit_dice": "20d10 + 20"
"modifier": !!int "3"
"stats":
  - !!int "1"
  - !!int "17"
  - !!int "13"
  - !!int "8"
  - !!int "9"
  - !!int "16"
"speed": "30 ft."
"skillsaves":
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+3"
"damage_resistances": "acid, cold, fire"
"damage_immunities": "bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[exhaustion](Інструменти%20ДМ/CLI/rules/conditions.md#Exhaustion),\
  \ [grappled](Інструменти%20ДМ/CLI/rules/conditions.md#Grappled), [paralyzed](Інс\
  трументи%20ДМ/CLI/rules/conditions.md#Paralyzed), [petrified](Інструменти%20ДМ/CLI/rules/conditions.md#Petrified),\
  \ [prone](Інструменти%20ДМ/CLI/rules/conditions.md#Prone), [restrained](Інструме\
  нти%20ДМ/CLI/rules/conditions.md#Restrained), [unconscious](Інструменти%20ДМ/CLI/rules/conditions.md#Unconscious)"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Giant"
"cr": "11"
"traits":
  - "desc": "The troll can move through other creatures and objects as if they were\
      \ difficult terrain. It takes 5 (d10) force damage if it ends its turn inside\
      \ an object."
    "name": "Incorporeal Movement"
  - "desc": "The troll regains 10 hit points at the start of each of its turns. If\
      \ the troll takes psychic or force damage, this trait doesn't function at the\
      \ start of the troll's next turn. The troll dies only if it starts its turn\
      \ with 0 hit points and doesn't regenerate."
    "name": "Regeneration"
"actions":
  - "desc": "The troll makes one Bite attack and two Claw attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. Hit:\
      \ 19 (3d10 + 3) psychic damage, and the target must succeed on a DC 15 Wisdom\
      \ saving throw or be [stunned](Інструменти%20ДМ/CLI/rules/conditions.md#Stunned)\
      \ for 1 minute. The [stunned](Інструменти%20ДМ/CLI/rules/conditions.md#Stunned)\
      \ target can repeat the saving throw at the end of each of its turns, ending\
      \ the effect on itself on a success."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. Hit:\
      \ 19 (3d10 + 3) psychic damage."
    "name": "Claws"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/giant/token/spirit-troll-mpmm.webp"
```
^statblock

## Environment

coastal, forest, swamp, underdark