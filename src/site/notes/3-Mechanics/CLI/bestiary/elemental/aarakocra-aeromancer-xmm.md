---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/elemental/aarakocra-aeromancer-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/4","ttrpg-cli/monster/environment/air","ttrpg-cli/monster/environment/mountain","ttrpg-cli/monster/environment/planar","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/elemental"],"noteIcon":""}
---

# [Aarakocra Aeromancer](3-Mechanics\CLI\bestiary\elemental/aarakocra-aeromancer-xmm.md)
*Source: Monster Manual (2024) p. 10*  

Aarakocra aeromancers control magical winds from the endless storms of the Elemental Plane of Air.

## Aarakocra

*Winged Guardians of the Sky*

- **Habitat.** Mountain, Planar (Elemental Plane of Air)  
- **Treasure.** Implements, Individual  

Aarakocra are birdlike folk who soar the skies of countless worlds and the endless expanses of the Elemental Plane of Air. They often resemble avians common to the lands where they dwell; some resemble hawks or condors, while others appear similar to hummingbirds or archaeopteryxes. In many lands, aarakocra tell of their ancient heroics resisting the wicked Queen of Chaos alongside the mysterious Wind Dukes of Aaqa.

```statblock
"name": "Aarakocra Aeromancer (XMM)"
"size": "Medium"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "16"
"hp": !!int "66"
"hit_dice": "12d8 + 12"
"stats":
- !!int "10"
- !!int "16"
- !!int "12"
- !!int "13"
- !!int "17"
- !!int "12"
"speed": "20 ft., fly 50 ft."
"saves":
  "Dexterity": !!int "5"
  "Wisdom": !!int "5"
"skillsaves":
  "Nature": !!int "5"
  "Perception": !!int "7"
  "Arcana": !!int "3"
"senses": "passive Perception 17"
"languages": "Aarakocra, Primordial (Auran)"
"cr": "4"
"traits":
- "desc": "The aarakocra casts one of the following spells, requiring no Material\
    \ components and using Wisdom as the spellcasting ability (spell save DC 13):\n\
    \nAt will: [Elementalism](3-Mechanics/CLI/spells/elementalism-xphb.md), [Gust\
    \ of Wind](3-Mechanics/CLI/spells/gust-of-wind-xphb.md), [Mage Hand](3-Mechanics/CLI/spells/mage-hand-xphb.md),\
    \ [Message](3-Mechanics/CLI/spells/message-xphb.md)\n\n1/day: [Lightning Bolt](3-Mechanics/CLI/spells/lightning-bolt-xphb.md)"
  "name": "Spellcasting"
- "desc": "The aarakocra casts [Feather Fall](3-Mechanics/CLI/spells/feather-fall-xphb.md)\
    \ in response to that spell's trigger, using the same spellcasting ability as\
    \ Spellcasting.\n\n1/day: [Feather Fall](3-Mechanics/CLI/spells/feather-fall-xphb.md)"
  "name": "Feather Fall (1/Day)"
"actions":
- "desc": "The aarakocra makes two Wind Staff attacks, and it can use Spellcasting\
    \ to cast [Gust of Wind](3-Mechanics/CLI/spells/gust-of-wind-xphb.md)."
  "name": "Multiattack"
- "desc": "Melee or Ranged Attack Roll: +5, reach 5 ft. or range 120 ft. Hit:\
    \ 7 (1d8 + 3) Bludgeoning damage plus 11 (2d10) Lightning damage."
  "name": "Wind Staff"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/elemental/token/aarakocra-aeromancer-xmm.webp"
```{ #statblock}


## Environment

mountain, planar, air