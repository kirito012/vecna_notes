---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/dragon/young-red-dragon-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/10","ttrpg-cli/monster/environment/hill","ttrpg-cli/monster/environment/mountain","ttrpg-cli/monster/size/large","ttrpg-cli/monster/type/dragon/chromatic"],"noteIcon":""}
---

# [Young Red Dragon](3-Mechanics\CLI\bestiary\dragon/young-red-dragon-xmm.md)
*Source: Monster Manual (2024) p. 254*  

Young red dragons number among the most unpredictable of their kind. They seek territories rich with treasures and potential followers, raiding, burning, and slaughtering to enforce their will. Unless these dragons meet significant resistance, they cement their power and begin reigns of terror that can last for centuries.

## Red Dragons

*Dragons of Greed and Devastation*

- **Habitat.** Hill, Mountain  
- **Treasure.** Any  

Red dragons take whatever they desire and burn to ash anything that stands in their way. These chromatic dragons endlessly desire more—more magic, territory, treasure, or whatever else inflames their cruel ambitions.

Red dragons make their lairs amid perilous cliffs and volcanoes. Within, they amass and fiercely protect hoards of treasure, and many have perfect recall of the hoards' contents and the locations of all they've collected. Should anything go missing, red dragons fly into rages. They don't rest until their treasures are returned and the thieves have burned.

Red dragons believe themselves to be the greatest of all dragons and, by extension, the greatest of all creatures. To them, pillaging and conquering are their right—treasures can find no more honored place than in their hoards, and other creatures are privileged to serve them.

### Red Dragon Lairs

Red dragons make their lairs in smoldering, unapproachable places such as volcanic mountains, burning wastelands, and ruins they've stolen from other creatures.

```statblock
"name": "Young Red Dragon (XMM)"
"size": "Large"
"type": "dragon"
"subtype": "chromatic"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"hp": !!int "178"
"hit_dice": "17d10 + 85"
"stats":
- !!int "23"
- !!int "10"
- !!int "21"
- !!int "14"
- !!int "11"
- !!int "19"
"speed": "40 ft., climb 40 ft., fly 80 ft."
"saves":
  "Dexterity": !!int "4"
  "Wisdom": !!int "4"
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "8"
"damage_immunities": "fire"
"senses": "blindsight 30 ft., darkvision 120 ft., passive Perception 18"
"languages": "Common, Draconic"
"cr": "10"
"actions":
- "desc": "The dragon makes three Rend attacks."
  "name": "Multiattack"
- "desc": "Melee Attack Roll: +10, reach 10 ft. Hit: 13 (2d6 + 6) Slashing\
    \ damage plus 3 (1d6) Fire damage."
  "name": "Rend"
- "desc": "Dexterity Saving Throw: DC 17, each creature in a 30-foot [Cone](3-Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md).\
    \ Failure: 56 (16d6) Fire damage. Success: Half damage."
  "name": "Fire Breath (Recharge 5-6)"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/dragon/token/young-red-dragon-xmm.webp"
```{ #statblock}


## Environment

hill, mountain