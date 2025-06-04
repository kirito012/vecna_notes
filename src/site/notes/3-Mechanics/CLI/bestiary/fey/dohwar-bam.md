---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/fey/dohwar-bam/","tags":["ttrpg-cli/compendium/src/5e/bam","ttrpg-cli/monster/cr/0","ttrpg-cli/monster/size/small","ttrpg-cli/monster/type/fey"],"noteIcon":""}
---

# [Dohwar](3-Mechanics\CLI\bestiary\fey/dohwar-bam.md)
*Source: Boo's Astral Menagerie p. 19, Light of Xaryxis*  

Dohwars are short, pudgy, flightless avians that look and move like penguins. Dohwars migrate from the Feywild to Wildspace, where they are typically encountered. They conduct their affairs in secrecy, preferring to meet in dark alleys and out-of-the-way places even when their business isn't illegal or dangerous. They tend to dress in a garish mishmash of clothing, but many of them also shroud themselves in hooded cloaks.

The average dohwar stands 3 feet tall and has bright plumage matching a particular color in the rainbow spectrum. This color can change at unpredictable times in the dohwar's life, often in response to the dohwar experiencing an overwhelming emotion. Instead of wings, it has arms and tiny hands.

Dohwars prefer to communicate through a form of telepathy they call merging, in which two dohwars stay in mental contact while both are telepathically linked with a third creature.

```statblock
"name": "Dohwar (BAM)"
"size": "Small"
"type": "fey"
"alignment": "Any alignment"
"ac": !!int "11"
"hp": !!int "10"
"hit_dice": "3d6"
"stats":
- !!int "5"
- !!int "12"
- !!int "11"
- !!int "11"
- !!int "14"
- !!int "13"
"speed": "20 ft., swim 20 ft."
"saves":
  "Dexterity": !!int "3"
  "Wisdom": !!int "4"
"skillsaves":
  "Deception": !!int "3"
  "Insight": !!int "4"
  "Persuasion": !!int "3"
"senses": "passive Perception 12"
"languages": "Common, Dohwar, telepathy 30 ft. (see also Merging below)"
"cr": "0"
"traits":
- "desc": "The dohwar casts the following spell, requiring no spell components and\
    \ using Charisma as the spellcasting ability (spell save DC 11):\n\n3/day:\
    \ [detect thoughts](3-Mechanics/CLI/spells/detect-thoughts-xphb.md)"
  "name": "Spellcasting (Psionics)"
- "desc": "Two dohwars can have a telepathic conversation with each other and a third\
    \ willing creature of their choice, provided all three are within 30 feet of one\
    \ another."
  "name": "Merging"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 3 (1d4\
    \ + 1) piercing damage."
  "name": "Bite"
"source":
- "BAM"
- "LoX"
"image": "3-Mechanics/CLI/bestiary/fey/token/dohwar-bam.webp"
```
^statblock