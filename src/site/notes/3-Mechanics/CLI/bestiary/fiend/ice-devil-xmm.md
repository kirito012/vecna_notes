---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/fiend/ice-devil-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/14","ttrpg-cli/monster/environment/nine-hells","ttrpg-cli/monster/environment/planar","ttrpg-cli/monster/size/large","ttrpg-cli/monster/type/fiend/devil"],"noteIcon":""}
---

# [Ice Devil](3-Mechanics\CLI\bestiary\fiend/ice-devil-xmm.md)
*Source: Monster Manual (2024) p. 176*  

## Ice Devil

*Devil of Antipathy and Intellectual Arrogance*

- **Habitat.** Planar (Nine Hells)  
- **Treasure.** Arcana  

Heartless strategists of the Nine Hells, ice devils—also known as gelugons—forsake emotion to indulge in their own malicious interpretations of logic. For them, the multiverse is a puzzle that must be solved to benefit them, their masters, and the Nine Hells.

Ice devils act maliciously, disguising their whims as reason and strategy. In the service of evil masters, these insectile devils patiently plot the movements of infernal armies and scheme ways to fulfill wicked goals. They might also serve as guardians, owing to their martial prowess and ability to reshape battlefields with walls of ice.

When indulging their own schemes, ice devils tempt mortals to forsake empathy and social connections to embrace selfish, destructive visions of intellectualism. After isolating victims, these devils drain them of their secrets or send them forth to spread fractious dogmas cloaked as reason.

Ice devils usually lurk in frozen realms, particularly the frigid layer of Cania in the Nine Hells.

> [!quote] A quote from Tasha  
> 
> Part of the charm of ice devils is that they always think they're smarter than you. Mmm—there are few pleasures sweeter than proving a devil wrong.


```statblock
"name": "Ice Devil (XMM)"
"size": "Large"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "18"
"hp": !!int "228"
"hit_dice": "24d10 + 96"
"stats":
- !!int "21"
- !!int "14"
- !!int "18"
- !!int "18"
- !!int "15"
- !!int "18"
"speed": "40 ft."
"saves":
  "Charisma": !!int "9"
  "Dexterity": !!int "7"
  "Wisdom": !!int "7"
  "Constitution": !!int "9"
"skillsaves":
  "Insight": !!int "7"
  "Perception": !!int "7"
  "Persuasion": !!int "9"
"damage_immunities": "cold, fire, poison"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "blindsight 120 ft., passive Perception 17"
"languages": "Infernal; telepathy 120 ft."
"cr": "14"
"traits":
- "desc": "The devil casts [Wall of Ice](3-Mechanics/CLI/spells/wall-of-ice-xphb.md)\
    \ (level 8 version), requiring no spell components and using Intelligence as the\
    \ spellcasting ability (spell save DC 17).\n"
  "name": "Ice Wall (Recharge 6)"
- "desc": "If the devil dies outside the Nine Hells, its body disappears in sulfurous\
    \ smoke, and it gains a new body instantly, reviving with all its [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
    \ somewhere in the Nine Hells."
  "name": "Diabolical Restoration"
- "desc": "The devil has [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md)\
    \ on saving throws against spells and other magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The devil makes three Ice Spear attacks. It can replace one attack with\
    \ a Tail attack."
  "name": "Multiattack"
- "desc": "Melee or Ranged Attack Roll: +10, reach 5 ft. or range 30/120 ft. Hit:\
    \ 14 (2d8 + 5) Piercing damage plus 10 (3d6) Cold damage. Until the end of\
    \ its next turn, the target can't take a [Bonus Action](3-Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md)\
    \ or [Reaction](3-Mechanics/CLI/rules/variant-rules/reaction-xphb.md), its [Speed](3-Mechanics/CLI/rules/variant-rules/speed-xphb.md)\
    \ decreases by 10 feet, and it can move or take one action on its turn, not both.\
    \ Hit or Miss: The spear magically returns to the devil's hand immediately after\
    \ a ranged attack."
  "name": "Ice Spear"
- "desc": "Melee Attack Roll: +10, reach 10 ft. Hit: 15 (3d6 + 5) Bludgeoning\
    \ damage plus 18 (4d8) Cold damage."
  "name": "Tail"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/fiend/token/ice-devil-xmm.webp"
```{ #statblock}


## Environment

planar, nine hells