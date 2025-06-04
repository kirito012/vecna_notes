---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/construct/blade-scout-veor/","tags":["ttrpg-cli/compendium/src/5e/veor","ttrpg-cli/monster/cr/7","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/construct/warforged"],"noteIcon":""}
---

# [Blade Scout](3-Mechanics\CLI\bestiary\construct/blade-scout-veor.md)
*Source: Vecna: Eve of Ruin p. 209*  

Blade scouts are responsible for exploring and charting Mournland regions not yet claimed by the Lord of Blades' legions.

## Blades of Eberron

In the aftermath of Eberron's Last War, a warforged called the Lord of Blades rose to fill the power vacuum left in the devastated Mournland. The Lord of Blades' followers, known as blades, formed a cult of personality that deifies the Lord of Blades and preaches a bloody, jingoistic doctrine of warforged superiority. The primary tenet of the blades is that non-warforged on the continent of Khorvaire must be slaughtered.

```statblock
"name": "Blade Scout (VEoR)"
"size": "Medium"
"type": "construct"
"subtype": "warforged"
"alignment": "typically  Lawful Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "105"
"hit_dice": "14d8 + 42"
"stats":
- !!int "14"
- !!int "20"
- !!int "16"
- !!int "10"
- !!int "19"
- !!int "10"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "8"
  "Wisdom": !!int "7"
"skillsaves":
  "Stealth": !!int "8"
  "Perception": !!int "7"
  "Acrobatics": !!int "8"
"damage_resistances": "poison"
"condition_immunities": "[exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "passive Perception 17"
"languages": "Common"
"cr": "7"
"traits":
- "desc": "The scout has advantage on an attack roll against a creature if at least\
    \ one of the scout's allies is within 5 feet of the creature and the ally doesn't\
    \ have the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
    \ condition."
  "name": "Pack Tactics"
"actions":
- "desc": "The scout makes three Armblade or Bolt Launcher attacks. It can replace\
    \ one of the attacks with a use of Snare Trap."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 12 (2d6\
    \ + 5) slashing damage."
  "name": "Armblade"
- "desc": "Ranged Weapon Attack: +8 to hit, range 80/320 ft., one target. Hit:\
    \ 9 (1d8 + 5) piercing damage."
  "name": "Bolt Launcher"
- "desc": "The scout deploys a Tiny mechanical trap on a solid surface within 5 feet\
    \ of itself. The trap is hidden, requiring a successful DC 17 Intelligence ([Investigation](3-Mechanics/CLI/rules/skills.md#Investigation))\
    \ check to find. The trap lasts for 1 minute. Whenever an enemy enters a space\
    \ within 10 feet of the trap or starts its turn there, it must succeed on a DC\
    \ 16 Dexterity saving throw or take 21 (6d6) piercing damage and have the [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
    \ condition. A creature makes this saving throw only once per turn."
  "name": "Snare Trap (1/Day)"
"bonus_actions":
- "desc": "The scout moves up to its speed without provoking opportunity attacks."
  "name": "Dash"
"source":
- "VEoR"
"image": "3-Mechanics/CLI/bestiary/construct/token/blade-scout-veor.webp"
```
^statblock