---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/dragon/black-dragon-wyrmling-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/2","ttrpg-cli/monster/environment/swamp","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/dragon/chromatic"],"noteIcon":""}
---

# [Black Dragon Wyrmling](3-Mechanics\CLI\bestiary\dragon/black-dragon-wyrmling-xmm.md)
*Source: Monster Manual (2024) p. 38. Available in the Free Rules (2024)*  

Black dragon wyrmlings lurk in bogs and polluted waterways, hunting for prey and weaker creatures to overpower. While older wyrmlings eventually seek their own territories, recently hatched ones might hunt one another, seeking dominance over their clutch and slaying rivals they can't subjugate.

## Black Dragons

*Dragons of Decay and Despair*

- **Habitat.** Swamp  
- **Treasure.** Relics  

Black dragons delight in suffering and ruin. While other chromatic dragons scheme for power and wealth, these dragons seek to tear down all they see and rule over what remains.

Black dragons are terrifying creatures with curved horns and withered visages suggestive of fiendish skulls. They typically inhabit stagnant swamps, crumbling ruins, or places of magical or environmental corruption. Their acid breath scars their domains, eroding the features from ancient statues and leaving nature with festering wounds.

Black dragons hoard tarnished symbols of hope and relics of fallen empires. The more sought-after the treasure, the more black dragons prize it—particularly if they were responsible for it being lost.

### Black Dragon Lairs

Black dragons lurk in dismal ruins, polluted bogs, or other sites gripped by decay.

```statblock
"name": "Black Dragon Wyrmling (XMM)"
"size": "Medium"
"type": "dragon"
"subtype": "chromatic"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"stats":
- !!int "15"
- !!int "14"
- !!int "13"
- !!int "10"
- !!int "11"
- !!int "13"
"speed": "30 ft., fly 60 ft., swim 30 ft."
"saves":
  "Dexterity": !!int "4"
  "Wisdom": !!int "2"
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "4"
"damage_immunities": "acid"
"senses": "blindsight 10 ft., darkvision 60 ft., passive Perception 14"
"languages": "Draconic"
"cr": "2"
"traits":
- "desc": "The dragon can breathe air and water."
  "name": "Amphibious"
"actions":
- "desc": "The dragon makes two Rend attacks."
  "name": "Multiattack"
- "desc": "Melee Attack Roll: +4, reach 5 ft. Hit: 5 (1d6 + 2) Slashing damage\
    \ plus 2 (1d4) Acid damage."
  "name": "Rend"
- "desc": "Dexterity Saving Throw: DC 11, each creature in a 15-foot-long, 5-foot-wide\
    \ [Line](3-Mechanics/CLI/rules/variant-rules/line-area-of-effect-xphb.md). Failure:\
    \ 22 (5d8) Acid damage. Success: Half damage."
  "name": "Acid Breath (Recharge 5-6)"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/dragon/token/black-dragon-wyrmling-xmm.webp"
```{ #statblock}


## Environment

swamp