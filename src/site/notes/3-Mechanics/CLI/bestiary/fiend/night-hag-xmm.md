---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/fiend/night-hag-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/5","ttrpg-cli/monster/environment/lower","ttrpg-cli/monster/environment/planar","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/fiend"],"noteIcon":""}
---

# [Night Hag](3-Mechanics\CLI\bestiary\fiend/night-hag-xmm.md)
*Source: Monster Manual (2024) p. 225*  

## Night Hag

*Hag of Nightmare and Corruption*

- **Habitat.** Planar (Lower Planes)  
- **Treasure.** Arcana  

Night hags seek mortals to torment and turn to evil. By day, night hags use supernatural deceptions to plague their victims, shape-shifting to pose as other creatures and make their targets believe the world has turned against them. By night, these hags reinforce their tortures with terrifying dreams. Once they force their targets to desperate limits, night hags claim their victims' tormented spirits, capturing them in sinister traps called soul bags. The hags then slip between planes of existence to barter stolen souls to vile magic-users and fiendish entities.

Night hags maintain networks of nefarious customers and collect rumors from across the Lower Planes. These hags might part with their secrets in exchange for magic items and other wicked prices.

```statblock
"name": "Night Hag (XMM)"
"size": "Medium"
"type": "fiend"
"alignment": "Neutral Evil"
"ac": !!int "17"
"hp": !!int "112"
"hit_dice": "15d8 + 45"
"stats":
- !!int "18"
- !!int "15"
- !!int "16"
- !!int "16"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "6"
  "Stealth": !!int "5"
  "Insight": !!int "5"
  "Perception": !!int "5"
"damage_resistances": "cold, fire"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)"
"senses": "darkvision 120 ft., passive Perception 15"
"languages": "Abyssal, Common, Infernal, Primordial"
"cr": "5"
"traits":
- "desc": "While within 30 feet of at least two hag allies, the hag can cast one of\
    \ the following spells, requiring no Material components, using the spell's normal\
    \ casting time, and using Intelligence as the spellcasting ability (spell save\
    \ DC 14): [Augury](3-Mechanics/CLI/spells/augury-xphb.md), [Find Familiar](3-Mechanics/CLI/spells/find-familiar-xphb.md),\
    \ [Identify](3-Mechanics/CLI/spells/identify-xphb.md), [Locate Object](3-Mechanics/CLI/spells/locate-object-xphb.md),\
    \ [Scrying](3-Mechanics/CLI/spells/scrying-xphb.md), or [Unseen Servant](3-Mechanics/CLI/spells/unseen-servant-xphb.md).\
    \ The hag must finish a [Long Rest](3-Mechanics/CLI/rules/variant-rules/long-rest-xphb.md)\
    \ before using this trait to cast that spell again.\n"
  "name": "Coven Magic"
- "desc": "The hag casts one of the following spells, requiring no Material components\
    \ and using Intelligence as the spellcasting ability (spell save DC 14):\n\nAt\
    \ will: [Detect Magic](3-Mechanics/CLI/spells/detect-magic-xphb.md), [Etherealness](3-Mechanics/CLI/spells/etherealness-xphb.md),\
    \ [Magic Missile](3-Mechanics/CLI/spells/magic-missile-xphb.md) (level 4 version)\n\
    \n2/day each: [Phantasmal Killer](3-Mechanics/CLI/spells/phantasmal-killer-xphb.md),\
    \ [Plane Shift](3-Mechanics/CLI/spells/plane-shift-xphb.md) (self only)"
  "name": "Spellcasting"
- "desc": "While on the Ethereal Plane, the hag casts [Dream](3-Mechanics/CLI/spells/dream-xphb.md),\
    \ using the same spellcasting ability as Spellcasting. Only the hag can serve\
    \ as the spell's messenger, and the target must be a creature the hag can see\
    \ on the Material Plane. The spell fails and is wasted if the target is under\
    \ the effect of the [Protection from Evil and Good](3-Mechanics/CLI/spells/protection-from-evil-and-good-xphb.md)\
    \ spell or within a [Magic Circle](3-Mechanics/CLI/spells/magic-circle-xphb.md)\
    \ spell.\n\nIf the target takes damage from the [Dream](3-Mechanics/CLI/spells/dream-xphb.md)\
    \ spell, the target's [Hit Point](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
    \ maximum decreases by an amount equal to that damage. If the spell kills the\
    \ target, its soul is trapped in the hag's soul bag, and the target can't be raised\
    \ from the dead until its soul is released.\n\n1/day: [Dream](3-Mechanics/CLI/spells/dream-xphb.md),\
    \ [Protection from Evil and Good](3-Mechanics/CLI/spells/protection-from-evil-and-good-xphb.md),\
    \ [Magic Circle](3-Mechanics/CLI/spells/magic-circle-xphb.md)"
  "name": "Nightmare Haunting (1/Day; Requires Soul Bag)"
- "desc": "The hag has [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md)\
    \ on saving throws against spells and other magical effects."
  "name": "Magic Resistance"
- "desc": "The hag has a soul bag. While holding or carrying the bag, the hag can\
    \ use its Nightmare Haunting action.\n\nThe bag has AC 15, HP 20, and [Resistance](3-Mechanics/CLI/rules/variant-rules/resistance-xphb.md)\
    \ to all damage. The bag turns to dust if reduced to 0 [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md).\
    \ If the bag is destroyed, any souls the bag is holding are released. The hag\
    \ can create a new bag after 7 days."
  "name": "Soul Bag"
"actions":
- "desc": "The hag makes two Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Attack Roll: +7, reach 5 ft. Hit: 13 (2d8 + 4) Slashing damage."
  "name": "Claw"
"bonus_actions":
- "desc": "The hag shape-shifts into a Small or Medium Humanoid, or it returns to\
    \ its true form. Other than its size, its game statistics are the same in each\
    \ form. Any equipment it is wearing or carrying isn't transformed."
  "name": "Shape-Shift"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/fiend/token/night-hag-xmm.webp"
```{ #statblock}


## Environment

planar, lower