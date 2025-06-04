---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/humanoid/performer-maestro-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/6","ttrpg-cli/monster/environment/any","ttrpg-cli/monster/size/small-or-medium","ttrpg-cli/monster/type/humanoid"],"noteIcon":""}
---

# [Performer Maestro](3-Mechanics\CLI\bestiary\humanoid/performer-maestro-xmm.md)
*Source: Monster Manual (2024) p. 237*  

Maestros are headlining performers who enjoy considerable renown. They might be theaters' marquee actors, astonishing daredevils, or jesters experienced at entertaining fickle royals. Some share their techniques with apprentices, while others jealously guard their secrets.

## Performers

*Artists and Entertainers*

- **Habitat.** Any  
- **Treasure.** Implements, Individual  

From royal courts to village squares, skilled entertainers hone their talents and delight audiences. Some travel far, sharing tales and demonstrating mysterious arts. Others serve in the courts and theaters of great nations, cultivating celebrity and navigating the whims of patrons. Many hone professional secrets and magical flourishes, striving to make their performances truly unforgettable.

Use the following list of entertainers and roles to inspire the performers in your adventures:

Acrobat

Actor

Aerialist

Animal trainer

Athlete

Burlesque artist

Busker

Circus performer

Comedian

Contortionist

Dancer

Daredevil

Jester

Juggler

Magician

Mentalist

Mime

Minstrel

Mourner

Oral historian

Poet

Puppeteer

Ritualist

Stage fighter

Storyteller

Throat singer

Town crier

Trick rider

Vocalist

Wrestler

> [!quote] A quote from Tindal, Carnival Barker  
> 
> Welcome, one! Welcome, all! Welcome to the short, and welcome to the tall! Welcome angels, welcome fiends, welcome to all from walks between! Welcome to the Carnival!


```statblock
"name": "Performer Maestro (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral"
"ac": !!int "18"
"hp": !!int "110"
"hit_dice": "17d8 + 34"
"stats":
- !!int "12"
- !!int "18"
- !!int "14"
- !!int "13"
- !!int "14"
- !!int "19"
"speed": "30 ft."
"saves":
  "Charisma": !!int "7"
  "Dexterity": !!int "7"
"skillsaves":
  "Athletics": !!int "4"
  "Stealth": !!int "7"
  "Perception": !!int "5"
  "Performance": !!int "10"
  "Acrobatics": !!int "10"
"senses": "passive Perception 15"
"languages": "Common plus one other language"
"cr": "6"
"traits":
- "desc": "The performer casts one of the following spells, requiring no Material\
    \ components and using Charisma as the spellcasting ability (spell save DC 15):\n\
    \nAt will: [Minor Illusion](3-Mechanics/CLI/spells/minor-illusion-xphb.md),\
    \ [Prestidigitation](3-Mechanics/CLI/spells/prestidigitation-xphb.md)\n\n1/day:\
    \ [Tasha's Hideous Laughter](3-Mechanics/CLI/spells/tashas-hideous-laughter-xphb.md)\
    \ (level 3 version)"
  "name": "Spellcasting"
"actions":
- "desc": "The performer makes three Rapier attacks."
  "name": "Multiattack"
- "desc": "Melee Attack Roll: +7, reach 5 ft. Hit: 8 (1d8 + 4) Piercing damage\
    \ plus 7 (2d6) Psychic damage."
  "name": "Rapier"
- "desc": "Wisdom Saving Throw: DC 15, each creature in a 20-foot-radius [Sphere](3-Mechanics/CLI/rules/variant-rules/sphere-area-of-effect-xphb.md)\
    \ centered on a point within 120 feet. Failure: 20 (3d10 + 4) Psychic damage,\
    \ and the target has the [Charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
    \ condition until the end of the performer's next turn. Success: Half damage\
    \ only."
  "name": "Beguiling Song"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/performer-maestro-xmm.webp"
```{ #statblock}


## Environment

any