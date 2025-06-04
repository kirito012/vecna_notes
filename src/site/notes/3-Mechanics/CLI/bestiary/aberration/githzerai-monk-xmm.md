---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/aberration/githzerai-monk-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/2","ttrpg-cli/monster/environment/limbo","ttrpg-cli/monster/environment/planar","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/aberration/gith"],"noteIcon":""}
---

# [Githzerai Monk](3-Mechanics\CLI\bestiary\aberration/githzerai-monk-xmm.md)
*Source: Monster Manual (2024) p. 136*  

Githzerai monks pursue control of their minds by honing their physical and psionic talents. They might be found beyond githzerai sanctuaries, testing themselves amid the dangerous extremes of the multiverse.

## Githzerai

*Explorers at Reality's Extremes*

- **Habitat.** Planar (Limbo)  
- **Treasure.** Arcana, Individual  

Githzerai are gaunt, humanlike beings, physically identical to githyanki. They share a history with githyanki as creatures physically and psychically transformed by mind flayers (see the "Githyanki" section). Githzerai know that in body and mind, their species was manipulated by their former illithid oppressors. Rather than giving in to this programming, githzerai follow the teachings of their first leader, Zerthimon, and reshape their minds and bodies to find peace.

Githzerai psychically create serene, hidden sanctuaries in chaotic reaches of the multiverse. Most of these redoubts drift through the chaotic plane of Limbo, but githzerai conclaves can also be found in the Abyss, the Elemental Chaos, and the Feywild. Githzerai create these cloisters to hone their psionic abilities, to gain insights from the multiverse, and to avoid githyanki and mind flayers.

### Adventures with Gith

Characters might be drawn into conflicts involving githzerai and githyanki in various ways. Roll on or choose a result from the Gith Conflicts table to inspire adventures featuring these age-old rivals.

**Gith Conflicts**

`dice: [](githzerai-monk-xmm.md#^gith-conflicts)`

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
"name": "Githzerai Monk (XMM)"
"size": "Medium"
"type": "aberration"
"subtype": "gith"
"alignment": "Lawful Neutral"
"ac": !!int "14"
"hp": !!int "38"
"hit_dice": "7d8 + 7"
"stats":
- !!int "12"
- !!int "15"
- !!int "12"
- !!int "13"
- !!int "14"
- !!int "10"
"speed": "40 ft."
"saves":
  "Dexterity": !!int "4"
  "Wisdom": !!int "4"
  "Intelligence": !!int "3"
  "Strength": !!int "3"
"skillsaves":
  "Insight": !!int "4"
  "Perception": !!int "4"
"senses": "passive Perception 14"
"languages": "Common, Gith"
"cr": "2"
"traits":
- "desc": "The githzerai casts one of the following spells, requiring no spell components\
    \ and using Wisdom as the spellcasting ability:\n\nAt will: [Mage Hand](3-Mechanics/CLI/spells/mage-hand-xphb.md)\
    \ (the hand is Invisible)\n\n1/day: [See Invisibility](3-Mechanics/CLI/spells/see-invisibility-xphb.md)"
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
- "desc": "Melee Attack Roll: +4, reach 5 ft. Hit: 6 (1d8 + 2) Bludgeoning\
    \ damage plus 9 (2d8) Psychic damage."
  "name": "Psi Strike"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/aberration/token/githzerai-monk-xmm.webp"
```{ #statblock}


## Environment

planar, limbo