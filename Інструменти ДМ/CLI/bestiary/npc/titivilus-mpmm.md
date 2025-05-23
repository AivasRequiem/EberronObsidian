---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/16
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
statblock-link: "#^statblock"
aliases:
- Titivilus
---
# [Titivilus](Інструменти ДМ\CLI\bestiary\npc/titivilus-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 242*  

Dispater, the gloomy Lord of Dis, rules from his iron palace, seeming to hide behind its labyrinthine corridors, iron walls, diabolical traps, and monstrous servants. Knowing he has enemies on all sides and fearing he'll be displaced like Moloch, Geryon, and so many others, he almost never travels farther than the sprawling city that lies outside his palace.

Dispater is correct to fear, but the true threat comes not from without. The lord's great error was allowing himself to be seduced by Titivilus, who beguiled his way into being the primary advisor in Dispater's household.

Although Titivilus is inferior in physical strength and power when compared to other archdevils, he compensates with cunning. A shrewd politician, he has clawed his way up through the ranks to become the second-most powerful devil in Dis, entirely by saying the right thing at the right time to get what he wanted. Charming and pleasant, he is a master at negotiation, able to twist words so as to leave his victims confused and believing he's on their side. Through these skills, Titivilus has manipulated everyone along his path to power, either to win them over to his cause or to remove them as a threat.

Since gaining his position, Titivilus has convinced Dispater that countless plots are being hatched against him and that Asmodeus himself seeks to remove Dispater from power. In response, Dispater has withdrawn to his palace and left day-to-day decisions to Titivilus, even authorizing him to answer and negotiate bargains with mortals who attempt to summon Dispater. Titivilus now represents his master and speaks with his voice, a turn of events that leads some to whisper that either Titivilus is Dispater in disguise or Titivilus has removed the archduke and replaced him altogether.

Titivilus recognizes the precariousness of his position. After all, Dispater's acceptance of his plans and his advice can last only so long before some other plotter steps in and reveals the truth. For insurance, Titivilus has begun recruiting outsiders to deal with problem devils, to insulate him against criticism, and, above all, to create complications that he can solve so as to reinforce his value in the eyes of his master. Titivilus finds adventurers well suited to the tasks he needs performed and recruits them directly or through intermediaries, expending them later as his plans require.

```statblock
"name": "Titivilus (MPMM)"
"size": "Medium"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "150"
"hit_dice": "20d8 + 60"
"modifier": !!int "6"
"stats":
  - !!int "19"
  - !!int "22"
  - !!int "17"
  - !!int "24"
  - !!int "22"
  - !!int "26"
"speed": "40 ft., fly 60 ft."
"saves":
  - "dexterity": "+11"
  - "constitution": "+8"
  - "wisdom": "+11"
  - "charisma": "+13"
"skillsaves":
  - "name": "[Deception](Інструменти%20ДМ/CLI/rules/skills.md#Deception)"
    "desc": "+13"
  - "name": "[Insight](Інструменти%20ДМ/CLI/rules/skills.md#Insight)"
    "desc": "+11"
  - "name": "[Intimidation](Інструменти%20ДМ/CLI/rules/skills.md#Intimidation)"
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
"senses": "darkvision 120 ft., passive Perception 16"
"languages": "all, telepathy 120 ft."
"cr": "16"
"traits":
  - "desc": "If Titivilus fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Titivilus has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "Titivilus regains 10 hit points at the start of his turn. If he takes\
      \ cold or radiant damage, this trait doesn't function at the start of his next\
      \ turn. Titivilus dies only if he starts his turn with 0 hit points and doesn't\
      \ regenerate."
    "name": "Regeneration"
  - "desc": "Whenever Titivilus speaks, he can choose a point within 60 feet of him;\
      \ his voice emanates from that point."
    "name": "Ventriloquism"
"actions":
  - "desc": "Titivilus makes one Silver Sword attack, and he uses Frightful Word."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 8\
      \ (1d8 + 4) force damage, or 9 (1d10 + 4) force damage if used with two\
      \ hands, plus 16 (3d10) necrotic damage. If the target is a creature, its\
      \ hit point maximum is reduced by an amount equal to half the necrotic damage\
      \ taken."
    "name": "Silver Sword"
  - "desc": "Titivilus targets one creature he can see within 10 feet of him. The\
      \ target must succeed on a DC 21 Wisdom saving throw or become [frightened](І\
      нструменти%20ДМ/CLI/rules/conditions.md#Frightened) of him for 1 minute. While\
      \ [frightened](Інструменти%20ДМ/CLI/rules/conditions.md#Frightened) in this\
      \ way, the target must take the [Dash](Інструменти%20ДМ/CLI/rules/actions.md#Dash)\
      \ action and move away from Titivilus by the safest available route on each\
      \ of its turns, unless there is nowhere to move, in which case it needn't take\
      \ the [Dash](Інструменти%20ДМ/CLI/rules/actions.md#Dash) action. The target\
      \ can repeat the saving throw at the end of each of its turns, ending the effect\
      \ on itself on a success."
    "name": "Frightful Word"
  - "desc": "Titivilus teleports, along with any equipment he is wearing or carrying,\
      \ up to 120 feet to an unoccupied space he can see."
    "name": "Teleport"
  - "desc": "Titivilus targets one creature he can see within 60 feet of him. The\
      \ target must succeed on a DC 21 Charisma saving throw or become [charmed](І\
      нструменти%20ДМ/CLI/rules/conditions.md#Charmed) by Titivilus for 1 minute.\
      \ The [charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed) target can\
      \ repeat the saving throw if Titivilus deals any damage to it. A creature that\
      \ succeeds on the saving throw is immune to Titivilus's Twisting Words for 24\
      \ hours."
    "name": "Twisting Words"
  - "desc": "Titivilus casts one of the following spells, requiring no material components\
      \ and using Charisma as the spellcasting ability (spell save DC 21):\n\nAt\
      \ will: [alter self](Інструменти%20ДМ/CLI/spells/alter-self-xphb.md), [major\
      \ image](Інструменти%20ДМ/CLI/spells/major-image-xphb.md), [nondetection](Ін\
      струменти%20ДМ/CLI/spells/nondetection-xphb.md), [sending](Інструменти%20ДМ\
      /CLI/spells/sending-xphb.md), [suggestion](Інструменти%20ДМ/CLI/spells/suggestion-xphb.md)\n\
      \n3/day each: [mislead](Інструменти%20ДМ/CLI/spells/mislead-xphb.md), [modify\
      \ memory](Інструменти%20ДМ/CLI/spells/modify-memory-xphb.md)"
    "name": "Spellcasting"
"legendary_actions":
  - "desc": "Titivilus uses Twisting Words. Alternatively, he targets one creature\
      \ [charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed) by him that is\
      \ within 60 feet of him; that [charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed)\
      \ target must succeed on a DC 21 Charisma saving throw, or Titivilus decides\
      \ how the target acts during its next turn."
    "name": "Corrupting Guidance"
  - "desc": "Titivilus uses Teleport."
    "name": "Teleport"
  - "desc": "Titivilus makes one Silver Sword attack, or he uses Frightful Word."
    "name": "Assault (Costs 2 Actions)"
"source":
  - "MPMM"
"image": "Інструменти%20ДМ/CLI/bestiary/npc/token/titivilus-mpmm.webp"
```
^statblock