---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/dragon/adult-black-dragon-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/14","ttrpg-cli/monster/environment/swamp","ttrpg-cli/monster/size/huge","ttrpg-cli/monster/type/dragon/chromatic"],"noteIcon":""}
---

# [Adult Black Dragon](3-Mechanics\CLI\bestiary\dragon/adult-black-dragon-xmm.md)
*Source: Monster Manual (2024) p. 39*  

By the time they're adults, black dragons are among the greatest terrors in the lands they claim. Wretched swamps and monster-haunted ruins grow more dismal and spread under an adult black dragon's influence. Morbid cultists and doomsayers frequently gather in the dragon's service, bringing with them undead terrors that answer to the black dragon and aid it in spreading ruin to nearby bastions of beauty and peace.

## Black Dragons

*Dragons of Decay and Despair*

- **Habitat.** Swamp  
- **Treasure.** Relics  

Black dragons delight in suffering and ruin. While other chromatic dragons scheme for power and wealth, these dragons seek to tear down all they see and rule over what remains.

Black dragons are terrifying creatures with curved horns and withered visages suggestive of fiendish skulls. They typically inhabit stagnant swamps, crumbling ruins, or places of magical or environmental corruption. Their acid breath scars their domains, eroding the features from ancient statues and leaving nature with festering wounds.

Black dragons hoard tarnished symbols of hope and relics of fallen empires. The more sought-after the treasure, the more black dragons prize it—particularly if they were responsible for it being lost.

### Black Dragon Lairs

Black dragons lurk in dismal ruins, polluted bogs, or other sites gripped by decay.

```statblock
"name": "Adult Black Dragon (XMM)"
"size": "Huge"
"type": "dragon"
"subtype": "chromatic"
"alignment": "Chaotic Evil"
"ac": !!int "19"
"hp": !!int "195"
"hit_dice": "17d12 + 85"
"stats":
- !!int "23"
- !!int "14"
- !!int "21"
- !!int "14"
- !!int "13"
- !!int "19"
"speed": "40 ft., fly 80 ft., swim 40 ft."
"saves":
  "Dexterity": !!int "7"
  "Wisdom": !!int "6"
"skillsaves":
  "Stealth": !!int "7"
  "Perception": !!int "11"
"damage_immunities": "acid"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 21"
"languages": "Common, Draconic"
"cr": "14"
"traits":
- "desc": "The dragon casts one of the following spells, requiring no Material components\
    \ and using Charisma as the spellcasting ability (spell save DC 17, +9 to hit\
    \ with spell attacks):\n\nAt will: [Detect Magic](3-Mechanics/CLI/spells/detect-magic-xphb.md),\
    \ [Fear](3-Mechanics/CLI/spells/fear-xphb.md), [Melf's Acid Arrow](3-Mechanics/CLI/spells/melfs-acid-arrow-xphb.md)\
    \ (level 3 version)\n\n1/day each: [Speak with Dead](3-Mechanics/CLI/spells/speak-with-dead-xphb.md),\
    \ [Vitriolic Sphere](3-Mechanics/CLI/spells/vitriolic-sphere-xphb.md)"
  "name": "Spellcasting"
- "desc": "The dragon can breathe air and water."
  "name": "Amphibious"
- "desc": "If the dragon fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day, or 4/Day in Lair)"
"actions":
- "desc": "The dragon makes three Rend attacks. It can replace one attack with a use\
    \ of Spellcasting to cast [Melf's Acid Arrow](3-Mechanics/CLI/spells/melfs-acid-arrow-xphb.md)\
    \ (level 3 version)."
  "name": "Multiattack"
- "desc": "Melee Attack Roll: +11, reach 10 ft. Hit: 13 (2d6 + 6) Slashing\
    \ damage plus 4 (1d8) Acid damage."
  "name": "Rend"
- "desc": "Dexterity Saving Throw: DC 18, each creature in a 60-foot-long, 5-foot-wide\
    \ [Line](3-Mechanics/CLI/rules/variant-rules/line-area-of-effect-xphb.md). Failure:\
    \ 54 (12d8) Acid damage. Success: Half damage."
  "name": "Acid Breath (Recharge 5-6)"
"legendary_actions":
- "desc": "Dexterity Saving Throw: DC 17, one creature the dragon can see within\
    \ 120 feet. Failure: 22 (4d10) Poison damage, and the target has [Disadvantage](3-Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md)\
    \ on saving throws to maintain [Concentration](3-Mechanics/CLI/rules/conditions.md#Concentration)\
    \ until the end of its next turn. Failure or Success: The dragon can't take\
    \ this action again until the start of its next turn."
  "name": "Cloud of Insects"
- "desc": "The dragon uses Spellcasting to cast [Fear](3-Mechanics/CLI/spells/fear-xphb.md).\
    \ The dragon can't take this action again until the start of its next turn."
  "name": "Frightful Presence"
- "desc": "The dragon can move up to half its [Speed](3-Mechanics/CLI/rules/variant-rules/speed-xphb.md),\
    \ and it makes one Rend attack."
  "name": "Pounce"
"regional_effects":
- "desc": "The region containing an adult or ancient black dragon's lair is warped\
    \ by its presence, creating the following effects:"
  "name": ""
- "desc": "- Acrid Haze. Odorous and stifling fog covers the area within 1 mile\
    \ of the lair, rendering that area [Lightly Obscured](3-Mechanics/CLI/rules/variant-rules/lightly-obscured-xphb.md).\
    \ Travel for creatures other than the dragon and its allies takes twice the usual\
    \ time in that area.  \n- Foul Water. Water sources within 1 mile of the lair\
    \ are supernaturally fouled. A creature that drinks such water must succeed on\
    \ a DC 15 Constitution saving throw or have the [Poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
    \ condition for 1 hour.  "
  "name": ""
- "desc": "If the dragon dies or moves its lair elsewhere, these effects end immediately."
  "name": ""
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/dragon/token/adult-black-dragon-xmm.webp"
```{ #statblock}


## Environment

swamp