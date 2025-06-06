---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/monstrosity/yuan-ti-malison-type-3-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/3","ttrpg-cli/monster/environment/desert","ttrpg-cli/monster/environment/forest","ttrpg-cli/monster/environment/swamp","ttrpg-cli/monster/environment/urban","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/monstrosity"],"noteIcon":""}
---

# [Yuan-ti Malison (Type 3)](3-Mechanics\CLI\bestiary\monstrosity/yuan-ti-malison-type-3-xmm.md)
*Source: Monster Manual (2024) p. 344*  

Malisons exhibit snakelike features that make them deadly in combat.

- **Type 3.** These malisons are human from the waist up, but below that extend the coils of a giant snake.  

Malisons possesses deadly venom, which some manipulate into magical strikes. They can also shape-shift into snakes, helping them to position themselves for surprise attacks or to slither away with nary a trace.

## Yuan-ti

*Power-Hungry Serpentine Conspirators*

- **Habitat.** Desert, Forest, Swamp, Urban  
- **Treasure.** Relics  

Exploiting pacts with sinister supernatural forces, yuan-ti bargain away their humanity for the lethality and predatory deviousness of serpents. From hidden bastions, they manipulate rulers and the wealthy, seeking to control the world. Many yuan-ti possess venomous magic, which often manifests as fangs or striking serpents.

Yuan-ti have humanlike forms with a variety of horrifying serpentine transformations. Some have a scattering of reptilian scales, while others are giants that are more snake than human. Typically, the more snakelike yuan-ti are, the greater esteem they hold among their kind.

Yuan-ti might gain their reptilian features through dangerous supernatural rites. Roll on or choose a result from the Yuan-ti Transformations table to inspire how yuan-ti obtain their serpentine aspects.

**Yuan-ti Transformations**

`dice: [](yuan-ti-malison-type-3-xmm.md#^yuan-ti-transformations)`

| dice: 1d6 | A Yuan-ti Gained Its Snake Features From... |
|-----------|---------------------------------------------|
| 1 | Bargaining parts of its soul to a pantheon of serpentine demigods. |
| 2 | A curse laid on its people in the distant past. |
| 3 | The dream-venom of Merrshaulk, a slumbering snake god. |
| 4 | Experiments by spirit nagas or other yuan-ti. |
| 5 | A ritual involving the skin of a fiendish snake. |
| 6 | Trials to excise its "weak" human parts. |{ #yuan-ti-transformations}


> [!quote] A quote from Last Message of Sorril Venil, Explorer of the Labyrinth of Madness  
> 
> Great magic, twisted and corrupted... Malice beyond reckoning... Flesh reshaped, becoming serpentine horrors...


```statblock
"name": "Yuan-ti Malison (Type 3) (XMM)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Neutral Evil"
"ac": !!int "12"
"hp": !!int "66"
"hit_dice": "12d8 + 12"
"stats":
- !!int "16"
- !!int "14"
- !!int "13"
- !!int "14"
- !!int "16"
- !!int "12"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  "Stealth": !!int "0"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Abyssal, Common, Draconic"
"cr": "3"
"traits":
- "desc": "The yuan-ti casts one of the following spells, requiring no Material components\
    \ and using Wisdom as the spellcasting ability (spell save DC 13):\n\nAt will:\
    \ [Animal Friendship](3-Mechanics/CLI/spells/animal-friendship-xphb.md) (snakes\
    \ only)\n\n2/day: [Suggestion](3-Mechanics/CLI/spells/suggestion-xphb.md)"
  "name": "Spellcasting (Yuan-ti Form Only)"
- "desc": "The yuan-ti has [Advantage](3-Mechanics/CLI/rules/variant-rules/advantage-xphb.md)\
    \ on saving throws against spells and other magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The yuan-ti makes two Poison Burst attacks, and it can use Spellcasting\
    \ to cast [Suggestion](3-Mechanics/CLI/spells/suggestion-xphb.md) if available."
  "name": "Multiattack"
- "desc": "Melee or Ranged Attack Roll: +5, reach 5 ft. or range 120 ft. Hit:\
    \ 12 (2d8 + 3) Poison damage."
  "name": "Poison Burst (Yuan-ti Form Only)"
- "desc": "Strength Saving Throw: DC 13, one Medium or smaller creature within 5\
    \ feet. Failure: 21 (4d8 + 3) Bludgeoning damage. The target has the [Grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
    \ condition (escape DC 13), and it has the [Restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
    \ condition until the grapple ends."
  "name": "Constrict"
"bonus_actions":
- "desc": "The yuan-ti shape-shifts into a Medium snake or returns to its true form.\
    \ If it dies, it stays in its current form. The yuan-ti's game statistics are\
    \ the same in each form, except where noted. Any equipment it is wearing or carrying\
    \ isn't transformed."
  "name": "Shape-Shift"
"source":
- "XMM"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/yuan-ti-malison-type-3-xmm.webp"
```{ #statblock}


## Environment

desert, forest, swamp, urban