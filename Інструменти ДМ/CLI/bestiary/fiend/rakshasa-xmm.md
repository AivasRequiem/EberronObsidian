---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/environment/nine-hells
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- Rakshasa
---
# [Rakshasa](Інструменти ДМ\CLI\bestiary\fiend/rakshasa-xmm.md)
*Source: Monster Manual (2024) p. 253. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Rakshasa

*Deceiver Hungry for Power and Flesh*

- **Habitat.** Planar (Nine Hells), Urban  
- **Treasure.** Relics  

Masters of manipulation, rakshasas infiltrate communities to claim positions of power. While disguising their true natures, they kidnap victims and indulge their insatiable hunger for flesh.

Rakshasas can withstand some degree of magic, but legends tell of blessed warriors felling them with crossbow bolts, arrows, or similar weapons.

Rakshasas' appearances combine humanlike bodies with the features of animals and monsters. All rakshasas have a physical oddity that remains when they adopt magical disguises, such as palms where the backs of the hands would be on humans.

```statblock
"name": "Rakshasa (XMM)"
"size": "Medium"
"type": "fiend"
"alignment": "Lawful Evil"
"ac": !!int "17"
"hp": !!int "221"
"hit_dice": "26d8 + 104"
"modifier": !!int "8"
"stats":
  - !!int "14"
  - !!int "17"
  - !!int "18"
  - !!int "13"
  - !!int "16"
  - !!int "20"
"speed": "40 ft."
"skillsaves":
  - "name": "[Deception](Інструменти%20ДМ/CLI/rules/skills.md#Deception)"
    "desc": "+10"
  - "name": "[Insight](Інструменти%20ДМ/CLI/rules/skills.md#Insight)"
    "desc": "+8"
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+8"
"damage_vulnerabilities": "piercing damage from weapons wielded by creatures under\
  \ the effect of a Bless spell"
"condition_immunities": "[charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed),\
  \ [frightened](Інструменти%20ДМ/CLI/rules/conditions.md#Frightened)"
"senses": "truesight 60 ft., passive Perception 18"
"languages": "Common, Infernal"
"cr": "13"
"traits":
  - "desc": "The rakshasa automatically succeeds on saving throws against spells and\
      \ other magical effects, and the attack rolls of spells automatically miss it.\
      \ Without the rakshasa's permission, no spell can observe the rakshasa remotely\
      \ or detect its thoughts, creature type, or alignment."
    "name": "Greater Magic Resistance"
  - "desc": "If the rakshasa dies outside the Nine Hells, its body turns to ichor,\
      \ and it gains a new body instantly, reviving with all its [Hit Points](Інст\
      рументи%20ДМ/CLI/rules/variant-rules/hit-points-xphb.md) somewhere in the Nine\
      \ Hells."
    "name": "Fiendish Restoration"
"actions":
  - "desc": "The rakshasa makes three Cursed Touch attacks."
    "name": "Multiattack"
  - "desc": "Melee Attack Roll: dice:1d20+10|noform|noparens|text(+10), reach\
      \ 5 ft. Hit: dice:2d6+5|noform|noparens|avg|text(12) (2d6 + 5) Slashing\
      \ damage plus dice:3d12|noform|noparens|avg|text(19) (3d12) Necrotic damage.\
      \ If the target is a creature, it is cursed. While cursed, the target gains\
      \ no benefit from finishing a [Short](Інструменти%20ДМ/CLI/rules/variant-rules/short-rest-xphb.md)\
      \ or [Long Rest](Інструменти%20ДМ/CLI/rules/variant-rules/long-rest-xphb.md)."
    "name": "Cursed Touch"
  - "desc": "Wisdom Saving Throw: DC 18, each enemy in a 30-foot [Emanation](Інс\
      трументи%20ДМ/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating\
      \ from the rakshasa. Failure: dice:8d6|noform|noparens|avg|text(28) (8d6)\
      \ Psychic damage, and the target has the [Frightened](Інструменти%20ДМ/CLI/rules/conditions.md#Frightened)\
      \ and [Incapacitated](Інструменти%20ДМ/CLI/rules/conditions.md#Incapacitated)\
      \ conditions until the start of the rakshasa's next turn."
    "name": "Baleful Command (Recharge 5-6)"
  - "desc": "The rakshasa casts one of the following spells, requiring no Material\
      \ components and using Charisma as the spellcasting ability (spell save DC 18):\n\
      \nAt will: [Detect Magic](Інструменти%20ДМ/CLI/spells/detect-magic-xphb.md),\
      \ [Detect Thoughts](Інструменти%20ДМ/CLI/spells/detect-thoughts-xphb.md), [Disguise\
      \ Self](Інструменти%20ДМ/CLI/spells/disguise-self-xphb.md), [Mage Hand](Інст\
      рументи%20ДМ/CLI/spells/mage-hand-xphb.md), [Minor Illusion](Інструменти%20Д\
      М/CLI/spells/minor-illusion-xphb.md)\n\n1/day each: [Fly](Інструменти%20Д\
      М/CLI/spells/fly-xphb.md), [Invisibility](Інструменти%20ДМ/CLI/spells/invisibility-xphb.md),\
      \ [Major Image](Інструменти%20ДМ/CLI/spells/major-image-xphb.md), [Plane Shift](І\
      нструменти%20ДМ/CLI/spells/plane-shift-xphb.md)"
    "name": "Spellcasting"
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/fiend/token/rakshasa-xmm.webp"
```
^statblock

## Environment

planar, nine hells, urban