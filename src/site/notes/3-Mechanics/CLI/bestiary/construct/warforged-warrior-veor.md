---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/construct/warforged-warrior-veor/","tags":["ttrpg-cli/compendium/src/5e/veor","ttrpg-cli/monster/cr/1","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/construct"],"noteIcon":""}
---

# [Warforged Warrior](3-Mechanics\CLI\bestiary\construct/warforged-warrior-veor.md)
*Source: Vecna: Eve of Ruin p. 238*  

Warforged warriors are formed from wood and steel, then magically imbued with life and sentience. They were created to fight in the Last War on the continent of Khorvaire in Eberron. In the aftermath of that conflict, they struggle to understand their place in the world.

```statblock
"name": "Warforged Warrior (VEoR)"
"size": "Medium"
"type": "construct"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "30"
"hit_dice": "4d8 + 12"
"stats":
- !!int "16"
- !!int "12"
- !!int "16"
- !!int "10"
- !!int "14"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "5"
  "Perception": !!int "4"
  "Survival": !!int "4"
"damage_resistances": "poison"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "passive Perception 14"
"languages": "Common"
"cr": "1"
"actions":
- "desc": "The warforged makes two Armblade attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Armblade"
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 30/120\
    \ ft., one target. Hit: 6 (1d6 + 3) piercing damage."
  "name": "Javelin"
"reactions":
- "desc": "When an attacker the warforged can see makes an attack roll against a creature\
    \ within 5 feet of the warforged, the warforged can impose disadvantage on the\
    \ attack roll."
  "name": "Protection"
"source":
- "VEoR"
"image": "3-Mechanics/CLI/bestiary/construct/token/warforged-warrior-veor.webp"
```
^statblock