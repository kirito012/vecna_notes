---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/monstrosity/thri-kreen-psion-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/8","ttrpg-cli/monster/environment/desert","ttrpg-cli/monster/environment/grassland","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/monstrosity"],"noteIcon":""}
---

# [Thri-kreen Psion](3-Mechanics\CLI\bestiary\monstrosity/thri-kreen-psion-xmm.md)
*Source: Monster Manual (2024) p. 306*  

Thri-kreen psions harness their psychic powers to avoid danger and manipulate objects from afar.

## Thri-kreen

*Mantid Psychics and Scavengers*

- **Habitat.** Desert, Grassland  
- **Treasure.** Armaments  

Thri-kreen are mantis-like wanderers who harness their innate camouflage and psychic abilities to survive. Different groups of thri-kreen have distinct carapaces, from the rocky shades of desert dwellers to the vibrant hues of those living in verdant lands. While their language has a distinctly insectile quality, thri-kreen often use telepathy to communicate, and groups can rapidly share a wealth of detailed information without making a sound.

> [!quote] A quote from Ka'Cha, Thri-kreen Knowledge Hunter  
> 
> I would tell you now the tale of the first Ka'Cha, the first thri-kreen who knew and taught the truth: that the clutch is all.


```statblock
"name": "Thri-kreen Psion (XMM)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Neutral"
"ac": !!int "16"
"hp": !!int "149"
"hit_dice": "23d8 + 46"
"stats":
- !!int "18"
- !!int "15"
- !!int "14"
- !!int "19"
- !!int "12"
- !!int "11"
"speed": "40 ft., fly 20 ft. (hover)"
"saves":
  "Dexterity": !!int "5"
  "Intelligence": !!int "7"
  "Strength": !!int "7"
  "Constitution": !!int "5"
"skillsaves":
  "Stealth": !!int "8"
  "Perception": !!int "4"
"damage_resistances": "psychic"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Thri-kreen; telepathy 120 ft."
"cr": "8"
"traits":
- "desc": "The thri-kreen casts one of the following spells, requiring no spell components\
    \ and using Intelligence as the spellcasting ability (spell save DC 15):\n\nAt\
    \ will: [Mage Hand](3-Mechanics/CLI/spells/mage-hand-xphb.md) (the hand is Invisible)\n\
    \n1/day each: [Detect Thoughts](3-Mechanics/CLI/spells/detect-thoughts-xphb.md),\
    \ [Sending](3-Mechanics/CLI/spells/sending-xphb.md), [Synaptic Static](3-Mechanics/CLI/spells/synaptic-static-xphb.md)"
  "name": "Spellcasting"
"actions":
- "desc": "The thri-kreen makes three Psionic Lance attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Attack Roll: +7, reach 10 ft. or range 120 ft. Hit:\
    \ 18 (4d6 + 4) Psychic damage."
  "name": "Psionic Lance"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/thri-kreen-psion-xmm.webp"
```{ #statblock}


## Environment

desert, grassland