---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/humanoid/inquisitor-of-the-tome-vrgr/","tags":["ttrpg-cli/compendium/src/5e/vrgr","ttrpg-cli/monster/cr/8","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/humanoid"],"noteIcon":""}
---

# [Inquisitor of the Tome](3-Mechanics\CLI\bestiary\humanoid/inquisitor-of-the-tome-vrgr.md)
*Source: Van Richten's Guide to Ravenloft p. 249, Vecna: Eve of Ruin*  

"Evil lurks everywhere. With our minds, we will unearth it, we will plumb its depths, and we will annihilate it." With those words, the psychically gifted priest Ulmed founded the Ulmist Inquisition, an order of psionic inquisitors that seeks to discover the wickedness hiding in people's souls.

In the days before Count Strahd von Zarovich became the first vampire, Strahd thundered across the lands with Ulmed. Their mission was clear: to destroy the infernal powers that had corrupted the world and to ensure that those powers never rose again. Strahd, Ulmed, and their companions hunted Fiends, Undead, Aberrations, and other supernatural threats and were tireless foes of cults like the priests of Osybus. When Strahd fell into darkness, Ulmed was heartbroken at his friend's transformation and changed the inquisition's mission. Instead of focusing on hunting monsters, it would also hunt the seeds of evil that can corrupt a person.

Ulmed and his friends Cosima, Ansel, and Tristian organized the inquisition into three orders, with each one specializing in a type of psionic power. The Order of Cosima harnessed the Mind Fire—their name for the fire of thought that blazes within each person's mind. They used that power to read thoughts, reshape memories, and dominate the recalcitrant. The inquisitors in the Order of Ansel subjected themselves to harsh asceticism in an effort to use psionic energy to empower their own bodies. They succeeded and became the martial arm of the inquisition, represented by a sword. Finally, the Order of Tristian endeavored to use intellect to alter the environment through telekinetic force, and the order's members became the inquisition's scholars, represented by a tome.

Today the inquisition rules the city of Malitain, a vast city-state to the north of Barovia's original site, and the inquisition sends its members throughout the multiverse, seeking to thwart the work of malevolent cults, otherworldly horrors, and the malice of mortals. The zeal of the inquisitors in this work has caused them to be a source of terror in many communities, where folk fear that an overzealous inquisitor might be as great a monster as the fiends the inquisitors originally hunted.

```statblock
"name": "Inquisitor of the Tome (VRGR)"
"size": "Medium"
"type": "humanoid"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "77"
"hit_dice": "14d8 + 14"
"stats":
- !!int "10"
- !!int "12"
- !!int "12"
- !!int "19"
- !!int "16"
- !!int "15"
"speed": "30 ft."
"saves":
  "Charisma": !!int "5"
  "Wisdom": !!int "6"
  "Intelligence": !!int "7"
"skillsaves":
  "Nature": !!int "7"
  "Religion": !!int "10"
  "History": !!int "7"
  "Arcana": !!int "10"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)"
"senses": "truesight 30 ft., passive Perception 13"
"languages": "any four languages, telepathy 120 ft."
"cr": "8"
"traits":
- "desc": "The inquisitor casts one of the following spells, requiring no components\
    \ and using Intelligence as the spellcasting ability (spell save DC 15):\n\nAt\
    \ will: [detect magic](3-Mechanics/CLI/spells/detect-magic.md), [dispel magic](3-Mechanics/CLI/spells/dispel-magic.md),\
    \ [levitate](3-Mechanics/CLI/spells/levitate.md), [mage armor](3-Mechanics/CLI/spells/mage-armor.md),\
    \ [mage hand](3-Mechanics/CLI/spells/mage-hand.md), [sending](3-Mechanics/CLI/spells/sending.md)\n\
    \n1/day each: [Otiluke's resilient sphere](3-Mechanics/CLI/spells/otilukes-resilient-sphere.md),\
    \ [telekinesis](3-Mechanics/CLI/spells/telekinesis.md)"
  "name": "Innate Spellcasting (Psionics)"
"actions":
- "desc": "The inquisitor attacks twice."
  "name": "Multiattack"
- "desc": "Ranged Spell Attack: +7 to hit, range 120 ft., one target. Hit: 22\
    \ (4d8 + 4) force damage, and if the target is a Large or smaller creature, the\
    \ inquisitor can push it up to 10 feet away."
  "name": "Force Bolt"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) slashing damage, or 9 (1d10 + 4) if used with two hands, plus 18 (4d8)\
    \ force damage."
  "name": "Silver Longsword"
- "desc": "Each creature in a 20-foot-radius sphere centered on a point the inquisitor\
    \ can see within 120 feet of it must succeed on a DC 15 Constitution saving throw\
    \ or take 31 (6d8 + 4) force damage and be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
    \ and moved to the unoccupied space closest to the sphere's center. Large and\
    \ smaller objects that aren't being worn or carried in the sphere automatically\
    \ take the damage and are similarly moved."
  "name": "Implode (Recharge 4-6)"
"reactions":
- "desc": "In response to being hit by an attack roll, the inquisitor increases its\
    \ AC by 4 against the attack. If this causes the attack to miss, the attacker\
    \ is hit by the attack instead."
  "name": "Telekinetic Deflection"
"source":
- "VRGR"
- "VEoR"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/inquisitor-of-the-tome-vrgr.webp"
```
^statblock