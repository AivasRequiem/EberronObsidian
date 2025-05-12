---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/erlw
- ttrpg-cli/monster/cr/0
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- Magewright
---
# [Magewright](Інструменти ДМ\CLI\bestiary\humanoid/magewright-erlw.md)
*Source: Eberron: Rising from the Last War p. 318*  

In Khorvaire, magic is part of everyday life. A chef might use [prestidigitation](Інструменти%20ДМ/CLI/spells/prestidigitation-xphb.md) to heat and season food, while a blacksmith uses [mending](Інструменти%20ДМ/CLI/spells/mending-xphb.md) to perform minor repairs and [guidance](Інструменти%20ДМ/CLI/spells/guidance-xphb.md) to help inspire their work. Those who work minor magic into their labors are called magewrights.

Far more limited in magical power than a typical spellcaster, a magewright is dedicated to learning a handful of spells, and magewrights cast their non-cantrip spells as rituals—even spells that can't normally be cast in this way. Most magewright rituals take 10 minutes to perform, but certain complex rituals can take up to 1 hour. However long the ritual takes, it requires extra material components, usually in the form of dragonshards.

## Creating a Magewright

The magewright stat block provides the baseline statistics for a magewright. You then add to that baseline by choosing a specialty from the Magewright Specialties table, or roll for one. The specialty determines additional spells the magewright knows, including ones that can be cast only as rituals. The specialty also gives the magewright more proficiencies.

**Magewright Specialties**

`dice: [](magewright-erlw.md#^magewright-specialties)`

| dice: d8 | Specialty | Spells | Proficiencies |
|----------|-----------|--------|---------------|
| 1 | Artisan | [Guidance](Інструменти%20ДМ/CLI/spells/guidance-xphb.md), [mending](Інструменти%20ДМ/CLI/spells/mending-xphb.md) | One type of artisan's tools |
| 2 | Entertainer | [Minor illusion](Інструменти%20ДМ/CLI/spells/minor-illusion-xphb.md), [thaumaturgy](Інструменти%20ДМ/CLI/spells/thaumaturgy-xphb.md). Ritual only: [disguise self](Інструменти%20ДМ/CLI/spells/disguise-self-xphb.md). | [Performance](Інструменти%20ДМ/CLI/rules/skills.md#Performance) (+3) |
| 3 | Healer | [Resistance](Інструменти%20ДМ/CLI/spells/resistance-xphb.md), [spare the dying](Інструменти%20ДМ/CLI/spells/spare-the-dying-xphb.md). Ritual only: [detect poison and disease](Інструменти%20ДМ/CLI/spells/detect-poison-and-disease-xphb.md), [lesser restoration](Інструменти%20ДМ/CLI/spells/lesser-restoration-xphb.md) (1 hour). | [Medicine](Інструменти%20ДМ/CLI/rules/skills.md#Medicine) (+4), [herbalism kit](Інструменти%20ДМ/CLI/items/herbalism-kit-xphb.md) |
| 4 | Lamplighter | [Light](Інструменти%20ДМ/CLI/spells/light-xphb.md). Ritual only: [continual flame](Інструменти%20ДМ/CLI/spells/continual-flame-xphb.md) (1 hour). | [Tinker's tools](Інструменти%20ДМ/CLI/items/tinkers-tools-xphb.md) |
| 5 | Locksmith | [Mending](Інструменти%20ДМ/CLI/spells/mending-xphb.md). Ritual only: [arcane lock](Інструменти%20ДМ/CLI/spells/arcane-lock-xphb.md) (1 hour), [knock](Інструменти%20ДМ/CLI/spells/knock-xphb.md). | [Thieves' tools](Інструменти%20ДМ/CLI/items/thieves-tools-xphb.md), [tinker's tools](Інструменти%20ДМ/CLI/items/tinkers-tools-xphb.md) |
| 6 | Mediator | [Guidance](Інструменти%20ДМ/CLI/spells/guidance-xphb.md). Ritual only: [comprehend languages](Інструменти%20ДМ/CLI/spells/comprehend-languages-xphb.md), [zone of truth](Інструменти%20ДМ/CLI/spells/zone-of-truth-xphb.md). | [Insight](Інструменти%20ДМ/CLI/rules/skills.md#Insight) (+4), [Persuasion](Інструменти%20ДМ/CLI/rules/skills.md#Persuasion) (+3) |
| 7 | Medium | [Minor illusion](Інструменти%20ДМ/CLI/spells/minor-illusion-xphb.md). Ritual only: [speak with dead](Інструменти%20ДМ/CLI/spells/speak-with-dead-xphb.md). | [Deception](Інструменти%20ДМ/CLI/rules/skills.md#Deception) (+3), [Religion](Інструменти%20ДМ/CLI/rules/skills.md#Religion) (+4) |
| 8 | Oracle | [Guidance](Інструменти%20ДМ/CLI/spells/guidance-xphb.md). Ritual only: [augury](Інструменти%20ДМ/CLI/spells/augury-xphb.md), [divination](Інструменти%20ДМ/CLI/spells/divination-xphb.md) (1 hour). | [History](Інструменти%20ДМ/CLI/rules/skills.md#History) (+4), [Religion](Інструменти%20ДМ/CLI/rules/skills.md#Religion) (+4) |
^magewright-specialties

```statblock
"name": "Magewright (ERLW)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "11"
"hp": !!int "9"
"hit_dice": "2d8"
"modifier": !!int "1"
"stats":
  - !!int "11"
  - !!int "13"
  - !!int "10"
  - !!int "14"
  - !!int "14"
  - !!int "12"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](Інструменти%20ДМ/CLI/rules/skills.md#Arcana)"
    "desc": "+4"
"senses": "passive Perception 12"
"languages": "Common plus any two languages"
"cr": "0"
"traits":
  - "desc": "The magewright's spellcasting ability is Intelligence (spell save DC\
      \ 12). To cast one of its rituals, the magewright must provide additional material\
      \ components whose value in gold pieces is 20 times the spell's level. These\
      \ components are consumed when the ritual is finished. The magewright knows\
      \ the following spells:\n\nAt will: [mage hand](Інструменти%20ДМ/CLI/spells/mage-hand-xphb.md),\
      \ [prestidigitation](Інструменти%20ДМ/CLI/spells/prestidigitation-xphb.md)\n\
      \nRituals: [knock](Інструменти%20ДМ/CLI/spells/knock-xphb.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "Melee  or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. Hit: 3 (1d4 + 1) piercing damage."
    "name": "Dagger"
"source":
  - "ERLW"
"image": "Інструменти%20ДМ/CLI/bestiary/humanoid/token/magewright-erlw.webp"
```
^statblock