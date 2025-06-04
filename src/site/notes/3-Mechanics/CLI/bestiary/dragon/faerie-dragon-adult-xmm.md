---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/dragon/faerie-dragon-adult-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/2","ttrpg-cli/monster/environment/forest","ttrpg-cli/monster/size/tiny","ttrpg-cli/monster/type/dragon"],"noteIcon":""}
---

# [Faerie Dragon Adult](3-Mechanics\CLI\bestiary\dragon/faerie-dragon-adult-xmm.md)
*Source: Monster Manual (2024) p. 117*  

The pranks of faerie dragon adults tend to lead others to people in need or wrongs to be righted.

## Faerie Dragons

*Whimsical Draconic Tricksters*

- **Habitat.** Forest  
- **Treasure.** Implements  

Faerie dragons are cat-size pranksters with draconic features, butterfly-like wings, and scales of warm hues as youths and cool hues as adults.

```statblock
"name": "Faerie Dragon Adult (XMM)"
"size": "Tiny"
"type": "dragon"
"alignment": "Chaotic Good"
"ac": !!int "15"
"hp": !!int "35"
"hit_dice": "10d4 + 10"
"stats":
- !!int "3"
- !!int "20"
- !!int "13"
- !!int "12"
- !!int "12"
- !!int "14"
"speed": "10 ft., fly 60 ft."
"skillsaves":
  "Stealth": !!int "7"
  "Perception": !!int "3"
  "Arcana": !!int "4"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Draconic, Sylvan; telepathy 60 ft. (faerie dragons only)"
"cr": "2"
"traits":
- "desc": "The dragon casts one of the following spells, requiring no Material components\
    \ and using Charisma as the spellcasting ability (spell save DC 13):\n\nAt will:\
    \ [Dancing Lights](3-Mechanics/CLI/spells/dancing-lights-xphb.md), [Mage Hand](3-Mechanics/CLI/spells/mage-hand-xphb.md),\
    \ [Minor Illusion](3-Mechanics/CLI/spells/minor-illusion-xphb.md)\n\n1/day each:\
    \ [Hallucinatory Terrain](3-Mechanics/CLI/spells/hallucinatory-terrain-xphb.md),\
    \ [Polymorph](3-Mechanics/CLI/spells/polymorph-xphb.md)"
  "name": "Spellcasting"
- "desc": "The dragon casts [Greater Invisibility](3-Mechanics/CLI/spells/greater-invisibility-xphb.md)\
    \ on itself, requiring no spell components and using the same spellcasting ability\
    \ as Spellcasting.\n\nAt will: [Greater Invisibility](3-Mechanics/CLI/spells/greater-invisibility-xphb.md)"
  "name": "Superior Invisibility"
- "desc": "The dragon has [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md)\
    \ on saving throws against spells and other magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Melee Attack Roll: +7, reach 5 ft. Hit: 7 (1d4 + 5) Piercing damage\
    \ plus 3 (1d6) Psychic damage."
  "name": "Bite"
- "desc": "Wisdom Saving Throw: DC 13, each creature in a 15-foot [Cone](3-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md).\
    \ Failure: The target has the [Incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
    \ condition and repeats the save at the end of each of its turns, ending the effect\
    \ on itself on a success. After 1 minute, it succeeds automatically. While [Incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated),\
    \ the target uses all its movement on each of its turns to move in a random direction."
  "name": "Euphoria Breath (Recharge 5-6)"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/dragon/token/faerie-dragon-adult-xmm.webp"
```{ #statblock}


## Environment

forest