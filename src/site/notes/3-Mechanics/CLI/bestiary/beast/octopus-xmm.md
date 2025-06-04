---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/beast/octopus-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/0","ttrpg-cli/monster/environment/underwater","ttrpg-cli/monster/size/small","ttrpg-cli/monster/type/beast"],"noteIcon":""}
---

# [Octopus](3-Mechanics\CLI\bestiary\beast/octopus-xmm.md)
*Source: Monster Manual (2024) p. 365, Player's Handbook (2024) p. 353*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](3-Mechanics/CLI/bestiary/beast/panther-xmm.md) stat block can also represent a mountain lion, while the [Giant Goat](3-Mechanics/CLI/bestiary/beast/giant-goat-xmm.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Octopus (XMM)"
"size": "Small"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "3"
"hit_dice": "1d6"
"stats":
- !!int "4"
- !!int "15"
- !!int "11"
- !!int "3"
- !!int "10"
- !!int "4"
"speed": "5 ft., swim 30 ft."
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "2"
"senses": "darkvision 30 ft., passive Perception 12"
"languages": ""
"cr": "0"
"traits":
- "desc": "The octopus can move through a space as narrow as 1 inch without expending\
    \ extra movement to do so."
  "name": "Compression"
- "desc": "The octopus can breathe only underwater."
  "name": "Water Breathing"
"actions":
- "desc": "Melee Attack Roll: +4, reach 5 ft. Hit: 1 Bludgeoning damage."
  "name": "Tentacles"
"reactions":
- "desc": "Trigger: A creature ends its turn within 5 feet of the octopus while underwater.\
    \ _Response:_ The octopus releases ink that fills a 5-foot [Cube](3-Mechanics/CLI/rules/variant-rules/cube-area-of-effect-xphb.md)\
    \ centered on itself, and the octopus moves up to its [Swim Speed](3-Mechanics/CLI/rules/variant-rules/swim-speed-xphb.md).\
    \ The [Cube](3-Mechanics/CLI/rules/variant-rules/cube-area-of-effect-xphb.md)\
    \ is [Heavily Obscured](3-Mechanics/CLI/rules/variant-rules/heavily-obscured-xphb.md)\
    \ for 1 minute or until a strong current or similar effect disperses the ink."
  "name": "Ink Cloud (1/Day)"
"source":
- "XMM"
- "XPHB"
"image": "3-Mechanics/CLI/bestiary/beast/token/octopus-xmm.webp"
```{ #statblock}


## Environment

underwater