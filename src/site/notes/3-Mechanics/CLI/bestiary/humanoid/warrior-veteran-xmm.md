---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/humanoid/warrior-veteran-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/3","ttrpg-cli/monster/environment/any","ttrpg-cli/monster/size/small-or-medium","ttrpg-cli/monster/type/humanoid"],"noteIcon":""}
---

# [Warrior Veteran](3-Mechanics\CLI\bestiary\humanoid/warrior-veteran-xmm.md)
*Source: Monster Manual (2024) p. 320*  

Warrior veterans have participated in numerous battles and can hold their own against lesser rivals and monsters.

## Warriors

*Soldiers and Scrappers*

- **Habitat.** Any  
- **Treasure.** Armaments  

Warriors are professionals who make a living through their prowess in battle. They might be skilled in using a variety of tactics or trained to take advantage of unusual battlefields. Warriors often work together, whether in armies or in teams with deliberate goals.

Roll on or choose a result from the Warrior Roles table to inspire the creation of different sorts of warriors.

**Warrior Roles**

`dice: [](warrior-veteran-xmm.md#^warrior-roles)`

| dice: 1d10 | The Warrior Is... |
|------------|-------------------|
| 1 | A bodyguard who protects a noble. |
| 2 | A cavalry officer with an unusual steed. |
| 3 | A crusader who fights for a divine cause. |
| 4 | A duelist who claims to be unbeatable. |
| 5 | A gate guard who asks nonsensical questions. |
| 6 | A grizzled veteran who trains new recruits. |
| 7 | A hunter skilled at slaying specific monsters. |
| 8 | A retired general who is weary of battle. |
| 9 | A volunteer with a homemade weapon. |
| 10 | A young mercenary trying to prove their skill. |{ #warrior-roles}


> [!quote] A quote from Minsc, Hero of Baldur's Gate  
> 
> Make way, evil! I'm armed to the teeth and packing a hamster!


```statblock
"name": "Warrior Veteran (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral"
"ac": !!int "17"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"stats":
- !!int "16"
- !!int "13"
- !!int "14"
- !!int "10"
- !!int "11"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "5"
  "Perception": !!int "2"
"senses": "passive Perception 12"
"languages": "Common plus one other language"
"cr": "3"
"actions":
- "desc": "The warrior makes two Greatsword or Heavy Crossbow attacks."
  "name": "Multiattack"
- "desc": "Melee Attack Roll: +5, reach 5 ft. Hit: 10 (2d6 + 3) Slashing damage."
  "name": "Greatsword"
- "desc": "Ranged Attack Roll: +3, range 100/400 ft. Hit: 12 (2d10 + 1) Piercing\
    \ damage."
  "name": "Heavy Crossbow"
"reactions":
- "desc": "Trigger: The warrior is hit by a melee attack roll while holding a weapon.\
    \ _Response:_ The warrior adds 2 to its AC against that attack, possibly causing\
    \ it to miss."
  "name": "Parry"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/warrior-veteran-xmm.webp"
```{ #statblock}


## Environment

any