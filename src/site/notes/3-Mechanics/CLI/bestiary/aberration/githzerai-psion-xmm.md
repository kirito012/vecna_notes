---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/aberration/githzerai-psion-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/12","ttrpg-cli/monster/environment/limbo","ttrpg-cli/monster/environment/planar","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/aberration/gith"],"noteIcon":""}
---

# [Githzerai Psion](3-Mechanics\CLI\bestiary\aberration/githzerai-psion-xmm.md)
*Source: Monster Manual (2024) p. 137*  

These powerful psions oversee githzerai sanctuaries, study enigmatic planar events, and lead rrakkma—hostile forays into mind flayer colonies to slay illithids and uncover secrets of how the ancient gith were transformed.

## Githzerai

*Explorers at Reality's Extremes*

- **Habitat.** Planar (Limbo)  
- **Treasure.** Arcana, Individual  

Githzerai are gaunt, humanlike beings, physically identical to githyanki. They share a history with githyanki as creatures physically and psychically transformed by mind flayers (see the "Githyanki" section). Githzerai know that in body and mind, their species was manipulated by their former illithid oppressors. Rather than giving in to this programming, githzerai follow the teachings of their first leader, Zerthimon, and reshape their minds and bodies to find peace.

Githzerai psychically create serene, hidden sanctuaries in chaotic reaches of the multiverse. Most of these redoubts drift through the chaotic plane of Limbo, but githzerai conclaves can also be found in the Abyss, the Elemental Chaos, and the Feywild. Githzerai create these cloisters to hone their psionic abilities, to gain insights from the multiverse, and to avoid githyanki and mind flayers.

### Adventures with Gith

Characters might be drawn into conflicts involving githzerai and githyanki in various ways. Roll on or choose a result from the Gith Conflicts table to inspire adventures featuring these age-old rivals.

**Gith Conflicts**

`dice: [](githzerai-psion-xmm.md#^gith-conflicts)`

| dice: 1d8 | The Characters Are... |
|-----------|-----------------------|
| 1 | Called on to deliver a message or mysterious parcel to or from Vlaakith the Lich Queen. |
| 2 | Encouraged by a disguised intellect devourer to seek out an elusive gith leader. |
| 3 | Entreated to aid githzerai fleeing the githyanki who destroyed their sanctuary. |
| 4 | Entrusted with renewing or disrupting the githyanki's alliance with red dragons. |
| 5 | Invited to hunt illithids with githyanki. |
| 6 | Pressed to uncover a gith spy in a planar community or on a spelljamming ship. |
| 7 | Sent on a quest to discover the last known location of the hero Gith or Zerthimon. |
| 8 | Tasked with returning the blade of a fallen githyanki knight to the knight's people. |{ #gith-conflicts}


> [!quote] A quote from Zaerith Menyar-Ag-Gith, Githzerai Leader  
> 
> We githzerai crave a challenge, so that when Zerthimon returns, he shall find us ready. Thus we traveled to howling Limbo to make our new home.


```statblock
"name": "Githzerai Psion (XMM)"
"size": "Medium"
"type": "aberration"
"subtype": "gith"
"alignment": "Lawful Neutral"
"ac": !!int "18"
"hp": !!int "169"
"hit_dice": "26d8 + 52"
"stats":
- !!int "12"
- !!int "18"
- !!int "15"
- !!int "19"
- !!int "18"
- !!int "14"
"speed": "40 ft., fly 40 ft. (hover)"
"saves":
  "Dexterity": !!int "8"
  "Wisdom": !!int "8"
  "Intelligence": !!int "8"
  "Strength": !!int "5"
"skillsaves":
  "Insight": !!int "8"
  "Perception": !!int "8"
  "Arcana": !!int "8"
"senses": "passive Perception 18"
"languages": "Common, Gith"
"cr": "12"
"traits":
- "desc": "The githzerai casts one of the following spells, requiring no spell components\
    \ and using Intelligence as the spellcasting ability (spell save DC 16):\n\nAt\
    \ will: [Mage Hand](3-Mechanics/CLI/spells/mage-hand-xphb.md) (the hand is Invisible)\n\
    \n1/day each: [Plane Shift](3-Mechanics/CLI/spells/plane-shift-xphb.md), [See\
    \ Invisibility](3-Mechanics/CLI/spells/see-invisibility-xphb.md)"
  "name": "Spellcasting"
- "desc": "The githzerai casts [Feather Fall](3-Mechanics/CLI/spells/feather-fall-xphb.md)\
    \ or [Shield](3-Mechanics/CLI/spells/shield-xphb.md) in response to the spell's\
    \ trigger, requiring no spell components and using the same spellcasting ability\
    \ as Spellcasting.\n\nAt will: [Feather Fall](3-Mechanics/CLI/spells/feather-fall-xphb.md),\
    \ [Shield](3-Mechanics/CLI/spells/shield-xphb.md)"
  "name": "Psionic Defense"
"actions":
- "desc": "The githzerai makes three Psychic Warp attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Attack Roll: +8, reach 5 ft. or range 120 ft. Hit:\
    \ 26 (4d10 + 4) Psychic damage, and the target has the githzerai's choice of\
    \ (A) the [Charmed](3-Mechanics/CLI/rules/conditions.md#Charmed) condition until\
    \ the start of the githzerai's next turn or (B) the [Prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
    \ condition, provided the target is a Large or smaller creature."
  "name": "Psychic Warp"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/aberration/token/githzerai-psion-xmm.webp"
```{ #statblock}


## Environment

planar, limbo