---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/fiend/degloth-veor/","tags":["ttrpg-cli/compendium/src/5e/veor","ttrpg-cli/monster/cr/11","ttrpg-cli/monster/size/large","ttrpg-cli/monster/type/fiend/demon"],"noteIcon":""}
---

# [Degloth](3-Mechanics\CLI\bestiary\fiend/degloth-veor.md)
*Source: Vecna: Eve of Ruin p. 218*  

Degloths are massive, blue, bipedal demons with razor-studded fists. They are commonly used as shock troops on the front lines of wars waged in the Abyss and other Outer Planes. Degloths gravitate toward violence and mayhem without caring about the reasons behind the bloodshed. They enjoy ripping their enemies limb from limb using their razor-studded fists, which are equally adept at slashing foes and crushing the life from them.

```statblock
"name": "Degloth (VEoR)"
"size": "Large"
"type": "fiend"
"subtype": "demon"
"alignment": "typically  Chaotic Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "133"
"hit_dice": "14d10 + 56"
"stats":
- !!int "23"
- !!int "17"
- !!int "18"
- !!int "6"
- !!int "11"
- !!int "9"
"speed": "40 ft., climb 40 ft."
"saves":
  "Strength": !!int "10"
  "Constitution": !!int "8"
"skillsaves":
  "Athletics": !!int "10"
  "Perception": !!int "4"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 14"
"languages": "Abyssal, telepathy 120 ft."
"cr": "11"
"traits":
- "desc": "The degloth has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The degloth makes two Razor Fist attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 17\
    \ (2d10 + 6) slashing damage, and if the target is a Medium or smaller creature,\
    \ the target has the [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
    \ condition (escape DC 18). Until this grapple ends, the target has the [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
    \ condition, and the degloth can't use this fist to grapple another target. The\
    \ degloth has two fists."
  "name": "Razor Fist"
"bonus_actions":
- "desc": "The degloth targets one creature currently [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
    \ by it. The target must make a DC 18 Strength saving throw, taking 15 (2d8 +\
    \ 6) bludgeoning damage on a failed save or half as much damage on a successful\
    \ one."
  "name": "Crush"
"source":
- "VEoR"
"image": "3-Mechanics/CLI/bestiary/fiend/token/degloth-veor.webp"
```
^statblock