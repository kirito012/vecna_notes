---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/humanoid/cultist-fanatic-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/2","ttrpg-cli/monster/environment/any","ttrpg-cli/monster/size/small-or-medium","ttrpg-cli/monster/type/humanoid"],"noteIcon":""}
---

# [Cultist Fanatic](3-Mechanics\CLI\bestiary\humanoid/cultist-fanatic-xmm.md)
*Source: Monster Manual (2024) p. 85. Available in the Free Rules (2024)*  

Cultist fanatics lead small cults or cells within larger cults. They're privy to more of a cult's mysteries than lower-ranking cultists are, granting them access to magical powers from their patrons.

## Cultists

*Doomsayers and Fanatics*

- **Habitat.** Any  
- **Treasure.** Individual, Relics  

Cultists use magic and extreme measures to spread radical beliefs. Some privately pursue esoteric secrets, while others form shadowy cabals seeking to bring about terrifying ends. Cultists often follow obscure mystical traditions or obsess over interpretations of ancient prophecies. They might worship supernatural patrons—deities, otherworldly creatures, manipulative alien minds, or stranger forces. Roll on or choose a result from the Cultist Agendas table to inspire what a cultist seeks to achieve.

**Cultist Agendas**

`dice: [](cultist-fanatic-xmm.md#^cultist-agendas)`

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

`dice: [](cultist-fanatic-xmm.md#^cult-symbols)`

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
"name": "Cultist Fanatic (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral"
"ac": !!int "13"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"stats":
- !!int "11"
- !!int "14"
- !!int "12"
- !!int "10"
- !!int "14"
- !!int "13"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "4"
"skillsaves":
  "Deception": !!int "3"
  "Religion": !!int "2"
  "Persuasion": !!int "3"
"senses": "passive Perception 12"
"languages": "Common"
"cr": "2"
"traits":
- "desc": "The cultist casts one of the following spells, using Wisdom as the spellcasting\
    \ ability (spell save DC 12, +4 to hit with spell attacks):\n\nAt will:\
    \ [Light](3-Mechanics/CLI/spells/light-xphb.md), [Thaumaturgy](3-Mechanics/CLI/spells/thaumaturgy-xphb.md)\n\
    \n1/day: [Hold Person](3-Mechanics/CLI/spells/hold-person-xphb.md)\n\n2/day:\
    \ [Command](3-Mechanics/CLI/spells/command-xphb.md)"
  "name": "Spellcasting"
- "desc": "The cultist casts the [Spiritual Weapon](3-Mechanics/CLI/spells/spiritual-weapon-xphb.md)\
    \ spell, using the same spellcasting ability as Spellcasting.\n\n2/day: [Spiritual\
    \ Weapon](3-Mechanics/CLI/spells/spiritual-weapon-xphb.md)"
  "name": "Spiritual Weapon (2/Day)"
"actions":
- "desc": "Melee Attack Roll: +4, reach 5 ft. Hit: 6 (1d8 + 2) Slashing damage\
    \ plus 7 (2d6) Necrotic damage."
  "name": "Pact Blade"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/cultist-fanatic-xmm.webp"
```{ #statblock}


## Environment

any