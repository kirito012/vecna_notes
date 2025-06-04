---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/humanoid/astral-elf-commander-bam/","tags":["ttrpg-cli/compendium/src/5e/bam","ttrpg-cli/monster/cr/7","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/humanoid"],"noteIcon":""}
---

# [Astral Elf Commander](3-Mechanics\CLI\bestiary\humanoid/astral-elf-commander-bam.md)
*Source: Boo's Astral Menagerie p. 12, Light of Xaryxis*  

An astral elf commander leads warriors into battle and usually has one or more spelljamming ships under their command. A commander channels the radiant energy of starlight through their weapons, and they can rescue warriors from a perilous situation by using their gods-given power of teleportation.

## Astral Elves

Long ago, some elves ventured to the Astral Plane to be closer to their gods. There, they ceased to age and could exist indefinitely without sustenance.

Astral elves were among the first creatures to dwell in the Silver Void. As other explorers have reached for the stars, astral elves have had to reckon with violent neighbors and strange visitors. Over the eons, astral elves have clashed with numerous invaders, including psurlons, mind flayers, and githyanki. When dealing with others, astral elves customarily cover their faces with ornate visors, becoming faceless extensions of their gods. Their fierce devotion to the pantheon of elven deities is repaid with divine power. For example, the gods invest astral elf warriors with the power to channel the radiant energy of starlight through their weapons, just as they empower astral elf leaders with the ability to cast spells and summon solar dragons.

Astral elves ply the Astral Sea and Wildspace in ships of their own design. These ships are fashioned from crystals harvested from Wildspace systems and bound together with an organic, plant-based material that hardens like ceramic. The elves sculpt these substances in various configurations to create star moths (see the *Astral Adventurer's Guide*) and other vessels. The elves also reshape the petrified bodies of dead gods found adrift in the Silver Void, transforming them into floating cities and citadels.

Although the Silver Void is their home, astral elves often venture into Wildspace systems and place their ships and citadels in orbit around stars. Astral elves do this for several reasons. Proximity to a star allows the astral elves to forge pacts with solar dragons and to collect starlight, which the elves use to grow crystals and repair their ships. Most important, astral elves use their time outside the Deep Astral to replenish their numbers by having and raising children.

Many astral elves are thousands (in some cases tens of thousands) of years old. Whatever their disposition, their longevity gives astral elves a perspective on time that few other kinds of creatures can appreciate. Whether they choose to live in quiet contemplation or strike out to explore the far reaches of the multiverse, astral elves tend to see events happening elsewhere as having little or no meaning to them.

> [!note] Astral Elves of Xaryxis
> 
> The adventure,*Light of Xaryxis*features an amoral astral elf society called the Xaryxian Empire. This empire is based in Xaryxispace, a Wildspace system illuminated by an enormous radiant sun named Xaryxis.{ #astral-elves-of-xaryxis}


```statblock
"name": "Astral Elf Commander (BAM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "17"
"ac_class": "[half plate](3-Mechanics/CLI/items/half-plate-armor-xphb.md)"
"hp": !!int "143"
"hit_dice": "26d8 + 26"
"stats":
- !!int "12"
- !!int "15"
- !!int "13"
- !!int "18"
- !!int "18"
- !!int "18"
"speed": "30 ft."
"saves":
  "Charisma": !!int "7"
  "Dexterity": !!int "5"
  "Wisdom": !!int "7"
  "Constitution": !!int "4"
"skillsaves":
  "Intimidation": !!int "7"
  "Deception": !!int "7"
  "History": !!int "7"
  "Survival": !!int "7"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Celestial, Common, Elvish"
"cr": "7"
"traits":
- "desc": "The elf casts the following spell, using Wisdom as the spellcasting ability:\n\
    \n2/day: [teleport](3-Mechanics/CLI/spells/teleport-xphb.md)"
  "name": "Spellcasting"
- "desc": "The elf has advantage on saving throws it makes to avoid or end the [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
    \ condition on itself, and magic can't put it to sleep."
  "name": "Fey Ancestry"
- "desc": "The elf doesn't require sleep."
  "name": "Unusual Nature"
"actions":
- "desc": "The elf makes two Longsword or Longbow attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d8\
    \ + 1) slashing damage, or 6 (1d10 + 1) slashing damage when used with two\
    \ hands, plus 14 (4d6) radiant damage."
  "name": "Longsword"
- "desc": "Ranged Weapon Attack: +5 to hit, range 150/600 ft., one target. Hit:\
    \ 6 (1d8 + 2) piercing damage plus 14 (4d6) radiant damage."
  "name": "Longbow"
"source":
- "BAM"
- "LoX"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/astral-elf-commander-bam.webp"
```
^statblock