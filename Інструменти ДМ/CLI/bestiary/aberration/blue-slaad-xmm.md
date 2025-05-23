---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/environment/limbo
- ttrpg-cli/monster/environment/planar
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- Blue Slaad
---
# [Blue Slaad](Інструменти ДМ\CLI\bestiary\aberration/blue-slaad-xmm.md)
*Source: Monster Manual (2024) p. 285*  

Almost as numerous as red slaadi, blue slaadi are muscular brutes with vicious blades extending from the backs of their claws. These claws carry a magical curse called chaos phage, which can transform victims into red or green slaadi. Blue slaadi accompany red slaadi and behave similarly. They innately know the signs of chaos phage and avoid slaying creatures that carry it or other slaad curses.

## Slaadi

*Chaos-Spawned Hordes of Limbo*

- **Habitat.** Planar (Limbo)  
- **Treasure.** Any  

Unpredictable slaadi devour and multiply across the Ever-Changing Chaos of Limbo. These toad-like, extraplanar beings embody the endless potentiality of their home plane of existence. While slaadi aren't inherently evil, their impulses are wild and often destructive. Many are driven to propagate through supernatural processes. Unfortunately, these processes typically are fatal for other creatures.

Slaadi have no formal society. Rather, strong slaadi dominate weaker ones. Blue and red slaadi rampage across Limbo and spill into other worlds at the direction of green slaadi. More powerful slaadi have connections to the Spawning Stone, a source of chaotic magic from which the first slaadi originated. The Spawning Stone is hidden deep within Limbo, and legends tie its origins to the modron overlord Primus or the ruinous slaad lords, such as Ssendam, the golden amoeboid terror, and Ygorl, the winged skeleton. These slaad lords and others plot to spread slaadi across the multiverse.

> [!note] Slaad Control Gems
> 
> A slaad born from the Spawning Stone has a magical control gem embedded in its head. If a creature claims the gem, the slaad has the [Charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed) condition and obeys the gem's bearer. The slaad ceases to be [Charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed) if it is harmed by the gem's bearer or the bearer's allies or if the gem is returned to the slaad. A [Greater Restoration](Інструменти%20ДМ/CLI/spells/greater-restoration-xphb.md) spell cast on a slaad destroys the gem, and the slaad ceases to be [Charmed](Інструменти%20ДМ/CLI/rules/conditions.md#Charmed).
> 
> One can obtain a slaad's control gem using a [Wish](Інструменти%20ДМ/CLI/spells/wish-xphb.md) or [Imprisonment](Інструменти%20ДМ/CLI/spells/imprisonment-xphb.md) spell. If the slaad fails its saving throw against [Imprisonment](Інструменти%20ДМ/CLI/spells/imprisonment-xphb.md), the caster gains the gem, and the slaad isn't imprisoned. An [Incapacitated](Інструменти%20ДМ/CLI/rules/conditions.md#Incapacitated) slaad's control gem can be removed by spending 1 minute and succeeding on a DC 20 Wisdom ([Medicine](Інструменти%20ДМ/CLI/rules/skills.md#Medicine)) check. Failing this check deals 22 (`4d10`) Piercing damage to the slaad.
^slaad-control-gems

> [!quote] A quote from Jebeel Sloom  
> 
> Fight a slaad and lose, the story's over. Fight a slaad and win, there's a thousand more standing in line just to prove they're tougher.


```statblock
"name": "Blue Slaad (XMM)"
"size": "Large"
"type": "aberration"
"alignment": "Chaotic Neutral"
"ac": !!int "15"
"hp": !!int "133"
"hit_dice": "14d10 + 56"
"modifier": !!int "2"
"stats":
  - !!int "20"
  - !!int "15"
  - !!int "18"
  - !!int "7"
  - !!int "7"
  - !!int "9"
"speed": "30 ft."
"skillsaves":
  - "name": "[Perception](Інструменти%20ДМ/CLI/rules/skills.md#Perception)"
    "desc": "+1"
"damage_resistances": "acid, cold, fire, lightning, thunder"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Slaad; telepathy 60 ft."
"cr": "7"
"traits":
  - "desc": "The slaad has [Advantage](Інструменти%20ДМ/CLI/rules/variant-rules/advantage-xphb.md)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "The slaad regains 10 [Hit Points](Інструменти%20ДМ/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ at the start of each of its turns if it has at least 1 [Hit Point](Інструм\
      енти%20ДМ/CLI/rules/variant-rules/hit-points-xphb.md)."
    "name": "Regeneration"
"actions":
  - "desc": "The slaad makes three Mutating Claw attacks."
    "name": "Multiattack"
  - "desc": "Melee Attack Roll: +8, reach 10 ft. Hit: 12 (2d6 + 5) Slashing\
      \ damage plus 3 (d6) Poison damage. If the target is a Humanoid not cursed\
      \ by a slaad, it is subjected to the following effect. Constitution Saving\
      \ Throw: DC 15. Failure: The target is cursed. The cursed target can't regain\
      \ [Hit Points](Інструменти%20ДМ/CLI/rules/variant-rules/hit-points-xphb.md),\
      \ and its [Hit Point](Інструменти%20ДМ/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ maximum decreases by 10 (3d6) after every 24 hours and doesn't return to\
      \ normal after finishing a [Long Rest](Інструменти%20ДМ/CLI/rules/variant-rules/long-rest-xphb.md).\
      \ If the curse reduces the target's [Hit Point](Інструменти%20ДМ/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ maximum to 0, the curse ends, and instead of dying, the target instantly transforms\
      \ into a [Red Slaad](Інструменти%20ДМ/CLI/bestiary/aberration/red-slaad-xmm.md)\
      \ or, if it can cast spells of level 3 or higher, a [Green Slaad](Інструмент\
      и%20ДМ/CLI/bestiary/aberration/green-slaad-xmm.md). Only a [Wish](Інструмент\
      и%20ДМ/CLI/spells/wish-xphb.md) spell can reverse this transformation."
    "name": "Mutating Claw"
"source":
  - "XMM"
"image": "Інструменти%20ДМ/CLI/bestiary/aberration/token/blue-slaad-xmm.webp"
```
^statblock

## Environment

planar, limbo