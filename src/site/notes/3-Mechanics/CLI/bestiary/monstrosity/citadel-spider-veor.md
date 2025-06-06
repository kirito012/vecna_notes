---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/monstrosity/citadel-spider-veor/","tags":["ttrpg-cli/compendium/src/5e/veor","ttrpg-cli/monster/cr/18","ttrpg-cli/monster/size/gargantuan","ttrpg-cli/monster/type/monstrosity"],"noteIcon":""}
---

# [Citadel Spider](3-Mechanics\CLI\bestiary\monstrosity/citadel-spider-veor.md)
*Source: Vecna: Eve of Ruin p. 214*  

> [!quote] A quote from Camlash, Balor General of Lolth  
> 
> Citadel spiders aren't smart, but for sheer battlefield power and versatility, they can't be beat.

Lolth's followers breed spiders of all types and sizes, infusing the creatures with foul energy from the Demonweb Pits. Perhaps the most feared of such abominations is the citadel spider. The titanic citadel spider serves as a powerhouse weapon and mobile command post. Wedges of chitin atop a citadel spider's back shield passengers and protect the spider's biological cannon. A citadel spider can launch globs of acidic webbing from its cannon that hold victims in place until the spider can eviscerate them with its serrated jaws.

```statblock
"name": "Citadel Spider (VEoR)"
"size": "Gargantuan"
"type": "monstrosity"
"alignment": "typically  Neutral Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "310"
"hit_dice": "20d20 + 150"
"stats":
- !!int "26"
- !!int "10"
- !!int "21"
- !!int "6"
- !!int "12"
- !!int "9"
"speed": "50 ft., climb 50 ft."
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)"
"senses": "blindsight 30 ft., darkvision 120 ft., passive Perception 11"
"languages": ""
"cr": "18"
"traits":
- "desc": "If the spider fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "The spider can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
- "desc": "The spider ignores movement restrictions caused by webbing."
  "name": "Web Walker"
"actions":
- "desc": "The spider makes two Bite attacks. It can replace one of these attacks\
    \ with a use of Web Bomb."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +14 to hit, reach 20 ft., one target. Hit: 19\
    \ (2d10 + 8) piercing damage plus 7 (2d6) poison damage."
  "name": "Bite"
- "desc": "Ranged Weapon Attack: +14 to hit, range 300 ft./600 ft., one target.\
    \ Hit: 24 (3d10 + 8) bludgeoning damage, and the target and all creatures within\
    \ 10 feet of it must succeed on a DC 19 Dexterity saving throw or take 10 (3d6)\
    \ acid damage and have the [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
    \ condition until the start of the spider's next turn."
  "name": "Web Bomb"
"reactions":
- "desc": "In response to being hit with an attack roll, the spider's carapace absorbs\
    \ some of the blow, reducing the damage it takes by 11 (2d10)."
  "name": "Absorb Blow"
"source":
- "VEoR"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/citadel-spider-veor.webp"
```
^statblock