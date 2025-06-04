---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/dragon/adult-white-dragon-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/13","ttrpg-cli/monster/environment/arctic","ttrpg-cli/monster/size/huge","ttrpg-cli/monster/type/dragon/chromatic"],"noteIcon":""}
---

# [Adult White Dragon](3-Mechanics\CLI\bestiary\dragon/adult-white-dragon-xmm.md)
*Source: Monster Manual (2024) p. 329*  

Adult white dragons claim large territories and are often the mightiest predators in those lands. While some lurk in their lairs for months, others regularly soar over their domains. When they spot something moving on the ice, they might swoop down to feed or extort food and offerings from sapient creatures.

## White Dragons

*Dragons of Cold and Cruelty*

- **Habitat.** Arctic  
- **Treasure.** Arcana  

Among the most primal chromatic dragons, white dragons prioritize survival over all. Life is harsh and uncertain in the arctic expanses, glacial heights, and frozen seas where these dragons dwell. White dragons fiercely protect their territories, scouring the frigid regions for food and evidence of trespassers. Most white dragons ignore the plots of smaller creatures and other dragons, concerning themselves only with their own survival.

White dragons create lairs to defend themselves from other deadly arctic creatures and from dangerous natural conditions. Within these shelters, white dragons hoard testaments to their superiority, such as monstrous skulls, the gear of defeated rivals, and curiosities that capture their interest. To protect such treasure, white dragons coax ice to form over their hoards or sink their wealth in frigid pools. For white dragons, each piece of treasure embodies a victory—the details of which inflate as these dragons age.

### White Dragon Lairs

White dragons brood in bitterly cold lairs clawed from stone and ice.

```statblock
"name": "Adult White Dragon (XMM)"
"size": "Huge"
"type": "dragon"
"subtype": "chromatic"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"hp": !!int "200"
"hit_dice": "16d12 + 96"
"stats":
- !!int "22"
- !!int "10"
- !!int "22"
- !!int "8"
- !!int "12"
- !!int "12"
"speed": "40 ft., burrow 30 ft., fly 80 ft., swim 40 ft."
"saves":
  "Dexterity": !!int "5"
  "Wisdom": !!int "6"
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "11"
"damage_immunities": "cold"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 21"
"languages": "Common, Draconic"
"cr": "13"
"traits":
- "desc": "The dragon casts [Fear](3-Mechanics/CLI/spells/fear-xphb.md), requiring\
    \ no Material components and using Charisma as the spellcasting ability (spell\
    \ save DC 14). The dragon can't take this action again until the start of its\
    \ next turn.\n"
  "name": "Frightful Presence"
- "desc": "The dragon can move across and climb icy surfaces without needing to make\
    \ an ability check. Additionally, [Difficult Terrain](3-Mechanics/CLI/rules/variant-rules/difficult-terrain-xphb.md)\
    \ composed of ice or snow doesn't cost it extra movement."
  "name": "Ice Walk"
- "desc": "If the dragon fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day, or 4/Day in Lair)"
"actions":
- "desc": "The dragon makes three Rend attacks."
  "name": "Multiattack"
- "desc": "Melee Attack Roll: +11, reach 10 ft. Hit: 13 (2d6 + 6) Slashing\
    \ damage plus 4 (1d8) Cold damage."
  "name": "Rend"
- "desc": "Constitution Saving Throw: DC 19, each creature in a 60-foot [Cone](3-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md).\
    \ Failure: 54 (12d8) Cold damage. Success: Half damage."
  "name": "Cold Breath (Recharge 5-6)"
"legendary_actions":
- "desc": "Constitution Saving Throw: DC 14, each creature in a 30-foot-radius [Sphere](3-Mechanics/CLI/rules/variant-rules/sphere-area-of-effect-xphb.md)\
    \ centered on a point the dragon can see within 120 feet. Failure: 7 (2d6)\
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
"image": "3-Mechanics/CLI/bestiary/dragon/token/adult-white-dragon-xmm.webp"
```{ #statblock}


## Environment

arctic