---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/humanoid/noble-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/1-8","ttrpg-cli/monster/environment/any","ttrpg-cli/monster/size/small-or-medium","ttrpg-cli/monster/type/humanoid"],"noteIcon":""}
---

# [Noble](3-Mechanics\CLI\bestiary\humanoid/noble-xmm.md)
*Source: Monster Manual (2024) p. 227. Available in the Free Rules (2024)*  

A noble's social advantages typically grant the noble access to greater education and training than most common folk, while nobles' experience with business or politics makes many adept negotiators.

## Nobles

*Royals and Rich Folk*

- **Habitat.** Any  
- **Treasure.** Individual  

Nobles encompass a variety of people with social influence. They might be rulers, wealthy merchants, callous bureaucrats, or the idle elite.

```statblock
"name": "Noble (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral"
"ac": !!int "15"
"hp": !!int "9"
"hit_dice": "2d8"
"stats":
- !!int "11"
- !!int "12"
- !!int "11"
- !!int "12"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "5"
  "Insight": !!int "4"
  "Persuasion": !!int "5"
"senses": "passive Perception 12"
"languages": "Common plus two other languages"
"cr": "1/8"
"actions":
- "desc": "Melee Attack Roll: +3, reach 5 ft. Hit: 5 (1d8 + 1) Piercing damage."
  "name": "Rapier"
"reactions":
- "desc": "Trigger: The noble is hit by a melee attack roll while holding a weapon.\
    \ _Response:_ The noble adds 2 to its AC against that attack, possibly causing\
    \ it to miss."
  "name": "Parry"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/noble-xmm.webp"
```{ #statblock}


## Environment

any