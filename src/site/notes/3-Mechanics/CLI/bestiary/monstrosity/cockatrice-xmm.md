---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/monstrosity/cockatrice-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/1-2","ttrpg-cli/monster/environment/grassland","ttrpg-cli/monster/size/small","ttrpg-cli/monster/type/monstrosity"],"noteIcon":""}
---

# [Cockatrice](3-Mechanics\CLI\bestiary\monstrosity/cockatrice-xmm.md)
*Source: Monster Manual (2024) p. 75*  

Cockatrices often try to claim eye-catching structures—such as ruins and secluded farms—as roosts.

## Cockatrices

*Accursed Avians with the Power to Petrify*

- **Habitat.** Grassland  
- **Treasure.** None  

Cockatrices combine the features of irate roosters and starving reptiles. They petrify those they bite, their slightest peck turning their prey to stone.

```statblock
"name": "Cockatrice (XMM)"
"size": "Small"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "22"
"hit_dice": "5d6 + 5"
"stats":
- !!int "6"
- !!int "12"
- !!int "12"
- !!int "2"
- !!int "13"
- !!int "5"
"speed": "20 ft., fly 40 ft."
"condition_immunities": "[petrified](3-Mechanics/CLI/rules/conditions.md#Petrified)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": ""
"cr": "1/2"
"actions":
- "desc": "Melee Attack Roll: +3, reach 5 ft. Hit: 3 (1d4 + 1) Piercing damage.\
    \ If the target is a creature, it is subjected to the following effect. Constitution\
    \ Saving Throw: DC 11. 1st Failure: The target has the [Restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
    \ condition. The target repeats the save at the end of its next turn if it is\
    \ still [Restrained](3-Mechanics/CLI/rules/conditions.md#Restrained), ending the\
    \ effect on itself on a success. 2nd Failure: The target has the [Petrified](3-Mechanics/CLI/rules/conditions.md#Petrified)\
    \ condition, instead of the [Restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
    \ condition, for 24 hours."
  "name": "Petrifying Bite"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/cockatrice-xmm.webp"
```{ #statblock}


## Environment

grassland