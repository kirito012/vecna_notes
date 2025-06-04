---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/aberration/death-slaad-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/10","ttrpg-cli/monster/environment/limbo","ttrpg-cli/monster/environment/planar","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/aberration"],"noteIcon":""}
---

# [Death Slaad](3-Mechanics\CLI\bestiary\aberration/death-slaad-xmm.md)
*Source: Monster Manual (2024) p. 287*  

Slaad lords create death slaadi by infusing gray slaadi with a portion of their chaotic energy. When groups of slaadi act deliberately, death slaadi are often behind their designs.

## Slaadi

*Chaos-Spawned Hordes of Limbo*

- **Habitat.** Planar (Limbo)  
- **Treasure.** Any  

Unpredictable slaadi devour and multiply across the Ever-Changing Chaos of Limbo. These toad-like, extraplanar beings embody the endless potentiality of their home plane of existence. While slaadi aren't inherently evil, their impulses are wild and often destructive. Many are driven to propagate through supernatural processes. Unfortunately, these processes typically are fatal for other creatures.

Slaadi have no formal society. Rather, strong slaadi dominate weaker ones. Blue and red slaadi rampage across Limbo and spill into other worlds at the direction of green slaadi. More powerful slaadi have connections to the Spawning Stone, a source of chaotic magic from which the first slaadi originated. The Spawning Stone is hidden deep within Limbo, and legends tie its origins to the modron overlord Primus or the ruinous slaad lords, such as Ssendam, the golden amoeboid terror, and Ygorl, the winged skeleton. These slaad lords and others plot to spread slaadi across the multiverse.

> [!note] Slaad Control Gems
> 
> A slaad born from the Spawning Stone has a magical control gem embedded in its head. If a creature claims the gem, the slaad has the [Charmed](3-Mechanics/CLI/rules/conditions.md#Charmed) condition and obeys the gem's bearer. The slaad ceases to be [Charmed](3-Mechanics/CLI/rules/conditions.md#Charmed) if it is harmed by the gem's bearer or the bearer's allies or if the gem is returned to the slaad. A [Greater Restoration](3-Mechanics/CLI/spells/greater-restoration-xphb.md) spell cast on a slaad destroys the gem, and the slaad ceases to be [Charmed](3-Mechanics/CLI/rules/conditions.md#Charmed).
> 
> One can obtain a slaad's control gem using a [Wish](3-Mechanics/CLI/spells/wish-xphb.md) or [Imprisonment](3-Mechanics/CLI/spells/imprisonment-xphb.md) spell. If the slaad fails its saving throw against [Imprisonment](3-Mechanics/CLI/spells/imprisonment-xphb.md), the caster gains the gem, and the slaad isn't imprisoned. An [Incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated) slaad's control gem can be removed by spending 1 minute and succeeding on a DC 20 Wisdom ([Medicine](3-Mechanics/CLI/rules/skills.md#Medicine)) check. Failing this check deals 22 (`4d10`) Piercing damage to the slaad.{ #slaad-control-gems}


> [!quote] A quote from Jebeel Sloom  
> 
> Fight a slaad and lose, the story's over. Fight a slaad and win, there's a thousand more standing in line just to prove they're tougher.


```statblock
"name": "Death Slaad (XMM)"
"size": "Medium"
"type": "aberration"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"hp": !!int "178"
"hit_dice": "21d8 + 84"
"stats":
- !!int "20"
- !!int "15"
- !!int "19"
- !!int "15"
- !!int "10"
- !!int "19"
"speed": "40 ft."
"skillsaves":
  "Perception": !!int "8"
  "Arcana": !!int "6"
"damage_resistances": "acid, cold, fire, lightning, thunder"
"senses": "blindsight 60 ft., darkvision 60 ft., passive Perception 18"
"languages": "Common, Slaad; telepathy 60 ft."
"cr": "10"
"traits":
- "desc": "The slaad casts one of the following spells, requiring no Material components\
    \ and using Charisma as the spellcasting ability (spell save DC 16):\n\nAt will:\
    \ [Detect Magic](3-Mechanics/CLI/spells/detect-magic-xphb.md), [Detect Thoughts](3-Mechanics/CLI/spells/detect-thoughts-xphb.md),\
    \ [Invisibility](3-Mechanics/CLI/spells/invisibility-xphb.md) (self only), [Mage\
    \ Hand](3-Mechanics/CLI/spells/mage-hand-xphb.md), [Major Image](3-Mechanics/CLI/spells/major-image-xphb.md)\n\
    \n1/day each: [Blight](3-Mechanics/CLI/spells/blight-xphb.md) (level 8 version),\
    \ [Cloudkill](3-Mechanics/CLI/spells/cloudkill-xphb.md) (level 6 version), [Fly](3-Mechanics/CLI/spells/fly-xphb.md),\
    \ [Plane Shift](3-Mechanics/CLI/spells/plane-shift-xphb.md), [Tongues](3-Mechanics/CLI/spells/tongues-xphb.md)"
  "name": "Spellcasting"
- "desc": "The slaad has [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md)\
    \ on saving throws against spells and other magical effects."
  "name": "Magic Resistance"
- "desc": "The slaad regains 10 [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
    \ at the start of each of its turns if it has at least 1 [Hit Point](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)."
  "name": "Regeneration"
"actions":
- "desc": "The slaad makes two Chaos Blade attacks."
  "name": "Multiattack"
- "desc": "Melee Attack Roll: +9, reach 10 ft. Hit: 11 (1d12 + 5) Slashing\
    \ damage plus 10 (3d6) Necrotic damage. Until the start of the slaad's next\
    \ turn, the target has a condition determined by rolling 1d4: on a 1, [Charmed](3-Mechanics/CLI/rules/conditions.md#Charmed);\
    \ on a 2, [Frightened](3-Mechanics/CLI/rules/conditions.md#Frightened); on a 3,\
    \ [Poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned); or on a 4, [Incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)."
  "name": "Chaos Blade"
"bonus_actions":
- "desc": "The slaad shape-shifts into a Small or Medium Humanoid, or it returns to\
    \ its true form. Other than its size, its game statistics are the same in each\
    \ form. Any equipment it is wearing or carrying isn't transformed."
  "name": "Shape-Shift"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/aberration/token/death-slaad-xmm.webp"
```{ #statblock}


## Environment

planar, limbo