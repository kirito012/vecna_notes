---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/elemental/merfolk-wavebender-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/6","ttrpg-cli/monster/environment/coastal","ttrpg-cli/monster/environment/underwater","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/elemental"],"noteIcon":""}
---

# [Merfolk Wavebender](3-Mechanics\CLI\bestiary\elemental/merfolk-wavebender-xmm.md)
*Source: Monster Manual (2024) p. 209*  

These merfolk mages use magic to manipulate water, storms, and sea creatures to aid them.

## Merfolk

*Protectors and Explorers of the Seas*

- **Habitat.** Coastal, Underwater  
- **Treasure.** Individual  

Beneath the waves dwell merfolk, mysterious creatures that merge the features of humans and sea creatures. Some are curious about land dwellers, while others view them with suspicion.

```statblock
"name": "Merfolk Wavebender (XMM)"
"size": "Medium"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "14"
"hp": !!int "97"
"hit_dice": "15d8 + 30"
"stats":
- !!int "10"
- !!int "18"
- !!int "14"
- !!int "13"
- !!int "19"
- !!int "15"
"speed": "10 ft., swim 40 ft."
"saves":
  "Charisma": !!int "5"
  "Dexterity": !!int "7"
  "Wisdom": !!int "7"
  "Constitution": !!int "5"
"skillsaves":
  "Perception": !!int "7"
"damage_resistances": "cold"
"senses": "passive Perception 17"
"languages": "Common, Primordial (Aquan)"
"cr": "6"
"traits":
- "desc": "The merfolk casts one of the following spells, requiring no Material components\
    \ and using Wisdom as the spellcasting ability (spell save DC 15):\n\nAt will:\
    \ [Elementalism](3-Mechanics/CLI/spells/elementalism-xphb.md), [Light](3-Mechanics/CLI/spells/light-xphb.md)\n\
    \n1/day each: [Control Water](3-Mechanics/CLI/spells/control-water-xphb.md),\
    \ [Create or Destroy Water](3-Mechanics/CLI/spells/create-or-destroy-water-xphb.md)"
  "name": "Spellcasting"
- "desc": "The merfolk can breathe air and water."
  "name": "Amphibious"
"actions":
- "desc": "The merfolk makes two Aquatic Burst attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Attack Roll: +7, reach 5 ft. or range 60 ft. Hit:\
    \ 20 (3d10 + 4) Cold damage. If the target is a Large or smaller creature, it\
    \ has the [Prone](3-Mechanics/CLI/rules/conditions.md#Prone) condition."
  "name": "Aquatic Burst"
"reactions":
- "desc": "Trigger: An enemy the merfolk can see enters a space within 5 feet of the\
    \ merfolk. _Response—_Strength Saving Throw: DC 15, the triggering enemy. Failure:\
    \ 14 (4d6) Cold damage. If the target is Large or smaller, it is pushed up to\
    \ 30 feet straight away from the merfolk by conjured water."
  "name": "Watery Rebuke"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/elemental/token/merfolk-wavebender-xmm.webp"
```{ #statblock}


## Environment

coastal, underwater