---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/monstrosity/ssurran-defiler-bam/","tags":["ttrpg-cli/compendium/src/5e/bam","ttrpg-cli/monster/cr/3","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/monstrosity/lizardfolk"],"noteIcon":""}
---

# [Ssurran Defiler](3-Mechanics\CLI\bestiary\monstrosity/ssurran-defiler-bam.md)
*Source: Boo's Astral Menagerie p. 58, Light of Xaryxis*  

Ssurran defilers can lay waste to the plant life around them and draw vital energy at the same time from other creatures that are caught in the area.

```statblock
"name": "Ssurran Defiler (BAM)"
"size": "Medium"
"type": "monstrosity"
"subtype": "lizardfolk"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "natural armor, intellect fortress"
"hp": !!int "52"
"hit_dice": "7d8 + 21"
"stats":
- !!int "13"
- !!int "12"
- !!int "16"
- !!int "15"
- !!int "15"
- !!int "7"
"speed": "30 ft., swim 30 ft."
"saves":
  "Intelligence": !!int "4"
  "Constitution": !!int "5"
"skillsaves":
  "Stealth": !!int "3"
  "Perception": !!int "4"
  "Arcana": !!int "4"
  "Survival": !!int "4"
"damage_resistances": "necrotic"
"senses": "passive Perception 14"
"languages": "Draconic"
"cr": "3"
"traits":
- "desc": "The ssurran casts one of the following spells, requiring no spell components\
    \ and using Intelligence as the spellcasting ability:\n\nAt will: [mage hand](3-Mechanics/CLI/spells/mage-hand-xphb.md)\
    \ (the hand is invisible)\n\n1/day: [invisibility](3-Mechanics/CLI/spells/invisibility-xphb.md)\
    \ (self only)"
  "name": "Spellcasting (Psionics)"
- "desc": "The ssurran can hold its breath for 15 minutes."
  "name": "Hold Breath"
- "desc": "The ssurran's AC includes its Intelligence modifier."
  "name": "Intellect Fortress"
"actions":
- "desc": "The ssurran makes two Claw attacks and uses Defile (if available)."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) slashing damage plus 4 (1d8) necrotic damage."
  "name": "Claw"
- "desc": "Ordinary vegetation within 10 feet of the ssurran withers and dies. In\
    \ addition, each creature within 10 feet of the ssurran must make a DC 11 Constitution\
    \ saving throw, taking 22 (4d10) necrotic damage on a failed save, or half as\
    \ much damage on a successful one. The ssurran regains 5 (1d10) hit points for\
    \ each creature that fails the saving throw."
  "name": "Defile (Recharge 6)"
"source":
- "BAM"
- "LoX"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/ssurran-defiler-bam.webp"
```
^statblock