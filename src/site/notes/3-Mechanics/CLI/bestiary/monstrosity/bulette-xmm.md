---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/monstrosity/bulette-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/5","ttrpg-cli/monster/environment/grassland","ttrpg-cli/monster/environment/hill","ttrpg-cli/monster/environment/mountain","ttrpg-cli/monster/size/large","ttrpg-cli/monster/type/monstrosity"],"noteIcon":""}
---

# [Bulette](3-Mechanics\CLI\bestiary\monstrosity/bulette-xmm.md)
*Source: Monster Manual (2024) p. 63*  

Bulettes range under vast territories. They often threaten animal herds, and they can wipe out whole farming communities.

## Bulettes

*Ravenous, Subsurface Land Sharks*

- **Habitat.** Grassland, Hill, Mountain  
- **Treasure.** None  

Also called "land sharks," bulettes are single-minded predators that burrow under, leap over, and burst through obstacles in pursuit of their quarry. They burrow rapidly just belowground. On sensing movement, they erupt from below, attempting to catch prey in their oversize maws.

```statblock
"name": "Bulette (XMM)"
"size": "Large"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "17"
"hp": !!int "94"
"hit_dice": "9d10 + 45"
"stats":
- !!int "19"
- !!int "11"
- !!int "21"
- !!int "2"
- !!int "10"
- !!int "5"
"speed": "40 ft., burrow 40 ft."
"skillsaves":
  "Perception": !!int "6"
"senses": "darkvision 60 ft., tremorsense 120 ft., passive Perception 16"
"languages": ""
"cr": "5"
"actions":
- "desc": "The bulette makes two Bite attacks."
  "name": "Multiattack"
- "desc": "Melee Attack Roll: +7, reach 5 ft. Hit: 17 (2d12 + 4) Piercing\
    \ damage."
  "name": "Bite"
- "desc": "The bulette spends 5 feet of movement to jump to a space within 15 feet\
    \ that contains one or more Large or smaller creatures. Dexterity Saving Throw:\
    \ DC 15, each creature in the bulette's destination space. Failure: 19 (3d12)\
    \ Bludgeoning damage, and the target has the [Prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
    \ condition. Success: Half damage, and the target is pushed 5 feet straight\
    \ away from the bulette."
  "name": "Deadly Leap"
"bonus_actions":
- "desc": "The bulette jumps up to 30 feet by spending 10 feet of movement."
  "name": "Leap"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/bulette-xmm.webp"
```{ #statblock}


## Environment

grassland, hill, mountain