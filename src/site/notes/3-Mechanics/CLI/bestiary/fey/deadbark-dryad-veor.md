---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/fey/deadbark-dryad-veor/","tags":["ttrpg-cli/compendium/src/5e/veor","ttrpg-cli/monster/cr/13","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/fey"],"noteIcon":""}
---

# [Deadbark Dryad](3-Mechanics\CLI\bestiary\fey/deadbark-dryad-veor.md)
*Source: Vecna: Eve of Ruin p. 216*  

When a dryad fails to protect its wilderness home from a great evil and is unable to forgive itself, the dryad might transform into a wicked Fey monster called a deadbark dryad. Such dryads relinquish any compassion they once felt for living beings and instead harbor hatred for anyone who dares to invade their rotted demesne.

The wilds around a deadbark dryad become malignant, souring into a swampy morass of stinging nettles and noxious muck. Deadbark dryads are immune to this toxic bog's deleterious effects.

A deadbark dryad is typically bound to the spot where it failed to protect its charge. When a dryad transforms into a deadbark dryad, it becomes stronger and more violent, and it typically gains a renewed dedication to protecting its now-fetid domain. Most deadbark dryads would rather fight to the death than allow any intrusion into their homes.

Deadbark dryads are most often found on Krynn, but occasionally they are found on other worlds where magic and trees are plentiful.

```statblock
"name": "Deadbark Dryad (VEoR)"
"size": "Medium"
"type": "fey"
"alignment": "typically  Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "187"
"hit_dice": "22d8 + 88"
"stats":
- !!int "17"
- !!int "16"
- !!int "18"
- !!int "11"
- !!int "16"
- !!int "18"
"speed": "30 ft."
"saves":
  "Charisma": !!int "9"
  "Constitution": !!int "9"
"skillsaves":
  "Stealth": !!int "8"
  "Perception": !!int "8"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 18"
"languages": "Elvish, Sylvan"
"cr": "13"
"traits":
- "desc": "The dryad casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 17):\n\nAt will:\
    \ [Druidcraft](3-Mechanics/CLI/spells/druidcraft.md)\n\n1/day: [Dispel Magic](3-Mechanics/CLI/spells/dispel-magic.md)\n\
    \n2/day each: [Pass without Trace](3-Mechanics/CLI/spells/pass-without-trace.md),\
    \ [Spike Growth](3-Mechanics/CLI/spells/spike-growth.md)"
  "name": "Spellcasting"
- "desc": "Difficult terrain composed of vegetation, such as foliage or thorns, doesn't\
    \ cost the dryad extra movement."
  "name": "Bramble Walk"
- "desc": "The dryad has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The dryad can communicate with Beasts and Plants as if they shared a language."
  "name": "Speak with Beasts and Plants"
"actions":
- "desc": "The dryad makes two Poisonous Thorn attacks and one Sapping Vine attack."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +8 to hit, reach 5 ft. or range 120 ft.,\
    \ one target. Hit: 13 (4d4 + 3) piercing damage plus 10 (3d6) poison damage.\
    \ If the target is a creature, it must succeed on a DC 17 Constitution saving\
    \ throw or have the [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned) condition\
    \ until the start of the dryad's next turn."
  "name": "Poisonous Thorn"
- "desc": "Melee Weapon Attack: +8 to hit, reach 30 ft., one target. Hit: The\
    \ target has the [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled) condition\
    \ (escape DC 16). Until the grapple ends, the target has the [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
    \ condition, and the dryad can't use the same vine on another target. A creature\
    \ [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained) in this way takes\
    \ 13 (3d8) necrotic damage at the start of its turn.\n\nThe dryad has six vines.\
    \ Each vine can be attacked (AC 20; 10 hit points; immunity to poison and psychic\
    \ damage). Destroying a vine deals no damage to the dryad, but any creature [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
    \ by that vine no longer has the [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
    \ condition. All vines immediately wither and disappear when the dryad is reduced\
    \ to 0 hit points."
  "name": "Sapping Vine"
"source":
- "VEoR"
"image": "3-Mechanics/CLI/bestiary/fey/token/deadbark-dryad-veor.webp"
```
^statblock