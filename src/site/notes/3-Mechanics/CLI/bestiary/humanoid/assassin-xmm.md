---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/humanoid/assassin-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/8","ttrpg-cli/monster/environment/any","ttrpg-cli/monster/size/small-or-medium","ttrpg-cli/monster/type/humanoid"],"noteIcon":""}
---

# [Assassin](3-Mechanics\CLI\bestiary\humanoid/assassin-xmm.md)
*Source: Monster Manual (2024) p. 22*  

## Assassin

*Contract Killer*

- **Habitat.** Any  
- **Treasure.** Implements, Individual  

Assassins are professional killers skilled at stealthily approaching their victims and striking unseen. Most assassins kill for a reason, perhaps hiring themselves out to wealthy patrons or slaying for an unscrupulous cause. They use poisons and other deadly tools, and they might carry equipment to help them break into secure areas or avoid capture.

Many assassins adhere to a professional code or exhibit some signature quirk. Roll on or choose a result from the Assassin Modus Operandi table to inspire an assassin's distinctive habits.

**Assassin Modus Operandi**

`dice: [](assassin-xmm.md#^assassin-modus-operandi)`

| dice: 1d6 | The Assassin Is Infamous For... |
|-----------|---------------------------------|
| 1 | Arranging their victims in artful tableaux. |
| 2 | Hiding within large objects, such as suits of armor or hollow furnishings. |
| 3 | Leaving behind a signature item, such as a calling card, flower, seashell, or tooth. |
| 4 | Posing as celebrities, holy people, or servants. |
| 5 | Taking trophies from their victims. |
| 6 | Using poison with a distinctive color or smell. |{ #assassin-modus-operandi}


```statblock
"name": "Assassin (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral"
"ac": !!int "16"
"hp": !!int "97"
"hit_dice": "15d8 + 30"
"stats":
- !!int "11"
- !!int "18"
- !!int "14"
- !!int "16"
- !!int "11"
- !!int "10"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "7"
  "Intelligence": !!int "6"
"skillsaves":
  "Stealth": !!int "10"
  "Perception": !!int "6"
  "Acrobatics": !!int "7"
"damage_resistances": "poison"
"senses": "passive Perception 16"
"languages": "Common, Thieves' cant"
"cr": "8"
"traits":
- "desc": "If the assassin is subjected to an effect that allows it to make a Dexterity\
    \ saving throw to take only half damage, the assassin instead takes no damage\
    \ if it succeeds on the save and only half damage if it fails. It can't use this\
    \ trait if it has the [Incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
    \ condition."
  "name": "Evasion"
"actions":
- "desc": "The assassin makes three attacks, using Shortsword or Light Crossbow in\
    \ any combination."
  "name": "Multiattack"
- "desc": "Melee Attack Roll: +7, reach 5 ft. Hit: 7 (1d6 + 4) Piercing damage\
    \ plus 17 (5d6) Poison damage, and the target has the [Poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
    \ condition until the start of the assassin's next turn."
  "name": "Shortsword"
- "desc": "Ranged Attack Roll: +7, range 80/320 ft. Hit: 8 (1d8 + 4) Piercing\
    \ damage plus 21 (6d6) Poison damage."
  "name": "Light Crossbow"
"bonus_actions":
- "desc": "The assassin takes the Dash, Disengage, or Hide action."
  "name": "Cunning Action"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/assassin-xmm.webp"
```{ #statblock}


## Environment

any