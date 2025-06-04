---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/dragon/ancient-green-dragon-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/22","ttrpg-cli/monster/environment/forest","ttrpg-cli/monster/size/gargantuan","ttrpg-cli/monster/type/dragon/chromatic"],"noteIcon":""}
---

# [Ancient Green Dragon](3-Mechanics\CLI\bestiary\dragon/ancient-green-dragon-xmm.md)
*Source: Monster Manual (2024) p. 154*  

Ancient green dragons are creatures of legend, rarely seen by their servants or foes. Via magic and well-hidden agents, these dragons stoke suspicion between allies and undermine noble works. As bonds fray, the dragons reap rewards of greater wealth and control. Eventually the ambitions of ancient green dragons stretch beyond their territories as they seek control over empires, planar realms, or death itself.

## Green Dragons

*Dragons of Deceit and Derision*

- **Habitat.** Forest  
- **Treasure.** Arcana  

From forbidden forest depths, green dragons whisper evils into the world and manipulate the lives of those who listen. Elusive, conniving, and egotistical, these chromatic dragons patiently prey on the fears of shorter-lived beings, corrupting and isolating them. Green dragons might lurk amid labyrinthine wildernesses for centuries without revealing themselves; even their most devoted followers might know them only as the voice of the woodlands or a whisper in their dreams.

Despite their might, most green dragons disdain physical violence, viewing combat as servants' work and preferring to trick foes into dangerous or exploitative scenarios. These dragons collect "baubles" that embody their webs of manipulation and serve as tools of extortion, such as compromising documents, family heirlooms, and sentimental treasures.

### Green Dragon Lairs

Green dragons lair in ancient forests, often shaping stands of massive trees into compounds of interwoven branches, hollow trunks, and caverns amid mighty roots. They might also dwell amid forested ruins, particularly the former homes of those they've conquered.

```statblock
"name": "Ancient Green Dragon (XMM)"
"size": "Gargantuan"
"type": "dragon"
"subtype": "chromatic"
"alignment": "Lawful Evil"
"ac": !!int "21"
"hp": !!int "402"
"hit_dice": "23d20 + 161"
"stats":
- !!int "27"
- !!int "12"
- !!int "25"
- !!int "20"
- !!int "17"
- !!int "22"
"speed": "40 ft., fly 80 ft., swim 40 ft."
"saves":
  "Dexterity": !!int "8"
  "Wisdom": !!int "10"
"skillsaves":
  "Deception": !!int "13"
  "Stealth": !!int "8"
  "Perception": !!int "17"
  "Persuasion": !!int "13"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 27"
"languages": "Common, Draconic"
"cr": "22"
"traits":
- "desc": "The dragon casts one of the following spells, requiring no Material components\
    \ and using Charisma as the spellcasting ability (spell save DC 21):\n\nAt will:\
    \ [Detect Magic](3-Mechanics/CLI/spells/detect-magic-xphb.md), [Mind Spike](3-Mechanics/CLI/spells/mind-spike-xphb.md)\
    \ (level 5 version)\n\n1/day each: [Geas](3-Mechanics/CLI/spells/geas-xphb.md),\
    \ [Modify Memory](3-Mechanics/CLI/spells/modify-memory-xphb.md)"
  "name": "Spellcasting"
- "desc": "The dragon can breathe air and water."
  "name": "Amphibious"
- "desc": "If the dragon fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (4/Day, or 5/Day in Lair)"
"actions":
- "desc": "The dragon makes three Rend attacks. It can replace one attack with a use\
    \ of Spellcasting to cast [Mind Spike](3-Mechanics/CLI/spells/mind-spike-xphb.md)\
    \ (level 5 version)."
  "name": "Multiattack"
- "desc": "Melee Attack Roll: +15, reach 15 ft. Hit: 17 (2d8 + 8) Slashing\
    \ damage plus 10 (3d6) Poison damage."
  "name": "Rend"
- "desc": "Constitution Saving Throw: DC 22, each creature in a 90-foot [Cone](3-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md).\
    \ Failure: 77 (22d6) Poison damage. Success: Half damage."
  "name": "Poison Breath (Recharge 5-6)"
"legendary_actions":
- "desc": "The dragon uses Spellcasting to cast [Mind Spike](3-Mechanics/CLI/spells/mind-spike-xphb.md)\
    \ (level 5 version)."
  "name": "Mind Invasion"
- "desc": "Constitution Saving Throw: DC 21, each creature in a 30-foot-radius [Sphere](3-Mechanics/CLI/rules/variant-rules/sphere-area-of-effect-xphb.md)\
    \ centered on a point the dragon can see within 90 feet. Failure: 17 (5d6)\
    \ Poison damage, and the target takes a -2 penalty to AC until the end of its\
    \ next turn. Failure or Success: The dragon can't take this action again until\
    \ the start of its next turn."
  "name": "Noxious Miasma"
- "desc": "The dragon moves up to half its [Speed](3-Mechanics/CLI/rules/variant-rules/speed-xphb.md),\
    \ and it makes one Rend attack."
  "name": "Pounce"
"regional_effects":
- "desc": "The region containing an adult or ancient green dragon's lair is warped\
    \ by its presence, creating the following effects:"
  "name": ""
- "desc": "- Beast Spies. Tiny Beasts magically gain the ability to understand\
    \ Draconic and can communicate telepathically with the dragon while within 1 mile\
    \ of the lair.  \n- Poisonous Thicket. Ordinary plants growing within 1 mile\
    \ of the lair poison the air around them. Whenever a creature other than the dragon\
    \ or its allies finishes a [Long Rest](3-Mechanics/CLI/rules/variant-rules/long-rest-xphb.md)\
    \ in that area, it must succeed on a DC 15 Constitution saving throw or have the\
    \ [Poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned) condition for 1 hour.\
    \  "
  "name": ""
- "desc": "If the dragon dies or moves its lair elsewhere, these effects end immediately."
  "name": ""
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/dragon/token/ancient-green-dragon-xmm.webp"
```{ #statblock}


## Environment

forest