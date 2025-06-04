---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/dragon/young-white-dragon-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/6","ttrpg-cli/monster/environment/arctic","ttrpg-cli/monster/size/large","ttrpg-cli/monster/type/dragon/chromatic"],"noteIcon":""}
---

# [Young White Dragon](3-Mechanics\CLI\bestiary\dragon/young-white-dragon-xmm.md)
*Source: Monster Manual (2024) p. 328*  

Young white dragons defend their hunting grounds from rivals. In some cases, kobolds and groups of humanoids might offer food and treasure to young white dragons, attempting to keep the dragons satiated and less likely to prey on their communities.

## White Dragons

*Dragons of Cold and Cruelty*

- **Habitat.** Arctic  
- **Treasure.** Arcana  

Among the most primal chromatic dragons, white dragons prioritize survival over all. Life is harsh and uncertain in the arctic expanses, glacial heights, and frozen seas where these dragons dwell. White dragons fiercely protect their territories, scouring the frigid regions for food and evidence of trespassers. Most white dragons ignore the plots of smaller creatures and other dragons, concerning themselves only with their own survival.

White dragons create lairs to defend themselves from other deadly arctic creatures and from dangerous natural conditions. Within these shelters, white dragons hoard testaments to their superiority, such as monstrous skulls, the gear of defeated rivals, and curiosities that capture their interest. To protect such treasure, white dragons coax ice to form over their hoards or sink their wealth in frigid pools. For white dragons, each piece of treasure embodies a victory—the details of which inflate as these dragons age.

### White Dragon Lairs

White dragons brood in bitterly cold lairs clawed from stone and ice.

```statblock
"name": "Young White Dragon (XMM)"
"size": "Large"
"type": "dragon"
"subtype": "chromatic"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"hp": !!int "123"
"hit_dice": "13d10 + 52"
"stats":
- !!int "18"
- !!int "10"
- !!int "18"
- !!int "6"
- !!int "11"
- !!int "12"
"speed": "40 ft., burrow 20 ft., fly 80 ft., swim 40 ft."
"saves":
  "Dexterity": !!int "3"
  "Wisdom": !!int "3"
"skillsaves":
  "Stealth": !!int "3"
  "Perception": !!int "6"
"damage_immunities": "cold"
"senses": "blindsight 30 ft., darkvision 120 ft., passive Perception 16"
"languages": "Common, Draconic"
"cr": "6"
"traits":
- "desc": "The dragon can move across and climb icy surfaces without needing to make\
    \ an ability check. Additionally, [Difficult Terrain](3-Mechanics/CLI/rules/variant-rules/difficult-terrain-xphb.md)\
    \ composed of ice or snow doesn't cost it extra movement."
  "name": "Ice Walk"
"actions":
- "desc": "The dragon makes three Rend attacks."
  "name": "Multiattack"
- "desc": "Melee Attack Roll: +7, reach 10 ft. Hit: 9 (2d4 + 4) Slashing damage\
    \ plus 2 (1d4) Cold damage."
  "name": "Rend"
- "desc": "Constitution Saving Throw: DC 15, each creature in a 30-foot [Cone](3-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md).\
    \ Failure: 40 (9d8) Cold damage. Success: Half damage."
  "name": "Cold Breath (Recharge 5-6)"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/dragon/token/young-white-dragon-xmm.webp"
```{ #statblock}


## Environment

arctic