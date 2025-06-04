---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/elemental/dao-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/11","ttrpg-cli/monster/environment/earth","ttrpg-cli/monster/environment/planar","ttrpg-cli/monster/environment/underdark","ttrpg-cli/monster/size/large","ttrpg-cli/monster/type/elemental/genie"],"noteIcon":""}
---

# [Dao](3-Mechanics\CLI\bestiary\elemental/dao-xmm.md)
*Source: Monster Manual (2024) p. 89*  

## Dao

*Genie of the Earth*

- **Habitat.** Planar (Elemental Plane of Earth), Underdark  
- **Treasure.** Implements  

Genies of minerals and gemstones, dao embody the resolve of rock. Using innate magic, they move through the earth unimpeded, exploring depths inaccessible to most. Dao delight in the treasures of the earth, whether raw gemstones, jewelry crafted from pure metals, or wondrous fossils. In exchange for such treasures, dao might reveal underground mysteries, such as paths through the Underdark, buried ruins, or whole subterranean realms.

Many dao call the Elemental Plane of Earth home. There, they create cities that glitter with treasure. Among these realms is the labyrinthine expanse called the Great Dismal Delve or the Sevenfold Mazework, which protects the City of Jewels, the Iron Crucible, and the Strait of Magnets.

> [!quote] A quote from Gundren Rockseeker, Dwarf Treasure Hunter  
> 
> On the Elemental Plane of Earth, galaxies of gemstones twinkle over vaults of treasure. If dao are there, so is wealth worth hunting.


```statblock
"name": "Dao (XMM)"
"size": "Large"
"type": "elemental"
"subtype": "genie"
"alignment": "Neutral"
"ac": !!int "18"
"hp": !!int "200"
"hit_dice": "16d10 + 112"
"stats":
- !!int "23"
- !!int "12"
- !!int "24"
- !!int "12"
- !!int "13"
- !!int "18"
"speed": "30 ft., burrow 30 ft., fly 30 ft. (hover)"
"saves":
  "Dexterity": !!int "5"
  "Wisdom": !!int "5"
"condition_immunities": "[petrified](3-Mechanics/CLI/rules/conditions.md#Petrified)"
"senses": "darkvision 120 ft., passive Perception 11"
"languages": "Primordial (Terran)"
"cr": "11"
"traits":
- "desc": "The dao casts one of the following spells, requiring no Material components\
    \ and using Charisma as the spellcasting ability (spell save DC 16):\n\nAt will:\
    \ [Detect Evil and Good](3-Mechanics/CLI/spells/detect-evil-and-good-xphb.md),\
    \ [Detect Magic](3-Mechanics/CLI/spells/detect-magic-xphb.md), [Stone Shape](3-Mechanics/CLI/spells/stone-shape-xphb.md)\n\
    \n1/day each: [Gaseous Form](3-Mechanics/CLI/spells/gaseous-form-xphb.md),\
    \ [Invisibility](3-Mechanics/CLI/spells/invisibility-xphb.md), [Move Earth](3-Mechanics/CLI/spells/move-earth-xphb.md),\
    \ [Passwall](3-Mechanics/CLI/spells/passwall-xphb.md), [Plane Shift](3-Mechanics/CLI/spells/plane-shift-xphb.md),\
    \ [Tongues](3-Mechanics/CLI/spells/tongues-xphb.md), [Wall of Stone](3-Mechanics/CLI/spells/wall-of-stone-xphb.md)"
  "name": "Spellcasting"
- "desc": "The dao can burrow through nonmagical, unworked earth and stone. While\
    \ doing so, the dao doesn't disturb the material it moves through."
  "name": "Earth Glide"
- "desc": "If the dao dies outside the Elemental Plane of Earth, its body dissolves\
    \ into dirt, and it gains a new body in 1d4 days, reviving with all its [Hit\
    \ Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) somewhere on\
    \ the Plane of Earth."
  "name": "Elemental Restoration"
- "desc": "The dao has [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md)\
    \ on saving throws against spells and other magical effects."
  "name": "Magic Resistance"
- "desc": "The dao has a 30 percent chance of knowing the [Wish](3-Mechanics/CLI/spells/wish-xphb.md)\
    \ spell. If the dao knows it, the dao can cast it only on behalf of a non-genie\
    \ creature who communicates a wish in a way the dao can understand. If the dao\
    \ casts the spell for the creature, the dao suffers none of the spell's stress.\
    \ Once the dao has cast it three times, the dao can't do so again for 365 days."
  "name": "Wishes"
"actions":
- "desc": "The dao makes three Earthen Maul attacks or two Earth Burst attacks."
  "name": "Multiattack"
- "desc": "Melee Attack Roll: +10, reach 5 ft. Hit: 20 (4d6 + 6) Bludgeoning\
    \ damage. If the target is a Large or smaller creature, it has the [Prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
    \ condition."
  "name": "Earthen Maul"
- "desc": "Ranged Attack Roll: +10, range 120 ft. Hit: 15 (2d8 + 6) Bludgeoning\
    \ damage. Hit or Miss: Earth explodes from the target's space, creating the\
    \ following effect. Dexterity Saving Throw: DC 16, each creature in a 10-foot\
    \ [Emanation](3-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md)\
    \ originating from and including the target. Failure: 10 (3d6) Thunder damage."
  "name": "Earth Burst"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/elemental/token/dao-xmm.webp"
```{ #statblock}


## Environment

planar, earth, underdark