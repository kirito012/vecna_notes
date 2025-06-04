---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/dragon/ancient-copper-dragon-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/21","ttrpg-cli/monster/environment/hill","ttrpg-cli/monster/size/gargantuan","ttrpg-cli/monster/type/dragon/metallic"],"noteIcon":""}
---

# [Ancient Copper Dragon](3-Mechanics\CLI\bestiary\dragon/ancient-copper-dragon-xmm.md)
*Source: Monster Manual (2024) p. 80*  

Ancient copper dragons use warmth and reliability to effect change over time. They open their cozy lairs to their friends as havens of learning and laughter for the young and those in need. These dragons watch for and oppose future threats while fostering sanctuaries of simple goodness.

## Copper Dragons

*Dragons of Curiosity and Community*

- **Habitat.** Hill  
- **Treasure.** Arcana  

Relentlessly friendly and curious, most copper dragons view the world as a place of endless wonder and possibility. These gregarious dragons are fonts of patience, hospitality, and humor, and they seek to improve the lives—or, at least, the mood—of those they interact with. If forced to fight to defend themselves or their friends, these dragons favor using their slowing breath and physical attacks to subdue antagonists. Only in cases of extreme peril or emotion do they use their deadly acid breath.

Copper dragons typically live in caverns amid picturesque hills and rock formations—particularly those that are prominent landmarks. These dragons collect gifts, though they have little interest in treasure without meaning, no matter how valuable it is. To them, thoughtfully given presents and the feelings or memories they symbolize are more important than masterpieces or magical relics.

### Copper Dragon Lairs

Copper dragons typically inhabit multichamber caves and renovated ruins.

```statblock
"name": "Ancient Copper Dragon (XMM)"
"size": "Gargantuan"
"type": "dragon"
"subtype": "metallic"
"alignment": "Chaotic Good"
"ac": !!int "21"
"hp": !!int "367"
"hit_dice": "21d20 + 147"
"stats":
- !!int "27"
- !!int "12"
- !!int "25"
- !!int "20"
- !!int "17"
- !!int "22"
"speed": "40 ft., climb 40 ft., fly 80 ft."
"saves":
  "Dexterity": !!int "8"
  "Wisdom": !!int "10"
"skillsaves":
  "Deception": !!int "13"
  "Stealth": !!int "8"
  "Perception": !!int "17"
"damage_immunities": "acid"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 27"
"languages": "Common, Draconic"
"cr": "21"
"traits":
- "desc": "The dragon casts one of the following spells, requiring no Material components\
    \ and using Charisma as the spellcasting ability (spell save DC 21):\n\nAt will:\
    \ [Detect Magic](3-Mechanics/CLI/spells/detect-magic-xphb.md), [Mind Spike](3-Mechanics/CLI/spells/mind-spike-xphb.md)\
    \ (level 5 version), [Minor Illusion](3-Mechanics/CLI/spells/minor-illusion-xphb.md),\
    \ [Shapechange](3-Mechanics/CLI/spells/shapechange-xphb.md) (Beast or Humanoid\
    \ form only, no [Temporary Hit Points](3-Mechanics/CLI/rules/variant-rules/temporary-hit-points-xphb.md)\
    \ gained from the spell, and no Concentration or [Temporary Hit Points](3-Mechanics/CLI/rules/variant-rules/temporary-hit-points-xphb.md)\
    \ required to maintain the spell)\n\n1/day each: [Greater Restoration](3-Mechanics/CLI/spells/greater-restoration-xphb.md),\
    \ [Major Image](3-Mechanics/CLI/spells/major-image-xphb.md), [Project Image](3-Mechanics/CLI/spells/project-image-xphb.md)"
  "name": "Spellcasting"
- "desc": "If the dragon fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (4/Day, or 5/Day in Lair)"
"actions":
- "desc": "The dragon makes three Rend attacks. It can replace one attack with a use\
    \ of (A) Slowing Breath or (B) Spellcasting to cast [Mind Spike](3-Mechanics/CLI/spells/mind-spike-xphb.md)\
    \ (level 5 version)."
  "name": "Multiattack"
- "desc": "Melee Attack Roll: +15, reach 15 ft. Hit: 19 (2d10 + 8) Slashing\
    \ damage plus 9 (2d8) Acid damage."
  "name": "Rend"
- "desc": "Dexterity Saving Throw: DC 22, each creature in an 90-foot-long, 10-foot-wide\
    \ [Line](3-Mechanics/CLI/rules/variant-rules/line-area-of-effect-xphb.md). Failure:\
    \ 63 (14d8) Acid damage. Success: Half damage."
  "name": "Acid Breath (Recharge 5-6)"
- "desc": "Constitution Saving Throw: DC 22, each creature in a 90-foot [Cone](3-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md).\
    \ Failure: The target can't take Reactions; its [Speed](3-Mechanics/CLI/rules/variant-rules/speed-xphb.md)\
    \ is halved; and it can take either an action or a [Bonus Action](3-Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md)\
    \ on its turn, not both. This effect lasts until the end of its next turn."
  "name": "Slowing Breath"
"legendary_actions":
- "desc": "Charisma Saving Throw: DC 21, one creature the dragon can see within\
    \ 120 feet. Failure: 31 (9d6) Psychic damage. Until the end of its next turn,\
    \ the target rolls 1d8 whenever it makes an ability check or attack roll and\
    \ subtracts the number rolled from the [D20 Test](3-Mechanics/CLI/rules/variant-rules/d20-test-xphb.md).\
    \ Failure or Success: The dragon can't take this action again until the start\
    \ of its next turn."
  "name": "Giggling Magic"
- "desc": "The dragon uses Spellcasting to cast [Mind Spike](3-Mechanics/CLI/spells/mind-spike-xphb.md)\
    \ (level 5 version). The dragon can't take this action again until the start of\
    \ its next turn."
  "name": "Mind Jolt"
- "desc": "The dragon moves up to half its [Speed](3-Mechanics/CLI/rules/variant-rules/speed-xphb.md),\
    \ and it makes one Rend attack."
  "name": "Pounce"
"regional_effects":
- "desc": "The region containing an adult or ancient copper dragon's lair is changed\
    \ by its presence, creating the following effects:"
  "name": ""
- "desc": "- Chatty Critters. Tiny Beasts magically gain the ability to speak\
    \ and understand Draconic while within 6 miles of the lair.  \n- Giggle Fits.\
    \ Whenever a creature other than the dragon and its allies is within 1 mile of\
    \ the lair and rolls a 1 on a [D20 Test](3-Mechanics/CLI/rules/variant-rules/d20-test-xphb.md),\
    \ it must succeed on a DC 15 Wisdom saving throw or have the [Incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
    \ condition until the end of its next turn, as it is wracked with laughter.  "
  "name": ""
- "desc": "If the dragon dies or moves its lair elsewhere, these effects end immediately."
  "name": ""
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/dragon/token/ancient-copper-dragon-xmm.webp"
```{ #statblock}


## Environment

hill