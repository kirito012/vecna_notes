---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/fiend/ultroloth-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/13","ttrpg-cli/monster/environment/lower","ttrpg-cli/monster/environment/planar","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/fiend/yugoloth"],"noteIcon":""}
---

# [Ultroloth](3-Mechanics\CLI\bestiary\fiend/ultroloth-xmm.md)
*Source: Monster Manual (2024) p. 311*  

## Ultroloth

*Yugoloth of Conspiracy and Control*

- **Habitat.** Planar (Lower Planes)  
- **Treasure.** Armaments  

With uncanny patience and fiendish cunning, ultroloths manipulate mortals and their fellow yugoloths alike, seeking to hoard power and spread suffering. These sinister masterminds often work with other yugoloths, but they might compel nearly any creature into their service. If coercion doesn't work, ultroloths use their eerie eyes and innate magic to hypnotize or charm targets.

Ultroloths strive to achieve planes-spanning plots. Roll on or choose a result from the Ultroloth Conspiracies table to inspire such villainy.

**Ultroloth Conspiracies**

`dice: [](ultroloth-xmm.md#^ultroloth-conspiracies)`

| dice: 1d6 | The Ultroloth Schemes To... |
|-----------|-----------------------------|
| 1 | Convince cultists their god has forsaken them. |
| 2 | Destabilize a nation and rule the chaos. |
| 3 | Incite a calamity and hold a world hostage. |
| 4 | Provoke hostilities between immortal armies and sell magic weapons to both sides. |
| 5 | Steal an invention and slay all who know of it. |
| 6 | Unleash fiendish hordes on a foe's homeland. |{ #ultroloth-conspiracies}


```statblock
"name": "Ultroloth (XMM)"
"size": "Medium"
"type": "fiend"
"subtype": "yugoloth"
"alignment": "Neutral Evil"
"ac": !!int "19"
"hp": !!int "221"
"hit_dice": "26d8 + 104"
"stats":
- !!int "19"
- !!int "16"
- !!int "18"
- !!int "19"
- !!int "15"
- !!int "18"
"speed": "30 ft., fly 60 ft. (hover)"
"skillsaves":
  "Deception": !!int "9"
  "Stealth": !!int "8"
  "Perception": !!int "7"
"damage_resistances": "cold, fire, lightning"
"damage_immunities": "acid, poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "truesight 120 ft., passive Perception 17"
"languages": "Abyssal, Infernal; telepathy 120 ft."
"cr": "13"
"traits":
- "desc": "The ultroloth casts one of the following spells, requiring no Material\
    \ components and using Intelligence as the spellcasting ability (spell save DC\
    \ 17):\n\nAt will: [Alter Self](3-Mechanics/CLI/spells/alter-self-xphb.md),\
    \ [Clairvoyance](3-Mechanics/CLI/spells/clairvoyance-xphb.md), [Detect Magic](3-Mechanics/CLI/spells/detect-magic-xphb.md)\n\
    \n1/day each: [Dimension Door](3-Mechanics/CLI/spells/dimension-door-xphb.md),\
    \ [Fireball](3-Mechanics/CLI/spells/fireball-xphb.md) (level 5 version), [Wall\
    \ of Fire](3-Mechanics/CLI/spells/wall-of-fire-xphb.md)"
  "name": "Spellcasting"
- "desc": "The ultroloth casts [Dispel Magic](3-Mechanics/CLI/spells/dispel-magic-xphb.md),\
    \ [Invisibility](3-Mechanics/CLI/spells/invisibility-xphb.md) (self only), [Misty\
    \ Step](3-Mechanics/CLI/spells/misty-step-xphb.md), or [Suggestion](3-Mechanics/CLI/spells/suggestion-xphb.md),\
    \ requiring no Material components and using the same spellcasting ability as\
    \ Spellcasting.\n"
  "name": "Fiendish Guile (Recharge 4-6)"
- "desc": "If the ultroloth dies outside Gehenna, its body dissolves into ichor, and\
    \ it gains a new body instantly, reviving with all its [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
    \ somewhere in Gehenna."
  "name": "Fiendish Restoration"
- "desc": "The ultroloth has [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md)\
    \ on saving throws against spells and other magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The ultroloth uses Hypnotic Gaze and makes two Mercurial Whip attacks."
  "name": "Multiattack"
- "desc": "Melee Attack Roll: +9, reach 15 ft. Hit: 25 (6d6 + 4) Force damage,\
    \ and the ultroloth can teleport the target up to 10 feet to an unoccupied space\
    \ the ultroloth can see that isn't in the air."
  "name": "Mercurial Whip"
- "desc": "Wisdom Saving Throw: DC 17, each creature in a 30-foot [Cone](3-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md).\
    \ Failure: 10 (3d6) Psychic damage, and the target has the [Stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)\
    \ condition until the start of the ultroloth's next turn. Success: The target\
    \ is immune to this ultroloth's Hypnotic Gaze for 24 hours."
  "name": "Hypnotic Gaze"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/fiend/token/ultroloth-xmm.webp"
```{ #statblock}


## Environment

planar, lower