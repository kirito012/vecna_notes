---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/beast/constrictor-snake-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/1-4","ttrpg-cli/monster/environment/desert","ttrpg-cli/monster/environment/forest","ttrpg-cli/monster/environment/swamp","ttrpg-cli/monster/environment/underwater","ttrpg-cli/monster/size/large","ttrpg-cli/monster/type/beast"],"noteIcon":""}
---

# [Constrictor Snake](3-Mechanics\CLI\bestiary\beast/constrictor-snake-xmm.md)
*Source: Monster Manual (2024) p. 351, Player's Handbook (2024) p. 348*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](3-Mechanics/CLI/bestiary/beast/panther-xmm.md) stat block can also represent a mountain lion, while the [Giant Goat](3-Mechanics/CLI/bestiary/beast/giant-goat-xmm.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Constrictor Snake (XMM)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "13"
"hit_dice": "2d10 + 2"
"stats":
- !!int "15"
- !!int "14"
- !!int "12"
- !!int "1"
- !!int "10"
- !!int "3"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "2"
"senses": "blindsight 10 ft., passive Perception 12"
"languages": ""
"cr": "1/4"
"actions":
- "desc": "Melee Attack Roll: +4, reach 5 ft. Hit: 6 (1d8 + 2) Piercing damage."
  "name": "Bite"
- "desc": "Strength Saving Throw: DC 12, one Medium or smaller creature the snake\
    \ can see within 5 feet. Failure: 7 (3d4) Bludgeoning damage, and the target\
    \ has the [Grappled](3-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape\
    \ DC 12)."
  "name": "Constrict"
"source":
- "XMM"
- "XPHB"
"image": "3-Mechanics/CLI/bestiary/beast/token/constrictor-snake-xmm.webp"
```{ #statblock}


## Environment

desert, forest, swamp, underwater