---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/dragon/adult-blue-dragon-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/16","ttrpg-cli/monster/environment/coastal","ttrpg-cli/monster/environment/desert","ttrpg-cli/monster/size/huge","ttrpg-cli/monster/type/dragon/chromatic"],"noteIcon":""}
---

# [Adult Blue Dragon](3-Mechanics\CLI\bestiary\dragon/adult-blue-dragon-xmm.md)
*Source: Monster Manual (2024) p. 49*  

Adult blue dragons command small empires, which might be territories of subjugated followers, shadowy criminal networks, or cultic enclaves. Endlessly suspicious and wary of rivals, these dragons enact elaborate schemes to ruin their foes, test the loyalty of their servants, and ensure their dominance for centuries.

## Blue Dragons

*Dragons of Tyranny and Tempests*

- **Habitat.** Desert  
- **Treasure.** Relics  

Arrogant and imperious, blue dragons are chromatic dragons that crave control and collect followers like other dragons hoard treasure. They seek to transform their territories into empires, domains to be feared by nations.

Blue dragons have sharp features with piercing horns and scales that range from sapphire to the shades of stormy skies. They dwell in deserts and badlands, particularly regions with dramatic spires from whose tops they might see for miles. They seek lairs near sites of symbolic power, such as the abandoned fortresses of giants, the colossi of fallen empires, or monuments raised by their followers.

Regalia of rulership and artistic masterpieces fill blue dragons' hoards. These dragons have no interest in treasures that are common or flawed, preferring one-of-a-kind gemstones, the crowns of fallen royals, and magic items capable of spreading the dragons' influence.

### Blue Dragon Lairs

Blue dragons dwell in arid lands. Their lairs might be death traps meant to entomb invaders or ostentatious fortresses where they plot domination.

```statblock
"name": "Adult Blue Dragon (XMM)"
"size": "Huge"
"type": "dragon"
"subtype": "chromatic"
"alignment": "Lawful Evil"
"ac": !!int "19"
"hp": !!int "212"
"hit_dice": "17d12 + 102"
"stats":
- !!int "25"
- !!int "10"
- !!int "23"
- !!int "16"
- !!int "15"
- !!int "20"
"speed": "40 ft., burrow 30 ft., fly 80 ft."
"saves":
  "Dexterity": !!int "5"
  "Wisdom": !!int "7"
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "12"
"damage_immunities": "lightning"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 22"
"languages": "Common, Draconic"
"cr": "16"
"traits":
- "desc": "The dragon casts one of the following spells, requiring no Material components\
    \ and using Charisma as the spellcasting ability (spell save DC 18):\n\nAt will:\
    \ [Detect Magic](3-Mechanics/CLI/spells/detect-magic-xphb.md), [Invisibility](3-Mechanics/CLI/spells/invisibility-xphb.md),\
    \ [Mage Hand](3-Mechanics/CLI/spells/mage-hand-xphb.md), [Shatter](3-Mechanics/CLI/spells/shatter-xphb.md)\n\
    \n1/day each: [Scrying](3-Mechanics/CLI/spells/scrying-xphb.md), [Sending](3-Mechanics/CLI/spells/sending-xphb.md)"
  "name": "Spellcasting"
- "desc": "If the dragon fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day, or 4/Day in Lair)"
"actions":
- "desc": "The dragon makes three Rend attacks. It can replace one attack with a use\
    \ of Spellcasting to cast [Shatter](3-Mechanics/CLI/spells/shatter-xphb.md)."
  "name": "Multiattack"
- "desc": "Melee Attack Roll: +12, reach 10 ft. Hit: 16 (2d8 + 7) Slashing\
    \ damage plus 5 (1d10) Lightning damage."
  "name": "Rend"
- "desc": "Dexterity Saving Throw: DC 19, each creature in a 90-foot-long, 5-foot-wide\
    \ [Line](3-Mechanics/CLI/rules/variant-rules/line-area-of-effect-xphb.md). Failure:\
    \ 60 (11d10) Lightning damage. Success: Half damage."
  "name": "Lightning Breath (Recharge 5-6)"
"legendary_actions":
- "desc": "The dragon uses Spellcasting to cast [Invisibility](3-Mechanics/CLI/spells/invisibility-xphb.md)\
    \ on itself, and it can fly up to half its [Fly Speed](3-Mechanics/CLI/rules/variant-rules/fly-speed-xphb.md).\
    \ The dragon can't take this action again until the start of its next turn."
  "name": "Cloaked Flight"
- "desc": "The dragon uses Spellcasting to cast [Shatter](3-Mechanics/CLI/spells/shatter-xphb.md).\
    \ The dragon can't take this action again until the start of its next turn."
  "name": "Sonic Boom"
- "desc": "The dragon makes one Rend attack."
  "name": "Tail Swipe"
"regional_effects":
- "desc": "The region containing an adult or ancient blue dragon's lair is changed\
    \ by its presence, creating the following effects:"
  "name": ""
- "desc": "- Sinkholes. Sinkholes form more frequently in the area within 1 mile\
    \ of the lair. Whenever a creature in that area other than the dragon and its\
    \ allies finishes a [Long Rest](3-Mechanics/CLI/rules/variant-rules/long-rest-xphb.md),\
    \ roll d20. On a 1, a sinkhole opens beneath the creature, and the creature\
    \ must succeed on a DC 15 Dexterity saving throw or fall 2d4 × 10 feet into\
    \ the sinkhole.  \n- Spiteful Storms. Dust devils and thunderstorms rage within\
    \ 1 mile of the lair. The area is [Lightly Obscured](3-Mechanics/CLI/rules/variant-rules/lightly-obscured-xphb.md).\
    \  "
  "name": ""
- "desc": "If the dragon dies or moves its lair elsewhere, these effects end immediately."
  "name": ""
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/dragon/token/adult-blue-dragon-xmm.webp"
```{ #statblock}


## Environment

coastal, desert