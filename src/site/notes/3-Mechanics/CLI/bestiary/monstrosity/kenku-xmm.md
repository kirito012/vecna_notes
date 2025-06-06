---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/monstrosity/kenku-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/1-4","ttrpg-cli/monster/environment/forest","ttrpg-cli/monster/environment/planar","ttrpg-cli/monster/environment/shadowfell","ttrpg-cli/monster/environment/urban","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/monstrosity"],"noteIcon":""}
---

# [Kenku](3-Mechanics\CLI\bestiary\monstrosity/kenku-xmm.md)
*Source: Monster Manual (2024) p. 183*  

## Kenku

*Flightless, Noise-Mimicking Avian*

- **Habitat.** Forest, Planar (Shadowfell), Urban  
- **Treasure.** Implements, Individual  

Kenku are birdlike folk who once soared the skies and sang enchanted songs, but a curse stole their wings and transformed their voices. Now kenku slip through the shadows of cities and the Shadowfell, trying to recover what they've lost. To some, this means seeking an end to their curse; others search for magic or contraptions to enable them to fly and sing again.

The curse affecting kenku allows them to vocally communicate only by mimicking sounds they've heard. Kenku can supernaturally re-create vast varieties of noises, from crying babies to running water and short phrases in others' voices. Cunning kenku use their mimicry to deceive foes, lure creatures into ambushes, and signal to allies.

```statblock
"name": "Kenku (XMM)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Neutral"
"ac": !!int "13"
"hp": !!int "13"
"hit_dice": "3d8"
"stats":
- !!int "10"
- !!int "16"
- !!int "10"
- !!int "11"
- !!int "10"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "4"
  "Stealth": !!int "5"
  "Perception": !!int "2"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Primordial (Auran)"
"cr": "1/4"
"traits":
- "desc": "The kenku casts [Faerie Fire](3-Mechanics/CLI/spells/faerie-fire-xphb.md),\
    \ using Intelligence as the spellcasting ability (spell save DC 10).\n"
  "name": "Eldritch Lantern (Recharge 4-6)"
- "desc": "The kenku can mimic any sounds it has heard, including voices. A creature\
    \ that hears the sounds can tell they are imitations with a successful DC 14 Wisdom\
    \ ([Insight](3-Mechanics/CLI/rules/skills.md#Insight)) check."
  "name": "Mimicry"
"actions":
- "desc": "Melee or Ranged Attack Roll: +5, reach 5 ft. or range 60 ft. Hit:\
    \ 6 (1d6 + 3) Necrotic damage. Hit or Miss: The blade magically returns to\
    \ the kenku's hand immediately after a ranged attack."
  "name": "Shadow Blade"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/kenku-xmm.webp"
```{ #statblock}


## Environment

forest, planar, shadowfell, urban