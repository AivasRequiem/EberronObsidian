---
obsidianUIMode: preview
cssclasses: json5e-spell
tags:
- ttrpg-cli/compendium/src/5e/xphb
- ttrpg-cli/spell/class/bard
- ttrpg-cli/spell/class/sorcerer
- ttrpg-cli/spell/class/wizard
- ttrpg-cli/spell/level/7th-level
- ttrpg-cli/spell/school/evocation
- ttrpg-cli/spell/subclass/evoker
classes:
- Bard
- Sorcerer
- Wizard
- Wizard (Evoker)
aliases:
- Prismatic Spray
---
# Prismatic Spray
*7th-level, Evocation*  


- **Casting time:** 1 Action
- **Range:** Self (60-foot Cone)
- **Components:** V, S
- **Duration:** Instantaneous

Eight rays of light flash from you in a 60-foot Cone. Each creature in the Cone makes a Dexterity saving throw. For each target, roll `d8` to determine which color ray affects it, consulting the Prismatic Rays table.

**Prismatic Rays**

`dice: [](prismatic-spray-xphb.md#^prismatic-rays)`

| dice: 1d8 | Ray |
|-----------|-----|
| 1 | **Red.** *Failed Save:* `12d6` Fire damage. *Successful Save:* Half as much damage. |
| 2 | **Orange.** *Failed Save:* `12d6` Acid damage. *Successful Save:* Half as much damage. |
| 3 | **Yellow.** *Failed Save:* `12d6` Lightning damage. *Successful Save:* Half as much damage. |
| 4 | **Green.** *Failed Save:* `12d6` Poison damage. *Successful Save:* Half as much damage. |
| 5 | **Blue.** *Failed Save:* `12d6` Cold damage. *Successful Save:* Half as much damage. |
| 6 | **Indigo.** *Failed Save:* The target has the [Restrained](Інструменти%20ДМ/CLI/rules/conditions.md#Restrained) condition and makes a Constitution saving throw at the end of each of its turns. If it successfully saves three times, the condition ends. If it fails three times, it has the [Petrified](Інструменти%20ДМ/CLI/rules/conditions.md#Petrified) condition until it is freed by an effect like the [Greater Restoration](Інструменти%20ДМ/CLI/spells/greater-restoration-xphb.md) spell. The successes and failures needn't be consecutive; keep track of both until the target collects three of a kind. |
| 7 | **Violet.** *Failed Save:* The target has the [Blinded](Інструменти%20ДМ/CLI/rules/conditions.md#Blinded) condition and makes a Wisdom saving throw at the start of your next turn. On a successful save, the condition ends. On a failed save, the condition ends, and the creature teleports to another plane of existence (DM's choice). |
| 8 | **Special.** The target is struck by two rays. Roll twice, rerolling any 8. |
^prismatic-rays

**Classes**: [Bard](Інструменти%20ДМ/CLI/lists/list-spells-classes-bard.md); [Wizard](Інструменти%20ДМ/CLI/lists/list-spells-classes-wizard.md); [Sorcerer](Інструменти%20ДМ/CLI/lists/list-spells-classes-sorcerer.md); [Wizard (Evoker)](Інструменти%20ДМ/CLI/lists/list-spells-classes-evoker-xphb.md "subclass=XPHB;class=XPHB")

*Source: Player's Handbook (2024) p. 307. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*