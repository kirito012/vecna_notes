---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/fiend/incubus-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/4","ttrpg-cli/monster/environment/lower","ttrpg-cli/monster/environment/planar","ttrpg-cli/monster/environment/urban","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/fiend"],"noteIcon":""}
---

# [Incubus](3-Mechanics\CLI\bestiary\fiend/incubus-xmm.md)
*Source: Monster Manual (2024) p. 178*  

## Incubus

*Life-Leeching Dream Stalker*

- **Habitat.** Planar (Lower Planes)  
- **Treasure.** Any  

Incubi exploit the vulnerability of mortal dreams. Slipping into the homes of sleepers, incubi feed off dreams and replace them with terrifying nightmares. Incubi visit victims nightly until their prey expires. The incubi then hunt for new victims, preferring the loved ones of past targets.

Incubi can transform into succubi and vice versa, taking the forms they need to manipulate foes in dreams or in the flesh.

Those visited by an incubus have recurring nightmares. Roll on or choose a result from the Incubus Nightmares table to inspire these night terrors.

**Incubus Nightmares**

`dice: [](incubus-xmm.md#^incubus-nightmares)`

| dice: 1d8 | The Incubus's Victim Has Dreams Of... |
|-----------|---------------------------------------|
| 1 | An angry family member or authority figure. |
| 2 | Being chased through the wilderness. |
| 3 | Being devoured by animals or monsters. |
| 4 | [Falling](3-Mechanics/CLI/traps-hazards/falling-xphb.md), drowning, or suffocating. |
| 5 | A ruinous public embarrassment. |
| 6 | A shadowy intruder or monstrous silhouette. |
| 7 | A traumatic past event. |
| 8 | A visitor with an eerie or enigmatic message. |{ #incubus-nightmares}


```statblock
"name": "Incubus (XMM)"
"size": "Medium"
"type": "fiend"
"alignment": "Neutral Evil"
"ac": !!int "15"
"hp": !!int "66"
"hit_dice": "12d8 + 12"
"stats":
- !!int "8"
- !!int "17"
- !!int "13"
- !!int "15"
- !!int "12"
- !!int "20"
"speed": "30 ft., fly 60 ft."
"skillsaves":
  "Deception": !!int "9"
  "Stealth": !!int "7"
  "Insight": !!int "5"
  "Perception": !!int "5"
  "Persuasion": !!int "9"
"damage_resistances": "cold, fire, poison, psychic"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Abyssal, Common, Infernal; telepathy 60 ft."
"cr": "4"
"traits":
- "desc": "The incubus casts one of the following spells, requiring no Material components\
    \ and using Charisma as the spellcasting ability (spell save DC 15):\n\nAt will:\
    \ [Disguise Self](3-Mechanics/CLI/spells/disguise-self-xphb.md), [Etherealness](3-Mechanics/CLI/spells/etherealness-xphb.md)\n\
    \n1/day each: [Dream](3-Mechanics/CLI/spells/dream-xphb.md), [Hypnotic Pattern](3-Mechanics/CLI/spells/hypnotic-pattern-xphb.md)"
  "name": "Spellcasting"
- "desc": "When the incubus finishes a [Long Rest](3-Mechanics/CLI/rules/variant-rules/long-rest-xphb.md),\
    \ it can shape-shift into a [Succubus](3-Mechanics/CLI/bestiary/fiend/succubus-xmm.md),\
    \ using that stat block instead of this one. Any equipment it's wearing or carrying\
    \ isn't transformed."
  "name": "Succubus Form"
"actions":
- "desc": "The incubus makes two Restless Touch attacks."
  "name": "Multiattack"
- "desc": "Melee Attack Roll: +7, reach 5 ft. Hit: 15 (3d6 + 5) Psychic damage,\
    \ and the target is cursed for 24 hours or until the incubus dies. Until the curse\
    \ ends, the target gains no benefit from finishing Short Rests."
  "name": "Restless Touch"
"bonus_actions":
- "desc": "Wisdom Saving Throw: DC 15, one creature the incubus can see within 60\
    \ feet. Failure: If the target has 20 [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
    \ or fewer, it has the [Unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)\
    \ condition for 1 hour, until it takes damage, or until a creature within 5 feet\
    \ of it takes an action to wake it. Otherwise, the target takes 18 (4d8) Psychic\
    \ damage."
  "name": "Nightmare (Recharge 6)"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/fiend/token/incubus-xmm.webp"
```{ #statblock}


## Environment

planar, lower, urban