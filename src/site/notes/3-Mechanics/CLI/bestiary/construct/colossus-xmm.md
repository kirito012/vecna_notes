---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/construct/colossus-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/25","ttrpg-cli/monster/environment/any","ttrpg-cli/monster/size/gargantuan","ttrpg-cli/monster/type/construct/titan"],"noteIcon":""}
---

# [Colossus](3-Mechanics\CLI\bestiary\construct/colossus-xmm.md)
*Source: Monster Manual (2024) p. 76*  

## Colossus

*Titanic Vessel of Divine Might*

- **Habitat.** Any  
- **Treasure.** Relics  

Colossi are massive Constructs created by the devout to reflect the nature of a deity, which could be benevolent or wicked. Colossi thrum with incredible magic and work divine will on the land.

Droves of faithful artisans craft a colossus in a shape to honor their deity, then call on that god to infuse the statue with life. This arduous process might take decades and involve hundreds of workers. If the god favors the creation, the mighty crystal at the construct's heart pulses with divine power, and the colossus rises to protect the faithful or enact the god's will.

Most colossi were created in ages past and now lie dormant in secluded wilderness, awakening only when disturbed or called on to serve once more.

```statblock
"name": "Colossus (XMM)"
"size": "Gargantuan"
"type": "construct"
"subtype": "titan"
"alignment": "Unaligned"
"ac": !!int "23"
"hp": !!int "553"
"hit_dice": "27d20 + 270"
"stats":
- !!int "30"
- !!int "11"
- !!int "30"
- !!int "3"
- !!int "11"
- !!int "8"
"speed": "60 ft."
"saves":
  "Dexterity": !!int "8"
  "Wisdom": !!int "8"
"damage_resistances": "necrotic, radiant"
"damage_immunities": "poison, psychic"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned),\
  \ [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned), [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)"
"senses": "truesight 300 ft., passive Perception 10"
"languages": "understands Celestial and Common but can't speak"
"cr": "25"
"traits":
- "desc": "The colossus can't shape-shift."
  "name": "Immutable Form"
- "desc": "If the colossus fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (4/Day)"
- "desc": "The colossus has [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md)\
    \ on saving throws against spells and other magical effects."
  "name": "Magic Resistance"
- "desc": "The colossus deals double damage to objects and structures."
  "name": "Siege Monster"
"actions":
- "desc": "The colossus makes three attacks, using Slam or Radiant Ray in any combination."
  "name": "Multiattack"
- "desc": "Melee Attack Roll: +18, reach 20 ft. Hit: 32 (4d10 + 10) Bludgeoning\
    \ damage, and the colossus pushes the target up to 20 feet straight away from\
    \ itself."
  "name": "Slam"
- "desc": "Ranged Attack Roll: +18, range 300 ft. Hit: 22 (4d10) Radiant damage.\
    \ If the target is a Large or smaller creature, it has the [Prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
    \ condition."
  "name": "Radiant Ray"
- "desc": "Dexterity Saving Throw: DC 26, each creature in a 300-foot-long, 10-foot-wide\
    \ [Line](3-Mechanics/CLI/rules/variant-rules/line-area-of-effect-xphb.md). Failure:\
    \ 65 (10d12) Radiant damage. Success: Half damage. Failure or Success: A\
    \ creature reduced to 0 [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
    \ by this beam disintegrates into dust, leaving behind any magic items it was\
    \ wearing or carrying."
  "name": "Divine Beam (Recharge 5-6)"
"legendary_actions":
- "desc": "The colossus makes one Radiant Ray attack."
  "name": "Smite"
- "desc": "The colossus moves up to half its [Speed](3-Mechanics/CLI/rules/variant-rules/speed-xphb.md)\
    \ without provoking Opportunity Attacks, and it can make one Slam attack at any\
    \ point during that move."
  "name": "Stomp"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/construct/token/colossus-xmm.webp"
```{ #statblock}


## Environment

any