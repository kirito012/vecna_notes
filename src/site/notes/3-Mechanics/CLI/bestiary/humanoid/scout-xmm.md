---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/humanoid/scout-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/1-2","ttrpg-cli/monster/environment/any","ttrpg-cli/monster/size/small-or-medium","ttrpg-cli/monster/type/humanoid"],"noteIcon":""}
---

# [Scout](3-Mechanics\CLI\bestiary\humanoid/scout-xmm.md)
*Source: Monster Manual (2024) p. 270. Available in the Free Rules (2024)*  

Scouts are keen archers and acutely aware of their surroundings. They often know several regions particularly well and are familiar with local creatures, landmarks, and perils.

## Scouts

*Watchers and Wanderers*

- **Habitat.** Any  
- **Treasure.** Implements, Individual  

Scouts are warriors of the wilderness, trained in hunting and tracking. They might be explorers or trappers, or they could perform more martial roles as archers, bounty hunters, or outriders.

```statblock
"name": "Scout (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral"
"ac": !!int "13"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"stats":
- !!int "11"
- !!int "14"
- !!int "12"
- !!int "11"
- !!int "13"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Nature": !!int "4"
  "Stealth": !!int "6"
  "Perception": !!int "5"
  "Survival": !!int "5"
"senses": "passive Perception 15"
"languages": "Common plus one other language"
"cr": "1/2"
"actions":
- "desc": "The scout makes two attacks, using Shortsword and Longbow in any combination."
  "name": "Multiattack"
- "desc": "Melee Attack Roll: +4, reach 5 ft. Hit: 5 (1d6 + 2) Piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Attack Roll: +4, range 150/600 ft. Hit: 6 (1d8 + 2) Piercing\
    \ damage."
  "name": "Longbow"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/scout-xmm.webp"
```{ #statblock}


## Environment

any