---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Kobold Inventor
---
# [Kobold Inventor](Інструменти ДМ\CLI\bestiary\humanoid/kobold-inventor-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 164*  

A kobold inventor builds improvised weapons to gain an advantage in combat. These weapons last for only one or two attacks before they break and typically work only for the inventor, but they might be surprisingly effective in the meantime. The weapons don't have to be lethal—often one serves its purpose if it distracts, scares, or confuses a creature long enough for the inventor to kill that foe.

```statblock
"name": "Kobold Inventor (MPMM)"
"size": "Small"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "12"
"hp": !!int "13"
"hit_dice": "3d6 + 3"
"modifier": !!int "2"
"stats":
  - !!int "7"
  - !!int "15"
  - !!int "12"
  - !!int "14"
  - !!int "10"
  - !!int "8"
"speed": "30 ft."
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Draconic"
"cr": "1/4"
"traits":
  - "desc": "The kobold has advantage on an attack roll against a creature if at least\
      \ one of the kobold's allies is within 5 feet of the creature and the ally isn't\
      \ [incapacitated](Інструменти%20ДМ/CLI/rules/conditions.md#Incapacitated)."
    "name": "Pack Tactics"
  - "desc": "While in sunlight, the kobold has disadvantage on attack rolls, as well\
      \ as on Wisdom ([Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception))\
      \ checks that rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "Melee  or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. Hit: 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
  - "desc": "Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. Hit:\
      \ 4 (1d4 + 2) bludgeoning damage."
    "name": "Sling"
  - "desc": "The kobold uses one of the following options (choose one or roll a d8);\
      \ the kobold can use each one no more than once per day:\n\n- 1 Acid. The\
      \ kobold hurls a [flask of acid](Інструменти%20ДМ/CLI/items/acid-xphb.md). Ranged\
      \ Weapon Attack: +4 to hit, range 5/20 ft., one target. Hit: 7 (2d6)\
      \ acid damage.  \n- 2 Alchemist's Fire. The kobold throws a [flask of alchemist's\
      \ fire](Інструменти%20ДМ/CLI/items/alchemists-fire-xphb.md). Ranged Weapon\
      \ Attack: +4 to hit, range 5/20 ft., one target. Hit: 2 (d4) fire damage\
      \ at the start of each of the target's turns. The target can end this damage\
      \ by using its action to make a DC 10 Dexterity check to extinguish the flames.\
      \  \n- 3 Basket of Centipedes. The kobold throws a small basket into a 5-foot-square\
      \ space within 20 feet of it. A [swarm of insects (centipedes)](Інструменти\
      %20ДМ/CLI/bestiary/beast/swarm-of-insects-xmm.md) with 11 hit points emerges\
      \ from the basket and rolls initiative. At the end of each of the swarm's turns,\
      \ there's a 50 percent chance that the swarm disperses.  \n- 4 Green Slime\
      \ Pot. The kobold throws a clay pot full of green slime at the target, and\
      \ it breaks open on impact. Ranged Weapon Attack: +4 to hit, range 5/20\
      \ ft., one target. Hit: 5 (d10) acid damage, and the target is covered in\
      \ slime until a creature uses its action to scrape or wash the slime off. A\
      \ target covered in the slime takes 5 (d10) acid damage at the start of each\
      \ of its turns.  \n- 5 Rot Grub Pot. The kobold throws a clay pot into a\
      \ 5-foot-square space within 20 feet of it, and it breaks open on impact. A\
      \ [swarm of rot grubs](Інструменти%20ДМ/CLI/bestiary/beast/swarm-of-rot-grubs-mpmm.md)\
      \ (in this book) emerges from the shattered pot and remains a hazard in that\
      \ square.  \n- 6 Scorpion on a Stick. The kobold makes a melee attack with\
      \ a [scorpion](Інструменти%20ДМ/CLI/bestiary/beast/scorpion-xmm.md) tied to\
      \ the end of a 5-foot-long pole. Melee Weapon Attack: +4 to hit, reach 5\
      \ ft., one target. Hit: 1 piercing damage, and the target must make a DC 9\
      \ Constitution saving throw, taking 4 (d8) poison damage on a failed save,\
      \ or half as much damage on a successful one.  \n- 7 Skunk in a Cage. The\
      \ kobold releases a skunk into an unoccupied space within 5 feet of it. The\
      \ skunk has a walking speed of 20 feet, AC 10, 1 hit point, and no effective\
      \ attacks. It rolls initiative and, on its turn, uses its action to spray musk\
      \ at a random creature within 5 feet of it. The target must succeed on a DC\
      \ 9 Constitution saving throw, or it retches and is [incapacitated](Інструме\
      нти%20ДМ/CLI/rules/conditions.md#Incapacitated) for 1 minute. The target can\
      \ repeat the saving throw at the end of each of its turns, ending the effect\
      \ on itself on a success. A creature that doesn't need to breathe or is immune\
      \ to poison automatically succeeds on the saving throw. Once the skunk has sprayed\
      \ its musk, it can't do so again until it finishes a short or long rest.  \n\
      - 8 Wasp Nest in a Bag. The kobold throws a small bag into a 5-foot-square\
      \ space within 20 feet of it. A [swarm of insects (wasps)](Інструменти%20ДМ\
      /CLI/bestiary/beast/swarm-of-insects-xmm.md) with 11 hit points emerges from\
      \ the bag and rolls initiative. At the end of each of the swarm's turns, there's\
      \ a 50 percent chance that the swarm disperses.  "
    "name": "Weapon Invention"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/kobold-inventor-mpmm.webp"
```
^statblock

## Environment

forest, hill, mountain, underdark, urban