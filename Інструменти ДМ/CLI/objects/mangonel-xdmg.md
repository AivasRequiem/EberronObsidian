---
obsidianUIMode: preview
cssclasses: json5e-object
tags:
- ttrpg-cli/compendium/src/5e/xdmg
- ttrpg-cli/object/size/large
- ttrpg-cli/object/type/siege-weapon
aliases:
- Mangonel
---
# Mangonel
%%-- Embedded content starts on the next line. --%%
*Source: Dungeon Master's Guide (2024) p. 97*  

A Mangonel is a catapult that hurls heavy projectiles in a high arc, so it can hit targets behind walls. Loading a Mangonel requires two [Utilize](Інструменти%20ДМ/CLI/rules/actions.md#Utilize) actions, and aiming it requires two more [Utilize](Інструменти%20ДМ/CLI/rules/actions.md#Utilize) actions. Then a crew member can take the Mangonel Stone action.

```ad-statblock
title: Mangonel
![](Інструменти%20ДМ/CLI/objects/token/mangonel-xdmg.webp#token)
*Large Siege weapon*

- **Armor Class** 15
- **Hit Points** 100
- **Speed** 

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|10 (+0)|10 (+0)|10 (+0)|10 (+0)|10 (+0)|


## Actions

***Mangonel Stone (Requires Load and Aim).*** *Ranged Attack Roll:* `dice:1d20+5|noform|noparens|text(+5)`, range 200/800 ft. (can't hit targets within 60 feet of itself). *Hit:* `dice:5d10|noform|noparens|avg|text(27)` (`5d10`) Bludgeoning damage.
```
^statblock