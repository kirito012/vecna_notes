---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/dragon/white-dragon-wyrmling-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/2","ttrpg-cli/monster/environment/arctic","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/dragon/chromatic"],"noteIcon":""}
---

# [White Dragon Wyrmling](3-Mechanics\CLI\bestiary\dragon/white-dragon-wyrmling-xmm.md)
*Source: Monster Manual (2024) p. 328*  

White dragon wyrmlings usually head off on their own soon after hatching. While the cold means little to these creatures, food is scarce in arctic realms, and predators there are merciless. Most white dragon wyrmlings survive by scavenging, hunting opportunistically, and quickly fleeing foes—including other white dragons.

## White Dragons

*Dragons of Cold and Cruelty*

- **Habitat.** Arctic  
- **Treasure.** Arcana  

Among the most primal chromatic dragons, white dragons prioritize survival over all. Life is harsh and uncertain in the arctic expanses, glacial heights, and frozen seas where these dragons dwell. White dragons fiercely protect their territories, scouring the frigid regions for food and evidence of trespassers. Most white dragons ignore the plots of smaller creatures and other dragons, concerning themselves only with their own survival.

White dragons create lairs to defend themselves from other deadly arctic creatures and from dangerous natural conditions. Within these shelters, white dragons hoard testaments to their superiority, such as monstrous skulls, the gear of defeated rivals, and curiosities that capture their interest. To protect such treasure, white dragons coax ice to form over their hoards or sink their wealth in frigid pools. For white dragons, each piece of treasure embodies a victory—the details of which inflate as these dragons age.

### White Dragon Lairs

White dragons brood in bitterly cold lairs clawed from stone and ice.

```statblock
"name": "White Dragon Wyrmling (XMM)"
"size": "Medium"
"type": "dragon"
"subtype": "chromatic"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"hp": !!int "32"
"hit_dice": "5d8 + 10"
"stats":
- !!int "14"
- !!int "10"
- !!int "14"
- !!int "5"
- !!int "10"
- !!int "11"
"speed": "30 ft., burrow 15 ft., fly 60 ft., swim 30 ft."
"saves":
  "Dexterity": !!int "2"
  "Wisdom": !!int "2"
"skillsaves":
  "Stealth": !!int "2"
  "Perception": !!int "4"
"damage_immunities": "cold"
"senses": "blindsight 10 ft., darkvision 60 ft., passive Perception 14"
"languages": "Draconic"
"cr": "2"
"traits":
- "desc": "The dragon can move across and climb icy surfaces without needing to make\
    \ an ability check. Additionally, [Difficult Terrain](3-Mechanics/CLI/rules/variant-rules/difficult-terrain-xphb.md)\
    \ composed of ice or snow doesn't cost it extra movement."
  "name": "Ice Walk"
"actions":
- "desc": "The dragon makes two Rend attacks."
  "name": "Multiattack"
- "desc": "Melee Attack Roll: +4, reach 5 ft. Hit: 6 (1d8 + 2) Slashing damage\
    \ plus 2 (1d4) Cold damage."
  "name": "Rend"
- "desc": "Constitution Saving Throw: DC 12, each creature in a 15-foot [Cone](3-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md).\
    \ Failure: 22 (5d8) Cold damage. Success: Half damage."
  "name": "Cold Breath (Recharge 5-6)"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/dragon/token/white-dragon-wyrmling-xmm.webp"
```{ #statblock}


## Environment

arctic