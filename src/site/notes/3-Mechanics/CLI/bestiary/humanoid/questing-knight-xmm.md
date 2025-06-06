---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/humanoid/questing-knight-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/12","ttrpg-cli/monster/environment/any","ttrpg-cli/monster/size/small-or-medium","ttrpg-cli/monster/type/humanoid"],"noteIcon":""}
---

# [Questing Knight](3-Mechanics\CLI\bestiary\humanoid/questing-knight-xmm.md)
*Source: Monster Manual (2024) p. 184*  

Questing knights travel in pursuit of a cause, such as slaying a villain, defeating a monster, recovering an Artifact, or restoring their lost honor.

## Knights

*Battle Masters and Heroic Wanderers*

- **Habitat.** Any  
- **Treasure.** Armaments, Individual  

Knights are skilled warriors trained for war and tested in battle. Many serve the rulers of a realm, a religion, or an order devoted to a cause.

```statblock
"name": "Questing Knight (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral"
"ac": !!int "18"
"hp": !!int "202"
"hit_dice": "27d8 + 81"
"stats":
- !!int "20"
- !!int "16"
- !!int "16"
- !!int "11"
- !!int "12"
- !!int "18"
"speed": "30 ft."
"saves":
  "Charisma": !!int "8"
  "Wisdom": !!int "5"
  "Strength": !!int "9"
  "Constitution": !!int "7"
"skillsaves":
  "Athletics": !!int "9"
  "Perception": !!int "5"
  "Persuasion": !!int "8"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)"
"senses": "passive Perception 15"
"languages": "Common plus one other language"
"cr": "12"
"traits":
- "desc": "The knight casts one of the following spells, using Charisma as the spellcasting\
    \ ability (spell save DC 16):\n\n1/day each: [Daylight](3-Mechanics/CLI/spells/daylight-xphb.md),\
    \ [Dispel Evil and Good](3-Mechanics/CLI/spells/dispel-evil-and-good-xphb.md),\
    \ [Greater Restoration](3-Mechanics/CLI/spells/greater-restoration-xphb.md), [Phantom\
    \ Steed](3-Mechanics/CLI/spells/phantom-steed-xphb.md)"
  "name": "Spellcasting"
- "desc": "Creatures of the knight's choice in a 30-foot [Emanation](3-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md)\
    \ originating from it have [Immunity](3-Mechanics/CLI/rules/variant-rules/immunity-xphb.md)\
    \ to the [Charmed](3-Mechanics/CLI/rules/conditions.md#Charmed) and [Frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
    \ conditions while there."
  "name": "Aura of Bravery"
"actions":
- "desc": "The knight makes three attacks, using Greatsword or Longbow in any combination."
  "name": "Multiattack"
- "desc": "Melee Attack Roll: +9, reach 5 ft. Hit: 12 (2d6 + 5) Slashing damage\
    \ plus 22 (5d8) Radiant damage."
  "name": "Greatsword"
- "desc": "Ranged Attack Roll: +7, range 150/600 ft. Hit: 12 (2d8 + 3) Piercing\
    \ damage plus 22 (5d8) Radiant damage."
  "name": "Longbow"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/questing-knight-xmm.webp"
```{ #statblock}


## Environment

any