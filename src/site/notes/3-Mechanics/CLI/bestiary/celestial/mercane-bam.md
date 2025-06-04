---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/celestial/mercane-bam/","tags":["ttrpg-cli/compendium/src/5e/bam","ttrpg-cli/monster/cr/5","ttrpg-cli/monster/size/large","ttrpg-cli/monster/type/celestial"],"noteIcon":""}
---

# [Mercane](3-Mechanics\CLI\bestiary\celestial/mercane-bam.md)
*Source: Boo's Astral Menagerie p. 37, Light of Xaryxis*  

Mercanes are the mysterious, magical creations of one or more deities whose portfolios revolve around fair commerce. Standing 12 feet tall, they are lanky blue beings who dress in elegant robes and have elongated heads and long, spindly fingers.

Mercanes conduct most of their business in Wildspace and the Astral Sea. To a mercane, commerce can take many forms, from the trading of goods and services to the trading of ideas and information. Mercanes are best known, however, for procuring and selling magic items, including artifacts and spelljamming helms. It's rare to see more than one mercane at a time, though it's common for a mercane to be accompanied by underlings or bodyguards.

Mercanes will conduct business with anyone, fairly and reliably, provided the other party has neither harmed nor swindled another mercane in the past. Mercanes have a special form of telepathy that enables them to communicate with one another across the multiverse. A mercane often uses this ability to warn another mercanes about individuals who are dangerous or unreliable. Once a mercane has been offended by someone, getting back into their good graces is next to impossible.

```statblock
"name": "Mercane (BAM)"
"size": "Large"
"type": "celestial"
"alignment": "typically  Lawful Neutral"
"ac": !!int "13"
"ac_class": "[mage armor](3-Mechanics/CLI/spells/mage-armor-xphb.md)"
"hp": !!int "75"
"hit_dice": "10d10 + 20"
"stats":
- !!int "16"
- !!int "10"
- !!int "15"
- !!int "18"
- !!int "16"
- !!int "15"
"speed": "30 ft."
"saves":
  "Charisma": !!int "5"
  "Wisdom": !!int "6"
  "Intelligence": !!int "7"
"skillsaves":
  "Insight": !!int "9"
  "Perception": !!int "6"
  "Persuasion": !!int "5"
"senses": "passive Perception 16"
"languages": "Common, Giant, telepathy 60 ft. (see also Mercane telepathy)"
"cr": "5"
"traits":
- "desc": "The mercane casts one of the following spells, requiring no spell components\
    \ and using Intelligence as the spellcasting ability (spell save DC 15):\n\nAt\
    \ will: [detect magic](3-Mechanics/CLI/spells/detect-magic-xphb.md), [light](3-Mechanics/CLI/spells/light-xphb.md)\n\
    \n1/day each: [dimension door](3-Mechanics/CLI/spells/dimension-door-xphb.md),\
    \ [invisibility](3-Mechanics/CLI/spells/invisibility-xphb.md), [mage armor](3-Mechanics/CLI/spells/mage-armor-xphb.md)\
    \ (self only)"
  "name": "Spellcasting (Psionics)"
- "desc": "The mercane can communicate telepathically with any other mercane it knows,\
    \ regardless of the distance between them."
  "name": "Mercane Telepathy"
"actions":
- "desc": "The mercane makes three Psi-Imbued Blade attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) slashing damage, and if the target is a creature, it must succeed\
    \ on a DC 15 Wisdom saving throw or be [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
    \ of the mercane until the end of the target's next turn."
  "name": "Psi-Imbued Blade"
"source":
- "BAM"
- "LoX"
"image": "3-Mechanics/CLI/bestiary/celestial/token/mercane-bam.webp"
```
^statblock