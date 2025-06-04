---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/elemental/azer-pyromancer-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/6","ttrpg-cli/monster/environment/fire","ttrpg-cli/monster/environment/mountain","ttrpg-cli/monster/environment/planar","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/elemental"],"noteIcon":""}
---

# [Azer Pyromancer](3-Mechanics\CLI\bestiary\elemental/azer-pyromancer-xmm.md)
*Source: Monster Manual (2024) p. 25*  

Azer pyromancers conjure flames from the Elemental Plane of Fire to defend themselves and stoke magical forges.

## Azers

*Fiery Smiths of Living Metal*

- **Habitat.** Mountain, Planar (Elemental Plane of Fire)  
- **Treasure.** Armaments, Individual  

Azers are living bronze folk who work the primal elements of creation to craft weapons and magical wonders among the multiverse's mightiest infernos.

```statblock
"name": "Azer Pyromancer (XMM)"
"size": "Medium"
"type": "elemental"
"alignment": "Lawful Neutral"
"ac": !!int "18"
"hp": !!int "97"
"hit_dice": "13d8 + 39"
"stats":
- !!int "15"
- !!int "14"
- !!int "16"
- !!int "12"
- !!int "18"
- !!int "13"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "7"
  "Constitution": !!int "6"
"skillsaves":
  "Perception": !!int "7"
  "Arcana": !!int "4"
"damage_immunities": "fire, poison"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "passive Perception 17"
"languages": "Primordial (Ignan)"
"cr": "6"
"traits":
- "desc": "The azer casts one of the following spells, requiring no Material components\
    \ and using Wisdom as the spellcasting ability (spell save DC 15):\n\nAt will:\
    \ [Elementalism](3-Mechanics/CLI/spells/elementalism-xphb.md), [Mage Hand](3-Mechanics/CLI/spells/mage-hand-xphb.md)\n\
    \n1/day: [Fireball](3-Mechanics/CLI/spells/fireball-xphb.md)"
  "name": "Spellcasting"
- "desc": "The azer casts [Hellish Rebuke](3-Mechanics/CLI/spells/hellish-rebuke-xphb.md)\
    \ in response to that spell's trigger, using the same spellcasting ability as\
    \ Spellcasting.\n\n2/day: [Hellish Rebuke](3-Mechanics/CLI/spells/hellish-rebuke-xphb.md)"
  "name": "Hellish Rebuke (2/Day)"
- "desc": "At the end of each of the azer's turns, each creature of the azer's choice\
    \ in a 5-foot [Emanation](3-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md)\
    \ originating from the azer takes 11 (2d10) Fire damage unless the azer has\
    \ the [Incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated) condition."
  "name": "Fire Aura"
- "desc": "The azer sheds [Bright Light](3-Mechanics/CLI/rules/variant-rules/bright-light-xphb.md)\
    \ in a 10-foot radius and [Dim Light](3-Mechanics/CLI/rules/variant-rules/dim-light-xphb.md)\
    \ for an additional 10 feet."
  "name": "Illumination"
"actions":
- "desc": "The azer makes two Flame Burst attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Attack Roll: +7, reach 5 ft. or range 120 ft. Hit:\
    \ 15 (2d10 + 4) Fire damage."
  "name": "Flame Burst"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/elemental/token/azer-pyromancer-xmm.webp"
```{ #statblock}


## Environment

mountain, planar, fire