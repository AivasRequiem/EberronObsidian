---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ggr
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- Skittering Horror
---
# [Skittering Horror](Інструменти ДМ\CLI\bestiary\aberration/skittering-horror-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 205*  

## Horrors and Madness

Horrors on Ravnica are terror and madness personified. You can represent this reality by using the madness rules in the Dungeon Master's Guide.

Whenever a character fails a saving throw against the flying horror's Frightening Screech, the shadow horror's claw attack, or the skittering horror's Maddening Presence, note that fact. At the end of the encounter, have each character who failed at least one of those saving throws make a DC 13 Wisdom saving throw. On a successful save, nothing happens. On a failed save, a character gains a form of madness from the Dungeon Master's Guide, with the severity depending on how many of the saving throws that character failed during the encounter, as shown on the Madness Severity table.

**Madness Severity**

| Failed Saves | Madness |
|--------------|---------|
| 1 | Short-term |
| 2-3 | Long-term |
| 4+ | Indefinite |
^madness-severity

## Horrors

Terrifying evils stalk, fly, and scuttle in the dark corners of Ravnica, from the depths of the undercity to the blackest parts of the night sky. Collectively, these creatures are called horrors-a variety of things that lurk in the dark and embody the deepest fears of Ravnica's people. All are evil creatures with dim reason and preternatural cunning.

At least three guilds have been known to compel horrors into service. For House Dimir, horrors spread fear and despair in the citizenry and carry out assassinations or kidnappings against well-protected targets. For the Cult of Rakdos, horrors are simply one more weapon in an arsenal of terrifying and shock-inspiring creatures that might appear on stage. For the Golgari Swarm, horrors scavenge the sewers and protect the guild's territory.

House Dimir uses all three base kinds of horrors. The Cult of Rakdos prefers shadow horrors, and the Golgari Swarm uses skittering horrors.

## Customizing a Horror

Horrors share some common body types but vary wildly in other characteristics. A particular horror's form might incorporate elements that resemble fiendish, insectile, or reptilian features. To customize a horror, choose a base creature (flying horror, shadow horror, or skittering horror), then roll once on the Primary Features table and once on the Secondary Features table (or choose an option from each table). Add those features to the base creature.

**Primary Features**

`dice: [](skittering-horror-ggr.md#^primary-features)`

| dice: d4 | Feature |
|----------|---------|
| 1 | Avoidance. If the horror is subjected to an effect that allows it to make a saving throw to take only half damage, it instead takes no damage if it succeeds on the saving throw, and only half damage if it fails. |
| 2 | Damage Resistances. The horror has resistance to necrotic and psychic damage. |
| 3 | Innate Spellcasting. The horror's innate spellcasting ability is Charisma (spell save DC 13 for flying horror, DC 16 for shadow horror, and DC 17 for skittering horror). It can innately cast the following spells, requiring no material components: 3/day: [darkness](Інструменти%20ДМ/CLI/spells/darkness-xphb.md) 1/day each: [fear](Інструменти%20ДМ/CLI/spells/fear-xphb.md) (shadow horror and skittering horror only), [phantasmal killer](Інструменти%20ДМ/CLI/spells/phantasmal-killer-xphb.md) (skittering horror only) |
| 4 | Psychic Rebuke. When the horror takes damage from a melee attack, it can use its reaction to emit psychic energy within a 5-foot radius. Each creature in that area takes 3 (`d6`) psychic damage (flying horror), 7 (`2d6`) psychic damage (shadow horror), or 10 (`3d6`) psychic damage (skittering horror). |
^primary-features

**Secondary Features**

`dice: [](skittering-horror-ggr.md#^secondary-features)`

| dice: d4 | Feature |
|----------|---------|
| 1 | Grasping Tendrils. The horror has four tendrils. Each tendril can be attacked (AC 12, 10 hit points). Destroying one deals no damage to the horror. As a bonus action, the horror can target one creature it can see within 10 feet of it. The target must succeed on a Dexterity saving throw or be [grappled](Інструменти%20ДМ/CLI/rules/conditions.md#Grappled) by the horror. The DC of the saving throw and the DC to escape the grapple are the same: 9 for the flying horror, 13 for the shadow horror, and 19 for the skittering horror. Until the grapple ends, the horror can't use the same tendril to grapple another target. |
| 2 | Indomitable Mind. The horror is immune to the [charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed) condition. |
| 3 | Keen Senses. The horror has advantage on Wisdom ([Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)) checks that rely on sight, sound, or smell. |
| 4 | Mind Sight. Magical darkness doesn't impede the horror's [darkvision](Інструменти%20ДМ/CLI/rules/senses.md#Darkvision). |
^secondary-features

```statblock
"name": "Skittering Horror (GGR)"
"size": "Huge"
"type": "aberration"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "228"
"hit_dice": "24d12 + 72"
"modifier": !!int "3"
"stats":
  - !!int "22"
  - !!int "16"
  - !!int "17"
  - !!int "2"
  - !!int "14"
  - !!int "18"
"speed": "40 ft., climb 40 ft."
"skillsaves":
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Stealth](Інструменти%20ДМ/CLI/rules/skills.md#Stealth)"
    "desc": "+8"
"damage_vulnerabilities": "radiant"
"condition_immunities": "[frightened](Інструменти%20ДМ/CLI/rules/conditions.md#Frightened)"
"senses": "darkvision 120 ft., passive Perception 17"
"languages": ""
"cr": "15"
"traits":
  - "desc": "The horror can climb difficult surfaces, including upside down on ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "While in sunlight, the horror has disadvantage on attack rolls and on\
      \ Wisdom ([Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)) checks\
      \ that rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "The horror can use its Maddening Presence and make three attacks: one\
      \ with its bite and two with its claws."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +11 to hit, reach 10 ft., one target. Hit:\
      \ 28 (4d10 + 6) piercing damage."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +11 to hit, reach 10 ft., one target. Hit:\
      \ 24 (4d8 + 6) slashing damage."
    "name": "Claws"
  - "desc": "The horror targets one creature it can see within 30 feet of it. If the\
      \ target can see or hear the horror, the target must make a DC 17 Wisdom saving\
      \ throw. On a failed saving throw, the target becomes [paralyzed](Інструмент\
      и%20ДМ/CLI/rules/conditions.md#Paralyzed) until the end of its next turn. If\
      \ a creature's saving throw is successful, the creature is immune to the horror's\
      \ Maddening Presence for the next 24 hours."
    "name": "Maddening Presence"
"source":
  - "GGR"
"image": "Інструменти%20ДМ/CLI/bestiary/aberration/token/skittering-horror-ggr.webp"
```
^statblock