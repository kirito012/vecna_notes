---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/beast/giant-hyena-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/1","ttrpg-cli/monster/environment/desert","ttrpg-cli/monster/environment/forest","ttrpg-cli/monster/environment/grassland","ttrpg-cli/monster/environment/hill","ttrpg-cli/monster/size/large","ttrpg-cli/monster/type/beast"],"noteIcon":""}
---

# [Giant Hyena](3-Mechanics\CLI\bestiary\beast/giant-hyena-xmm.md)
*Source: Monster Manual (2024) p. 357*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](3-Mechanics/CLI/bestiary/beast/panther-xmm.md) stat block can also represent a mountain lion, while the [Giant Goat](3-Mechanics/CLI/bestiary/beast/giant-goat-xmm.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Giant Hyena (XMM)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "45"
"hit_dice": "6d10 + 12"
"stats":
- !!int "16"
- !!int "14"
- !!int "14"
- !!int "2"
- !!int "12"
- !!int "7"
"speed": "50 ft."
"skillsaves":
  "Perception": !!int "3"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": ""
"cr": "1"
"actions":
- "desc": "Melee Attack Roll: +5, reach 5 ft. Hit: 10 (2d6 + 3) Piercing damage."
  "name": "Bite"
"bonus_actions":
- "desc": "Immediately after dealing damage to a creature that was already [Bloodied](3-Mechanics/CLI/rules/variant-rules/bloodied-xphb.md),\
    \ the hyena can move up to half its [Speed](3-Mechanics/CLI/rules/variant-rules/speed-xphb.md),\
    \ and it makes one Bite attack."
  "name": "Rampage (1/Day)"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/beast/token/giant-hyena-xmm.webp"
```{ #statblock}


## Environment

desert, forest, grassland, hill