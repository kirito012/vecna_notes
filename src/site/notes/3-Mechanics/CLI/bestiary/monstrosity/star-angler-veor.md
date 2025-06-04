---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/monstrosity/star-angler-veor/","tags":["ttrpg-cli/compendium/src/5e/veor","ttrpg-cli/monster/cr/8","ttrpg-cli/monster/size/large","ttrpg-cli/monster/type/monstrosity"],"noteIcon":""}
---

# [Star Angler](3-Mechanics\CLI\bestiary\monstrosity/star-angler-veor.md)
*Source: Vecna: Eve of Ruin p. 237*  

Distantly related to scavvers, star anglers are astral predators that resemble hulking, golden anglerfish with iridescent fins and tails. A star angler lacks eyes, and its hide is dotted with bioluminescent specks, allowing it to easily blend into the vast expanse of the Astral Plane. A star angler's signature lure emits an enchanting glow that has pulled many Wildspace explorers to their demises.

```statblock
"name": "Star Angler (VEoR)"
"size": "Large"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "119"
"hit_dice": "14d10 + 42"
"stats":
- !!int "21"
- !!int "15"
- !!int "17"
- !!int "3"
- !!int "14"
- !!int "6"
"speed": "0 ft., fly 40 ft."
"skillsaves":
  "Stealth": !!int "8"
  "Perception": !!int "5"
"senses": "blindsight 120 ft. (can't see beyond this radius), passive Perception 15"
"languages": ""
"cr": "8"
"traits":
- "desc": "If the star angler is subjected to an effect that allows it to make a saving\
    \ throw to take only half damage, it instead takes no damage if it succeeds on\
    \ the saving throw and only half damage if it fails."
  "name": "Avoidance"
- "desc": "The star angler's lure sheds bright light in a 30-foot radius and dim light\
    \ for an additional 30 feet."
  "name": "Illumination"
"actions":
- "desc": "The star angler makes three Bite attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 16 (2d10\
    \ + 5) piercing damage."
  "name": "Bite"
"bonus_actions":
- "desc": "The star angler's lure flares with enchanting starlight, targeting one\
    \ creature the star angler can see within 120 feet of itself. The target must\
    \ succeed on a DC 13 Wisdom saving throw or have the [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
    \ condition until the start of the star angler's next turn. While [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
    \ in this way, the target has the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
    \ condition and must use its movement on its turn to move directly toward the\
    \ star angler; a [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed) target\
    \ doesn't avoid opportunity attacks, but it does avoid damaging terrain. A target\
    \ can be [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed) by only one star\
    \ angler at a time."
  "name": "Lure Charm"
"source":
- "VEoR"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/star-angler-veor.webp"
```
^statblock