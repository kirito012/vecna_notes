---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/humanoid/priest-acolyte-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/1-4","ttrpg-cli/monster/environment/any","ttrpg-cli/monster/size/small-or-medium","ttrpg-cli/monster/type/humanoid"],"noteIcon":""}
---

# [Priest Acolyte](3-Mechanics\CLI\bestiary\humanoid/priest-acolyte-xmm.md)
*Source: Monster Manual (2024) p. 247*  

Priest acolytes have great faith but modest magical skill. Some might be trainees in religious organizations or soldiers in zealous armies, while others are faith leaders in small communities or wanderers on pilgrimages.

## Priests

*Arbiters of the Mortal and the Divine*

- **Habitat.** Any  
- **Treasure.** Individual, Relics  

Priests harness the power of faith to work miracles. These religious adherents are as diverse as the faiths they follow. Some obey gods and their servants, while others live by age-old creeds. Belief guides priests' actions and their magic, which they use to shape the world in line with their ideologies.

Roll on or choose a result from the Priest Roles table to inspire different sorts of priests.

**Priest Roles**

`dice: [](priest-acolyte-xmm.md#^priest-roles)`

| dice: 1d10 | The Priest Is... |
|------------|------------------|
| 1 | An ascetic who keeps wicked spirits at bay. |
| 2 | An elder who speaks for the dead. |
| 3 | An exorcist who hunts wicked spirits. |
| 4 | A follower of a god no one has heard of. |
| 5 | A mediator and teacher of traditional ways. |
| 6 | A philosopher devoted to a concept, multiversal view, or plane of existence. |
| 7 | The reincarnation of an ancient faith leader. |
| 8 | A ritualist who uses tinctures and performances to access the divine. |
| 9 | A shaman whose medicines ease many ills. |
| 10 | A zealot who wages war for a divine cause. |{ #priest-roles}


> [!quote]  
> 
> Shining One, light my hours. Enkindle my soul, and inspire my deeds. Chase the shadows from my path, and let me walk in your brilliance.


```statblock
"name": "Priest Acolyte (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral"
"ac": !!int "13"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"stats":
- !!int "14"
- !!int "10"
- !!int "12"
- !!int "10"
- !!int "14"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Medicine": !!int "4"
  "Religion": !!int "2"
"senses": "passive Perception 12"
"languages": "Common"
"cr": "1/4"
"traits":
- "desc": "The priest casts one of the following spells, using Wisdom as the spellcasting\
    \ ability:\n\nAt will: [Light](3-Mechanics/CLI/spells/light-xphb.md), [Thaumaturgy](3-Mechanics/CLI/spells/thaumaturgy-xphb.md)"
  "name": "Spellcasting"
- "desc": "The priest casts [Bless](3-Mechanics/CLI/spells/bless-xphb.md), [Healing\
    \ Word](3-Mechanics/CLI/spells/healing-word-xphb.md), or [Sanctuary](3-Mechanics/CLI/spells/sanctuary-xphb.md),\
    \ using the same spellcasting ability as Spellcasting.\n\n1/day: [Bless](3-Mechanics/CLI/spells/bless-xphb.md),\
    \ [Healing Word](3-Mechanics/CLI/spells/healing-word-xphb.md), [Sanctuary](3-Mechanics/CLI/spells/sanctuary-xphb.md)"
  "name": "Divine Aid (1/Day)"
"actions":
- "desc": "Melee Attack Roll: +4, reach 5 ft. Hit: 5 (1d6 + 2) Bludgeoning\
    \ damage plus 2 (1d4) Radiant damage."
  "name": "Mace"
- "desc": "Ranged Attack Roll: +4, range 60 ft. Hit: 7 (2d6) Radiant damage."
  "name": "Radiant Flame"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/priest-acolyte-xmm.webp"
```{ #statblock}


## Environment

any