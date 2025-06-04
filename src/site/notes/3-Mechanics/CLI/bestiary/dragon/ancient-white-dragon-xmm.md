---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/dragon/ancient-white-dragon-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/20","ttrpg-cli/monster/environment/arctic","ttrpg-cli/monster/size/gargantuan","ttrpg-cli/monster/type/dragon/chromatic"],"noteIcon":""}
---

# [Ancient White Dragon](3-Mechanics\CLI\bestiary\dragon/ancient-white-dragon-xmm.md)
*Source: Monster Manual (2024) p. 330*  

Like arctic storms, ancient white dragons threaten icy realms. They emerge from their frozen lairs to indulge their hungers for food or treasure, menacing other creatures with lethal cold. While they might ignore animals or small groups of polar wanderers, these dragons are quick to challenge other dragons and creatures wielding powerful magic, hoping to add their foes' skulls and magic items to their own hoards.

## White Dragons

*Dragons of Cold and Cruelty*

- **Habitat.** Arctic  
- **Treasure.** Arcana  

Among the most primal chromatic dragons, white dragons prioritize survival over all. Life is harsh and uncertain in the arctic expanses, glacial heights, and frozen seas where these dragons dwell. White dragons fiercely protect their territories, scouring the frigid regions for food and evidence of trespassers. Most white dragons ignore the plots of smaller creatures and other dragons, concerning themselves only with their own survival.

White dragons create lairs to defend themselves from other deadly arctic creatures and from dangerous natural conditions. Within these shelters, white dragons hoard testaments to their superiority, such as monstrous skulls, the gear of defeated rivals, and curiosities that capture their interest. To protect such treasure, white dragons coax ice to form over their hoards or sink their wealth in frigid pools. For white dragons, each piece of treasure embodies a victory—the details of which inflate as these dragons age.

### White Dragon Lairs

White dragons brood in bitterly cold lairs clawed from stone and ice.

```statblock
"name": "Ancient White Dragon (XMM)"
"size": "Gargantuan"
"type": "dragon"
"subtype": "chromatic"
"alignment": "Chaotic Evil"
"ac": !!int "20"
"hp": !!int "333"
"hit_dice": "18d20 + 144"
"stats":
- !!int "26"
- !!int "10"
- !!int "26"
- !!int "10"
- !!int "13"
- !!int "18"
"speed": "40 ft., burrow 40 ft., fly 80 ft., swim 40 ft."
"saves":
  "Dexterity": !!int "6"
  "Wisdom": !!int "7"
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "13"
"damage_immunities": "cold"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 23"
"languages": "Common, Draconic"
"cr": "20"
"traits":
- "desc": "The dragon casts [Fear](3-Mechanics/CLI/spells/fear-xphb.md), requiring\
    \ no Material components and using Charisma as the spellcasting ability (spell\
    \ save DC 18). The dragon can't take this action again until the start of its\
    \ next turn.\n"
  "name": "Frightful Presence"
- "desc": "The dragon can move across and climb icy surfaces without needing to make\
    \ an ability check. Additionally, [Difficult Terrain](3-Mechanics/CLI/rules/variant-rules/difficult-terrain-xphb.md)\
    \ composed of ice or snow doesn't cost it extra movement."
  "name": "Ice Walk"
- "desc": "If the dragon fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (4/Day, or 5/Day in Lair)"
"actions":
- "desc": "The dragon makes three Rend attacks."
  "name": "Multiattack"
- "desc": "Melee Attack Roll: +14, reach 15 ft. Hit: 17 (2d8 + 8) Slashing\
    \ damage plus 7 (2d6) Cold damage."
  "name": "Rend"
- "desc": "Constitution Saving Throw: DC 22, each creature in a 90-foot [Cone](3-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md).\
    \ Failure: 63 (14d8) Cold damage. Success: Half damage."
  "name": "Cold Breath (Recharge 5-6)"
"legendary_actions":
- "desc": "Constitution Saving Throw: DC 20, each creature in a 30-foot-radius [Sphere](3-Mechanics/CLI/rules/variant-rules/sphere-area-of-effect-xphb.md)\
    \ centered on a point the dragon can see within 120 feet. Failure: 14 (4d6)\
    \ Cold damage, and the target's [Speed](3-Mechanics/CLI/rules/variant-rules/speed-xphb.md)\
    \ is 0 until the end of the target's next turn. Failure or Success: The dragon\
    \ can't take this action again until the start of its next turn."
  "name": "Freezing Burst"
- "desc": "The dragon moves up to half its [Speed](3-Mechanics/CLI/rules/variant-rules/speed-xphb.md),\
    \ and it makes one Rend attack."
  "name": "Pounce"
"regional_effects":
- "desc": "The region containing an adult or ancient white dragon's lair is affected\
    \ by its presence, creating the following effects:"
  "name": ""
- "desc": "- Frigid Cold. The area within 1 mile of the lair is an area of [extreme\
    \ cold](3-Mechanics/CLI/traps-hazards/extreme-cold-xdmg.md). Any water in that\
    \ area is [frigid water](3-Mechanics/CLI/traps-hazards/frigid-water-xdmg.md).\
    \ See the \"Dungeon Master's Guide\" for rules on extreme cold and frigid water.\
    \  \n- Glacial Gloom. The area within 1 mile of the lair is [Lightly Obscured](3-Mechanics/CLI/rules/variant-rules/lightly-obscured-xphb.md)\
    \ by chilly fog. Whenever a creature other than the dragon or one of its allies\
    \ finishes a [Long Rest](3-Mechanics/CLI/rules/variant-rules/long-rest-xphb.md)\
    \ in that area, that creature must succeed on a DC 15 Constitution saving throw\
    \ or have its [Speed](3-Mechanics/CLI/rules/variant-rules/speed-xphb.md) reduced\
    \ by 10 feet for 1 hour.  "
  "name": ""
- "desc": "If the dragon dies or moves its lair elsewhere, these effects end immediately."
  "name": ""
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/dragon/token/ancient-white-dragon-xmm.webp"
```{ #statblock}


## Environment

arctic