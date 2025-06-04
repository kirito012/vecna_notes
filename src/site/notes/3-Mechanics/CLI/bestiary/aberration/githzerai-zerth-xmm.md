---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/aberration/githzerai-zerth-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/6","ttrpg-cli/monster/environment/limbo","ttrpg-cli/monster/environment/planar","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/aberration/gith"],"noteIcon":""}
---

# [Githzerai Zerth](3-Mechanics\CLI\bestiary\aberration/githzerai-zerth-xmm.md)
*Source: Monster Manual (2024) p. 137*  

Githzerai zerths embody the discipline espoused by their first leader, Zerthimon. Their psionic control aids them in protecting their people and traveling the planes of existence without fear of being followed by githyanki or mind flayer foes.

## Githzerai

*Explorers at Reality's Extremes*

- **Habitat.** Planar (Limbo)  
- **Treasure.** Arcana, Individual  

Githzerai are gaunt, humanlike beings, physically identical to githyanki. They share a history with githyanki as creatures physically and psychically transformed by mind flayers (see the "Githyanki" section). Githzerai know that in body and mind, their species was manipulated by their former illithid oppressors. Rather than giving in to this programming, githzerai follow the teachings of their first leader, Zerthimon, and reshape their minds and bodies to find peace.

Githzerai psychically create serene, hidden sanctuaries in chaotic reaches of the multiverse. Most of these redoubts drift through the chaotic plane of Limbo, but githzerai conclaves can also be found in the Abyss, the Elemental Chaos, and the Feywild. Githzerai create these cloisters to hone their psionic abilities, to gain insights from the multiverse, and to avoid githyanki and mind flayers.

### Adventures with Gith

Characters might be drawn into conflicts involving githzerai and githyanki in various ways. Roll on or choose a result from the Gith Conflicts table to inspire adventures featuring these age-old rivals.

**Gith Conflicts**

`dice: [](githzerai-zerth-xmm.md#^gith-conflicts)`

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
"name": "Githzerai Zerth (XMM)"
"size": "Medium"
"type": "aberration"
"subtype": "gith"
"alignment": "Lawful Neutral"
"ac": !!int "17"
"hp": !!int "84"
"hit_dice": "13d8 + 26"
"stats":
- !!int "13"
- !!int "18"
- !!int "15"
- !!int "16"
- !!int "17"
- !!int "12"
"speed": "40 ft."
"saves":
  "Dexterity": !!int "7"
  "Wisdom": !!int "6"
  "Intelligence": !!int "6"
  "Strength": !!int "4"
"skillsaves":
  "Insight": !!int "6"
  "Perception": !!int "6"
  "Arcana": !!int "6"
"senses": "passive Perception 16"
"languages": "Common, Gith"
"cr": "6"
"traits":
- "desc": "The githzerai casts one of the following spells, requiring no spell components\
    \ and using Wisdom as the spellcasting ability (spell save DC 14):\n\nAt will:\
    \ [Mage Hand](3-Mechanics/CLI/spells/mage-hand-xphb.md) (the hand is Invisible)\n\
    \n1/day each: [Phantasmal Killer](3-Mechanics/CLI/spells/phantasmal-killer-xphb.md)\
    \ (level 6 version), [Plane Shift](3-Mechanics/CLI/spells/plane-shift-xphb.md),\
    \ [See Invisibility](3-Mechanics/CLI/spells/see-invisibility-xphb.md)"
  "name": "Spellcasting"
- "desc": "The githzerai casts [Jump](3-Mechanics/CLI/spells/jump-xphb.md), requiring\
    \ no spell components and using the same spellcasting ability as Spellcasting.\n\
    \n2/day: [Jump](3-Mechanics/CLI/spells/jump-xphb.md)"
  "name": "Psi-Powered Leap (2/Day)"
- "desc": "The githzerai casts [Feather Fall](3-Mechanics/CLI/spells/feather-fall-xphb.md)\
    \ or [Shield](3-Mechanics/CLI/spells/shield-xphb.md) in response to the spell's\
    \ trigger, requiring no spell components and using the same spellcasting ability\
    \ as Spellcasting.\n\n2/day: [Feather Fall](3-Mechanics/CLI/spells/feather-fall-xphb.md),\
    \ [Shield](3-Mechanics/CLI/spells/shield-xphb.md)"
  "name": "Psionic Defense (2/Day)"
"actions":
- "desc": "The githzerai makes two Psi Strike attacks."
  "name": "Multiattack"
- "desc": "Melee Attack Roll: +7, reach 5 ft. Hit: 11 (2d6 + 4) Bludgeoning\
    \ damage plus 13 (3d8) Psychic damage."
  "name": "Psi Strike"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/aberration/token/githzerai-zerth-xmm.webp"
```{ #statblock}


## Environment

planar, limbo