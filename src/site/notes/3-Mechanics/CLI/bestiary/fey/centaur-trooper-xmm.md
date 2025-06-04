---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/fey/centaur-trooper-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/2","ttrpg-cli/monster/environment/feywild","ttrpg-cli/monster/environment/forest","ttrpg-cli/monster/environment/grassland","ttrpg-cli/monster/environment/planar","ttrpg-cli/monster/size/large","ttrpg-cli/monster/type/fey"],"noteIcon":""}
---

# [Centaur Trooper](3-Mechanics\CLI\bestiary\fey/centaur-trooper-xmm.md)
*Source: Monster Manual (2024) p. 67*  

Centaur troopers are knight-like guardians. Many are suspicious of non-Fey creatures.

## Centaurs

*Defenders of the Feywild*

- **Habitat.** Forest, Grassland, Planar (Feywild)  
- **Treasure.** Armaments, Individual  

Centaurs are defenders of forests, plains, and sites of primeval power. With upper bodies like humans' and the lower bodies of horses, centaurs charge into battle against those who would harm their allies.

```statblock
"name": "Centaur Trooper (XMM)"
"size": "Large"
"type": "fey"
"alignment": "Neutral Good"
"ac": !!int "16"
"hp": !!int "45"
"hit_dice": "6d10 + 12"
"stats":
- !!int "18"
- !!int "14"
- !!int "14"
- !!int "9"
- !!int "13"
- !!int "11"
"speed": "50 ft."
"skillsaves":
  "Athletics": !!int "6"
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": "Elvish, Sylvan"
"cr": "2"
"actions":
- "desc": "The centaur makes two attacks, using Pike or Longbow in any combination."
  "name": "Multiattack"
- "desc": "Melee Attack Roll: +6, reach 10 ft. Hit: 9 (1d10 + 4) Piercing\
    \ damage."
  "name": "Pike"
- "desc": "Ranged Attack Roll: +4, range 150/600 ft. Hit: 6 (1d8 + 2) Piercing\
    \ damage."
  "name": "Longbow"
"bonus_actions":
- "desc": "The centaur moves up to its [Speed](3-Mechanics/CLI/rules/variant-rules/speed-xphb.md)\
    \ without provoking Opportunity Attacks and can move through the spaces of Medium\
    \ or smaller creatures. Each creature whose space the centaur enters is targeted\
    \ once by the following effect. Strength Saving Throw: DC 14. Failure: 7 (1d6\
    \ + 4) Bludgeoning damage, and the target has the [Prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
    \ condition."
  "name": "Trampling Charge (Recharge 5-6)"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/fey/token/centaur-trooper-xmm.webp"
```{ #statblock}


## Environment

forest, grassland, planar, feywild