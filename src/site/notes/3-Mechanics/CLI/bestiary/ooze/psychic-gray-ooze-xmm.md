---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/ooze/psychic-gray-ooze-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/1","ttrpg-cli/monster/environment/underdark","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/ooze"],"noteIcon":""}
---

# [Psychic Gray Ooze](3-Mechanics\CLI\bestiary\ooze/psychic-gray-ooze-xmm.md)
*Source: Monster Manual (2024) p. 151*  

Psychic gray oozes exhibit violent psionic abilities. These oozes sometimes result from failed attempts to summon or create creatures linked to the Elemental Plane of Earth, like gargoyles or homunculi.

## Gray Oozes

*Hungry Slimes and Magical Failures*

- **Habitat.** Underdark  
- **Treasure.** None  

Gray oozes are predatory, corrosive slimes that blend in with stony surroundings.

```statblock
"name": "Psychic Gray Ooze (XMM)"
"size": "Medium"
"type": "ooze"
"alignment": "Unaligned"
"ac": !!int "9"
"hp": !!int "37"
"hit_dice": "5d8 + 15"
"stats":
- !!int "12"
- !!int "8"
- !!int "16"
- !!int "10"
- !!int "6"
- !!int "2"
"speed": "10 ft., climb 10 ft."
"skillsaves":
  "Stealth": !!int "3"
"damage_resistances": "acid, cold, fire, psychic"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled),\
  \ [prone](3-Mechanics/CLI/rules/conditions.md#Prone), [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)"
"senses": "blindsight 60 ft., passive Perception 8"
"languages": ""
"cr": "1"
"traits":
- "desc": "The ooze can move through a space as narrow as 1 inch without expending\
    \ extra movement to do so."
  "name": "Amorphous"
"actions":
- "desc": "Melee Attack Roll: +3, reach 5 ft. Hit: 11 (3d6 + 1) Acid damage,\
    \ and the target has [Disadvantage](3-Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md)\
    \ on Intelligence saving throws until the end of the ooze's next turn."
  "name": "Pseudopod"
- "desc": "Intelligence Saving Throw: DC 10, one creature the ooze can see within\
    \ 60 feet. Failure: 13 (3d8) Psychic damage."
  "name": "Psychic Crush"
"reactions":
- "desc": "Trigger: The ooze fails a saving throw against a spell or another magical\
    \ effect created by a creature. _Response:_ The triggering creature takes 3 (1d6)\
    \ Psychic damage."
  "name": "Mind Corrosion"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/ooze/token/psychic-gray-ooze-xmm.webp"
```{ #statblock}


## Environment

underdark