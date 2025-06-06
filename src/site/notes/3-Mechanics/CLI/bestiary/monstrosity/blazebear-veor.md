---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/monstrosity/blazebear-veor/","tags":["ttrpg-cli/compendium/src/5e/veor","ttrpg-cli/monster/cr/12","ttrpg-cli/monster/size/large","ttrpg-cli/monster/type/monstrosity"],"noteIcon":""}
---

# [Blazebear](3-Mechanics\CLI\bestiary\monstrosity/blazebear-veor.md)
*Source: Vecna: Eve of Ruin p. 210*  

> [!quote] A quote from Clank, Warforged Merchant from Sharn  
> 
> Even the animals in the Mournland are warped by magic. You should see the bears—terrifying!

On the world of Eberron, many strange, magic-warped monsters have emerged from the depths of the war-wracked Mournland. The blazebear is one such monster, so named for its hulking, ursine figure and the glow of its eyes. This glow is magical energy that saturates the blazebear's entire body. Swipes from a blazebear's claws dole out painful wounds and can end spells, and its gaze can stun prey.

```statblock
"name": "Blazebear (VEoR)"
"size": "Large"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "189"
"hit_dice": "18d10 + 90"
"stats":
- !!int "24"
- !!int "17"
- !!int "21"
- !!int "3"
- !!int "13"
- !!int "16"
"speed": "30 ft."
"saves":
  "Charisma": !!int "7"
  "Strength": !!int "11"
"skillsaves":
  "Perception": !!int "5"
"senses": "darkvision 120 ft., passive Perception 15"
"languages": ""
"cr": "12"
"traits":
- "desc": "The blazebear has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The blazebear can see normally through heavily obscured areas created by\
    \ mist or fog, including areas created by spells such as Fog Cloud."
  "name": "Mist Sight"
"actions":
- "desc": "The blazebear makes two Bite attacks. It can replace one attack with Stunning\
    \ Gaze if available."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +11 to hit, reach 5 ft., one target. Hit: 20 (2d12\
    \ + 7) piercing damage plus 11 (2d10) force damage."
  "name": "Bite"
- "desc": "The blazebear targets two creatures it can see within 120 feet of itself.\
    \ Each target must succeed on a DC 15 Wisdom saving throw or have the [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)\
    \ condition until the start of the blazebear's next turn."
  "name": "Stunning Gaze (Recharge 5-6)"
"reactions":
- "desc": "Melee Weapon Attack: +11 to hit, reach 10 ft., one creature casting a\
    \ spell of 3rd level or lower. Hit: 22 (4d10) force damage, and the target must\
    \ succeed on a DC 15 Intelligence saving throw or the spell fails and has no effect."
  "name": "Antimagic Swipe"
"source":
- "VEoR"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/blazebear-veor.webp"
```
^statblock