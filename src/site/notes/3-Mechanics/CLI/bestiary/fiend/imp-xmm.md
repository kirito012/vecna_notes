---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/fiend/imp-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/1","ttrpg-cli/monster/environment/any","ttrpg-cli/monster/size/tiny","ttrpg-cli/monster/type/fiend/devil"],"noteIcon":""}
---

# [Imp](3-Mechanics\CLI\bestiary\fiend/imp-xmm.md)
*Source: Monster Manual (2024) p. 177, Player's Handbook (2024) p. 352*  

## Imp

*Devil of Pettiness and Suspicion*

- **Habitat.** Any  
- **Treasure.** None  

Known for their cowardice and toadying, imps serve devils and wicked magic-users. Their abilities to shape-shift and pass unseen make them skillful spies and adept at fleeing danger. Imps sent to surveil other creatures relate what they discover to their masters, but they frequently omit important details or cast events in the worst possible light to mislead their masters into following the imps' devilish council.

Imps without masters delight in manipulating other creatures and inflating their own egos. They might take over bands of weaker monsters, or they might pose as helpful spirits and trick influential individuals into pursuing nefarious ends.

> [!quote] A quote from Skeever, Imp Servant of Firan Zal'Honan  
> 
> I can tell you what I know, but wouldn't you rather I tell you what'll let you do what you know you're going to do anyway?


```statblock
"name": "Imp (XMM)"
"size": "Tiny"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "13"
"hp": !!int "21"
"hit_dice": "6d4 + 6"
"stats":
- !!int "6"
- !!int "17"
- !!int "13"
- !!int "11"
- !!int "12"
- !!int "14"
"speed": "20 ft., fly 40 ft."
"skillsaves":
  "Deception": !!int "4"
  "Stealth": !!int "5"
  "Insight": !!int "3"
"damage_resistances": "cold"
"damage_immunities": "fire, poison"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft. (unimpeded by magical darkness), passive Perception\
  \ 11"
"languages": "Common, Infernal"
"cr": "1"
"traits":
- "desc": "The imp casts [Invisibility](3-Mechanics/CLI/spells/invisibility-xphb.md)\
    \ on itself, requiring no spell components and using Charisma as the spellcasting\
    \ ability.\n\nAt will: [Invisibility](3-Mechanics/CLI/spells/invisibility-xphb.md)"
  "name": "Invisibility"
- "desc": "The imp has [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md)\
    \ on saving throws against spells and other magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Melee Attack Roll: +5, reach 5 ft. Hit: 6 (1d6 + 3) Piercing damage\
    \ plus 7 (2d6) Poison damage."
  "name": "Sting"
- "desc": "The imp shape-shifts to resemble a rat ([Speed](3-Mechanics/CLI/rules/variant-rules/speed-xphb.md)\
    \ 20 ft.), a raven (20 ft., Fly 60 ft.), or a spider (20 ft., Climb 20 ft.), or\
    \ it returns to its true form. Its statistics are the same in each form, except\
    \ for its [Speed](3-Mechanics/CLI/rules/variant-rules/speed-xphb.md). Any equipment\
    \ it is wearing or carrying isn't transformed."
  "name": "Shape-Shift"
"source":
- "XMM"
- "XPHB"
"image": "3-Mechanics/CLI/bestiary/fiend/token/imp-xmm.webp"
```{ #statblock}


## Environment

any