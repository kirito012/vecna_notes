---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/dragon/shadow-dragon-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/13","ttrpg-cli/monster/environment/planar","ttrpg-cli/monster/environment/shadowfell","ttrpg-cli/monster/environment/underdark","ttrpg-cli/monster/size/huge","ttrpg-cli/monster/type/dragon"],"noteIcon":""}
---

# [Shadow Dragon](3-Mechanics\CLI\bestiary\dragon/shadow-dragon-xmm.md)
*Source: Monster Manual (2024) p. 275*  

## Shadow Dragons

*Dragon Corrupted by Darkness*

- **Habitat.** Planar (Shadowfell), Underdark  
- **Treasure.** Any  

Shadow dragons haunt forgotten, lightless places. While they might have once been other types of dragons, the influence of planar forces, negative energy, or sinister magic has stripped them of their former color or luster. In place of any former breath weapon, shadow dragons exhale caliginous gouts that saps life from everything it touches. Those slain by a shadow dragon's breath rise as shades obedient to the shadow dragon's will.

Shadow dragons typically dwell in the Underdark, particularly in areas with connections to the Shadowfell or other tenebrous realms. In some cases, they might lurk in dark, corrupted reaches of the regions they preferred before transforming into shadow dragons. Overgrown swamps, sepulchral desert ruins, and ash-choked volcanoes make natural lairs for shadow dragons.

Like many other dragons, shadow dragons collect hoards. Their tastes tend to be morbid—collecting coins from ruined empires and their victims' skulls.

### Shadow Dragon Lairs

Shadow dragons lair in places of darkness and despair, such as accursed ruins, the depths of the Underdark, or the Shadowfell.

> [!quote] A quote from Challenge Tempting Victims to the Lair of the Shadow Dragon Aurgloroasa  
> 
> If ye truly be adventurers of lore, seek the great shadowy wyrm who lairs beneath the Peaks of Thunder and return in triumph bearing aloft her fabled Eye of Shadow.


```statblock
"name": "Shadow Dragon (XMM)"
"size": "Huge"
"type": "dragon"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"hp": !!int "189"
"hit_dice": "18d12 + 72"
"stats":
- !!int "21"
- !!int "19"
- !!int "18"
- !!int "14"
- !!int "12"
- !!int "18"
"speed": "40 ft., climb 40 ft., fly 80 ft."
"saves":
  "Dexterity": !!int "9"
  "Wisdom": !!int "6"
"skillsaves":
  "Stealth": !!int "14"
  "Perception": !!int "11"
"damage_resistances": "See Living Shadow"
"damage_immunities": "necrotic"
"senses": "blindsight 30 ft., darkvision 120 ft., passive Perception 21"
"languages": "Common, Draconic"
"cr": "13"
"traits":
- "desc": "If the dragon fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day, or 4/Day in Lair)"
- "desc": "While in [Dim Light](3-Mechanics/CLI/rules/variant-rules/dim-light-xphb.md)\
    \ or [Darkness](3-Mechanics/CLI/rules/variant-rules/darkness-xphb.md), the dragon\
    \ has [Resistance](3-Mechanics/CLI/rules/variant-rules/resistance-xphb.md) to\
    \ damage that isn't Force, Psychic, or Radiant."
  "name": "Living Shadow"
- "desc": "While in sunlight, the dragon has [Disadvantage](3-Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md)\
    \ on ability checks and attack rolls."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "The dragon makes three Rend attacks."
  "name": "Multiattack"
- "desc": "Melee Attack Roll: +10, reach 10 ft. Hit: 12 (2d6 + 5) Slashing\
    \ damage plus 3 (1d6) Necrotic damage."
  "name": "Rend"
- "desc": "Dexterity Saving Throw: DC 17, each creature in a 60-foot [Cone](3-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md).\
    \ Failure: 35 (10d6) Necrotic damage. Success: Half damage. Failure or\
    \ Success: A Humanoid reduced to 0 [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
    \ by this damage dies, and a [Shadow](3-Mechanics/CLI/bestiary/undead/shadow-xmm.md)\
    \ rises from the corpse. The shadow is under the dragon's control and shares the\
    \ dragon's [Initiative](3-Mechanics/CLI/rules/variant-rules/initiative-xphb.md)\
    \ count but acts immediately after the dragon."
  "name": "Shadow Breath (Recharge 5-6)"
"bonus_actions":
- "desc": "While in [Dim Light](3-Mechanics/CLI/rules/variant-rules/dim-light-xphb.md)\
    \ or [Darkness](3-Mechanics/CLI/rules/variant-rules/darkness-xphb.md), the dragon\
    \ takes the Hide action."
  "name": "Shadow Stealth"
"legendary_actions":
- "desc": "The dragon moves up to half its [Speed](3-Mechanics/CLI/rules/variant-rules/speed-xphb.md),\
    \ and it makes one Rend attack."
  "name": "Pounce"
- "desc": "The dragon uses Shadow Stealth, and one creature of its choice that it\
    \ can see within 10 feet of it takes 10 (3d6) Necrotic damage. The dragon can't\
    \ take this action again until the start of its next turn."
  "name": "Veil of Shadow"
"regional_effects":
- "desc": "The region around a shadow dragon's lair is twisted by its presence, creating\
    \ the following effects:"
  "name": ""
- "desc": "- Negative Energy Suffusion. Whenever a creature within 1 mile of the\
    \ lair regains [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
    \ from a spell, it subtracts 1d10 from the number of [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
    \ regained.  \n- Stifling Shadows. Within 1 mile of the lair, effects that\
    \ normally create [Bright Light](3-Mechanics/CLI/rules/variant-rules/bright-light-xphb.md)\
    \ instead create [Dim Light](3-Mechanics/CLI/rules/variant-rules/dim-light-xphb.md),\
    \ and creatures there have [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md)\
    \ on Dexterity ([Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)) checks.  "
  "name": ""
- "desc": "If the dragon dies or moves its lair elsewhere, these effects end immediately."
  "name": ""
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/dragon/token/shadow-dragon-xmm.webp"
```{ #statblock}


## Environment

planar, shadowfell, underdark