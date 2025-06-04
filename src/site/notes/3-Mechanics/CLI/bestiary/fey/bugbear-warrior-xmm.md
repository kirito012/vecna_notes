---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/fey/bugbear-warrior-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/1","ttrpg-cli/monster/environment/feywild","ttrpg-cli/monster/environment/forest","ttrpg-cli/monster/environment/grassland","ttrpg-cli/monster/environment/planar","ttrpg-cli/monster/environment/underdark","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/fey/goblinoid"],"noteIcon":""}
---

# [Bugbear Warrior](3-Mechanics\CLI\bestiary\fey/bugbear-warrior-xmm.md)
*Source: Monster Manual (2024) p. 62. Available in the Free Rules (2024)*  

Bugbear warriors serve those who offer them treasure, food, or the chance to hunt challenging prey.

## Bugbears

*Lurking Goblinoid Brutes*

- **Habitat.** Forest, Grassland, Planar (Feywild), Underdark  
- **Treasure.** Armaments, Individual  

Bugbears embody fear of the wilds and the menace of natural places. They're notoriously stealthy, and foes that venture into their territories often vanish without a trace.

```statblock
"name": "Bugbear Warrior (XMM)"
"size": "Medium"
"type": "fey"
"subtype": "goblinoid"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"stats":
- !!int "15"
- !!int "14"
- !!int "13"
- !!int "8"
- !!int "11"
- !!int "9"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "6"
  "Survival": !!int "2"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Goblin"
"cr": "1"
"traits":
- "desc": "The bugbear needn't spend extra movement to move a creature it is grappling."
  "name": "Abduct"
"actions":
- "desc": "Melee Attack Roll: +4, reach 10 ft. Hit: 9 (2d6 + 2) Bludgeoning\
    \ damage. If the target is a Medium or smaller creature, it has the [Grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
    \ condition (escape DC 12)."
  "name": "Grab"
- "desc": "Melee or Ranged Attack Roll: +4 (with [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md)\
    \ if the target is [Grappled](3-Mechanics/CLI/rules/conditions.md#Grappled) by\
    \ the bugbear), reach 10 ft. or range 20/60 ft. Hit: 9 (3d4 + 2) Bludgeoning\
    \ damage."
  "name": "Light Hammer"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/fey/token/bugbear-warrior-xmm.webp"
```{ #statblock}


## Environment

forest, grassland, planar, feywild, underdark