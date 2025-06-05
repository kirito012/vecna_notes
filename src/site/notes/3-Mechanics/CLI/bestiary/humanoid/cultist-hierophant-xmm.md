---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/humanoid/cultist-hierophant-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/10","ttrpg-cli/monster/environment/any","ttrpg-cli/monster/size/small-or-medium","ttrpg-cli/monster/type/humanoid"],"noteIcon":""}
---

# [Cultist Hierophant](3-Mechanics\CLI\bestiary\humanoid/cultist-hierophant-xmm.md)
*Source: Monster Manual (2024) p. 85*  

Cultist hierophants are leaders who oversee the lives of their underlings, dictate the edicts of the cult, and interpret their patron's will. They possess supernatural powers gained from the cult's patron, supernatural sources, or the power of their own fanaticism. These leaders know their cult's deepest secrets and often control strange relics, mystical sites, and monstrous servants.

## Cultists

*Doomsayers and Fanatics*

- **Habitat.** Any  
- **Treasure.** Individual, Relics  

Cultists use magic and extreme measures to spread radical beliefs. Some privately pursue esoteric secrets, while others form shadowy cabals seeking to bring about terrifying ends. Cultists often follow obscure mystical traditions or obsess over interpretations of ancient prophecies. They might worship supernatural patrons—deities, otherworldly creatures, manipulative alien minds, or stranger forces. Roll on or choose a result from the Cultist Agendas table to inspire what a cultist seeks to achieve.

**Cultist Agendas**

`dice: [](cultist-hierophant-xmm.md#^cultist-agendas)`

| dice: 1d6 | The Cultist Strives To... |
|-----------|---------------------------|
| 1 | Bring about the end of a dominant order, an age, or the world. |
| 2 | Burn away the comfortable lies of reality, revealing forgotten or terrible truths. |
| 3 | Expand their faith though mind control or supernatural coercion. |
| 4 | Make global changes, like sinking the land or awakening volcanoes. |
| 5 | Remake life on a mass scale, altering other creatures' bodies or spiritual beings. |
| 6 | Summon their deity or its herald, weapon, or realm into their world. |{ #cultist-agendas}


### Occult Symbols

Cults often identify with symbols that exemplify their beliefs. Such symbols might mark objects important to the cult, as well as the dress and bodies of cultists themselves. These symbols might be broadly understandable, or they might have meaning only to cultists. Roll twice on or choose results from the Cult Symbols table to inspire a cult's icons.

**Cult Symbols**

`dice: [](cultist-hierophant-xmm.md#^cult-symbols)`

| dice: 1d10 | The Symbol Is... | Depicted As... |
|------------|------------------|----------------|
| 1 | An alchemical sign | A calendar or map |
| 2 | An animal | A crest or as heraldry |
| 3 | A celestial body | An elaborate diagram |
| 4 | A deity's icon | A metaphorical image |
| 5 | An element | A mystical being |
| 6 | An eye | Part of an equation |
| 7 | A geometric shape | A repeating pattern |
| 8 | A letter or number | A series of scratches |
| 9 | Part of a monster | A simple pictogram |
| 10 | A skull | A weapon or tool |{ #cult-symbols}


### Cult Members

Cults often form hierarchies around a charismatic or domineering leader. While cult members might work independently, they take their orders from superiors with greater supernatural powers. 

### Types of Cultists

Cults can organize around any mystical tradition, but many serve supernatural beings. Cult members often have abilities tied to the forces they worship.

> [!quote] A quote from Rites of the Cult of Elemental Evil  
> 
> Dread Tharizdun, power of the Elder Elemental Eye and master of all destructive forces, I am the Champion of Elemental Evil and am ready to carry out your wishes.


```statblock
"name": "Cultist Hierophant (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral"
"ac": !!int "16"
"hp": !!int "144"
"hit_dice": "17d8 + 68"
"stats":
- !!int "14"
- !!int "18"
- !!int "18"
- !!int "13"
- !!int "16"
- !!int "20"
"speed": "30 ft."
"saves":
  "Charisma": !!int "9"
  "Wisdom": !!int "7"
"skillsaves":
  "Religion": !!int "5"
  "Perception": !!int "7"
  "Persuasion": !!int "9"
"senses": "passive Perception 17"
"languages": "Celestial, Common"
"cr": "10"
"traits":
- "desc": "The cultist casts one of the following spells, using Charisma as the spellcasting\
    \ ability (spell save DC 17):\n\nAt will: [Mage Armor](3-Mechanics/CLI/spells/mage-armor-xphb.md)\
    \ (included in AC), [Thaumaturgy](3-Mechanics/CLI/spells/thaumaturgy-xphb.md)\n\
    \n1/day each: [Jallarzi's Storm of Radiance](3-Mechanics/CLI/spells/jallarzis-storm-of-radiance-xphb.md)\
    \ (level 7 version), [Mass Suggestion](3-Mechanics/CLI/spells/mass-suggestion-xphb.md)"
  "name": "Spellcasting"
"actions":
- "desc": "The cultist makes three attacks, using Pact Blade or Radiant Ray in any\
    \ combination."
  "name": "Multiattack"
- "desc": "Melee Attack Roll: +9, reach 5 ft. Hit: 12 (2d6 + 5) Slashing damage\
    \ plus 18 (4d8) Radiant damage."
  "name": "Pact Blade"
- "desc": "Ranged Attack Roll: +9, range 120 ft. Hit: 31 (4d12 + 5) Radiant\
    \ damage."
  "name": "Radiant Ray"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/cultist-hierophant-xmm.webp"
```{ #statblock}


## Environment

any