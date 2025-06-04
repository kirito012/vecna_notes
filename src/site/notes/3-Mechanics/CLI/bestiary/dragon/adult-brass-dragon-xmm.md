---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/dragon/adult-brass-dragon-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/13","ttrpg-cli/monster/environment/desert","ttrpg-cli/monster/size/huge","ttrpg-cli/monster/type/dragon/metallic"],"noteIcon":""}
---

# [Adult Brass Dragon](3-Mechanics\CLI\bestiary\dragon/adult-brass-dragon-xmm.md)
*Source: Monster Manual (2024) p. 55*  

Adult brass dragons know many secrets and have vast networks of contacts. These dragons share perspectives they've learned from across the world and passionately combat the lies of con artists and villains that lead people astray.

## Brass Dragons

*Dragons of Lore and Rapport*

- **Habitat.** Desert  
- **Treasure.** Arcana  

Gregarious and outgoing, brass dragons relish sharing knowledge and stories. Although these metallic dragons favor arid lands, they cheerfully journey considerable distances to visit friendly creatures, pass on what they've learned, and collect news. Though good natured, brass dragons don't shirk from combat when necessary, thwarting foes with magical sleep and searing them with flame.

Brass dragons favor warm climes, particularly steppes and rocky or sandy deserts, and they usually dwell near prominent crossroads or oases that regularly draw visitors. They enjoy adopting Humanoid forms, disguising themselves as traveling merchants, scholars, storytellers, or anyone else invested in others' stories.

Brass dragons collect eclectic objects. While such items might seem like knickknacks, each is part of a story—perhaps a nostalgic memento or evidence of a tale passed into myth. An old friend's hat and the crown of the last ruler of a forgotten dynasty could occupy the same shelf in a brass dragon's hoard.

### Brass Dragon Lairs

Brass dragons usually dwell in secret caves and canyons near well-traveled routes.

```statblock
"name": "Adult Brass Dragon (XMM)"
"size": "Huge"
"type": "dragon"
"subtype": "metallic"
"alignment": "Chaotic Good"
"ac": !!int "18"
"hp": !!int "172"
"hit_dice": "15d12 + 75"
"stats":
- !!int "23"
- !!int "10"
- !!int "21"
- !!int "14"
- !!int "13"
- !!int "17"
"speed": "40 ft., burrow 30 ft., fly 80 ft."
"saves":
  "Dexterity": !!int "5"
  "Wisdom": !!int "6"
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "11"
  "History": !!int "7"
  "Persuasion": !!int "8"
"damage_immunities": "fire"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 21"
"languages": "Common, Draconic"
"cr": "13"
"traits":
- "desc": "The dragon casts one of the following spells, requiring no Material components\
    \ and using Charisma as the spellcasting ability (spell save DC 16):\n\nAt will:\
    \ [Detect Magic](3-Mechanics/CLI/spells/detect-magic-xphb.md), [Minor Illusion](3-Mechanics/CLI/spells/minor-illusion-xphb.md),\
    \ [Scorching Ray](3-Mechanics/CLI/spells/scorching-ray-xphb.md), [Shapechange](3-Mechanics/CLI/spells/shapechange-xphb.md)\
    \ (Beast or Humanoid form only, no [Temporary Hit Points](3-Mechanics/CLI/rules/variant-rules/temporary-hit-points-xphb.md)\
    \ gained from the spell, and no Concentration or [Temporary Hit Points](3-Mechanics/CLI/rules/variant-rules/temporary-hit-points-xphb.md)\
    \ required to maintain the spell), [Speak with Animals](3-Mechanics/CLI/spells/speak-with-animals-xphb.md)\n\
    \n1/day each: [Detect Thoughts](3-Mechanics/CLI/spells/detect-thoughts-xphb.md),\
    \ [Control Weather](3-Mechanics/CLI/spells/control-weather-xphb.md)"
  "name": "Spellcasting"
- "desc": "If the dragon fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day, or 4/Day in Lair)"
"actions":
- "desc": "The dragon makes three Rend attacks. It can replace one attack with a use\
    \ of (A) Sleep Breath or (B) Spellcasting to cast [Scorching Ray](3-Mechanics/CLI/spells/scorching-ray-xphb.md)."
  "name": "Multiattack"
- "desc": "Melee Attack Roll: +11, reach 10 ft. Hit: 17 (2d10 + 6) Slashing\
    \ damage plus 4 (1d8) Fire damage."
  "name": "Rend"
- "desc": "Dexterity Saving Throw: DC 18, each creature in a 60-foot-long, 5-foot-wide\
    \ [Line](3-Mechanics/CLI/rules/variant-rules/line-area-of-effect-xphb.md). Failure:\
    \ 45 (10d8) Fire damage. Success: Half damage."
  "name": "Fire Breath (Recharge 5-6)"
- "desc": "Constitution Saving Throw: DC 18, each creature in a 60-foot [Cone](3-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md).\
    \ Failure: The target has the [Incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
    \ condition until the end of its next turn, at which point it repeats the save.\
    \ 2nd Failure: The target has the [Unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)\
    \ condition for 10 minutes. This effect ends for the target if it takes damage\
    \ or a creature within 5 feet of it takes an action to wake it."
  "name": "Sleep Breath"
"legendary_actions":
- "desc": "The dragon uses Spellcasting to cast [Scorching Ray](3-Mechanics/CLI/spells/scorching-ray-xphb.md)."
  "name": "Blazing Light"
- "desc": "The dragon moves up to half its [Speed](3-Mechanics/CLI/rules/variant-rules/speed-xphb.md),\
    \ and it makes one Rend attack."
  "name": "Pounce"
- "desc": "Dexterity Saving Throw: DC 16, one creature the dragon can see within\
    \ 120 feet. Failure: 27 (6d8) Fire damage, and the target's [Speed](3-Mechanics/CLI/rules/variant-rules/speed-xphb.md)\
    \ is halved until the end of its next turn. Failure or Success: The dragon can't\
    \ take this action again until the start of its next turn."
  "name": "Scorching Sands"
"regional_effects":
- "desc": "The area containing an adult or ancient brass dragon's lair is altered\
    \ by its presence, creating the following effects:"
  "name": ""
- "desc": "- Mirages. While in its lair, the dragon can cast [Major Image](3-Mechanics/CLI/spells/major-image-xphb.md),\
    \ requiring no Material components and using the same spellcasting ability as\
    \ its Spellcasting action. When casting the spell this way, the spell's range\
    \ is 1 mile, and the dragon doesn't need to see the spot where the illusion appears.\
    \  \n- Refreshing Water. Water within 1 mile of the lair is magically refreshing.\
    \ A creature that drinks such water gains 2d4 [Temporary Hit Points](3-Mechanics/CLI/rules/variant-rules/temporary-hit-points-xphb.md),\
    \ and the dragon is immediately aware of the creature's presence.  "
  "name": ""
- "desc": "If the dragon dies or moves its lair elsewhere, these effects end immediately."
  "name": ""
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/dragon/token/adult-brass-dragon-xmm.webp"
```{ #statblock}


## Environment

desert