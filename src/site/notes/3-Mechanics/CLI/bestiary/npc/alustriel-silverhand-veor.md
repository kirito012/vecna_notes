---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/npc/alustriel-silverhand-veor/","tags":["ttrpg-cli/compendium/src/5e/veor","ttrpg-cli/monster/cr/21","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/humanoid/human","ttrpg-cli/monster/type/humanoid/wizard"],"noteIcon":""}
---

# [Alustriel Silverhand](3-Mechanics\CLI\bestiary\npc/alustriel-silverhand-veor.md)
*Source: Vecna: Eve of Ruin p. 242*  

Lady Alustriel Silverhand, called the Shining Lady, has been an influential wizard and proponent of good across Toril for centuries. Alustriel is one of the Seven Sisters—immortal daughters of Mystra, the god of magic. The divine energy Mystra passed to Alustriel grants Alustriel incredible power over arcane magic.

Alustriel's youthful appearance as a human woman with silver hair gives no hint of her supernaturally extended life span. She typically wears long robes and wields a unicorn-headed staff, her*Staff of Silverymoon*.

## Personality

Alustriel's primary concerns are to spread kindness, reward virtue, and promote a culture of compassion throughout the multiverse. She is good at building alliances and quick to intervene when she senses a threat to the forces of good. She has traveled far and established safe houses across the planes—such as her sanctum in the city of Sigil. Alustriel doesn't seek personal glory or wealth; her style of influencing the cosmos is quiet yet steady.

## History

Like other Chosen of Mystra, Alustriel is concerned with preserving the Weave, the primary incarnation of magic that permeates Toril. She believes that the Weave favors those who act with mercy and compassion, seeks to deliver lives of security for all, and bolsters people's efforts when they seek to right wrongs and combat evil.

Nowhere are Alustriel and her deeds better known than in the Silver Marches and its capital, Silverymoon. Alustriel ruled Silverymoon for centuries, once disguised as a wizard named Elué Dualen and then later in her true form. She helped create Silverymoon's famous Moonbridge and cofounded the Lady's College, the first school in Faerûn for mages as students rather than as apprentices in service.

Alustriel stepped down as Silverymoon's high mage more than a century ago. Her son, Methrammar Aerasumé, now leads the city and works to uphold his mother's legacy.

Alustriel has partaken in countless adventures before and after her tenure as Silverymoon's high mage. She has befriended famous adventurers such as Drizzt Do'Urden, worked with prominent organizations like the Harpers, and helped prevent or undo many kinds of evil.

```statblock
"name": "Alustriel Silverhand (VEoR)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, wizard"
"alignment": "Chaotic Good"
"ac": !!int "15"
"ac_class": "18 with [mage armor](3-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "272"
"hit_dice": "32d8 + 128"
"stats":
- !!int "12"
- !!int "20"
- !!int "18"
- !!int "24"
- !!int "23"
- !!int "22"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "13"
  "Intelligence": !!int "14"
  "Constitution": !!int "11"
"skillsaves":
  "Religion": !!int "14"
  "Insight": !!int "13"
  "History": !!int "14"
  "Arcana": !!int "14"
"damage_resistances": "radiant"
"damage_immunities": "poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "passive Perception 16"
"languages": "Common, Draconic, Elvish"
"cr": "21"
"traits":
- "desc": "Alustriel casts one of the following spells, using Intelligence as the\
    \ spellcasting ability (spell save DC 22):\n\nAt will: [Dancing Lights](3-Mechanics/CLI/spells/dancing-lights.md),\
    \ [Detect Magic](3-Mechanics/CLI/spells/detect-magic.md), [Mage Armor](3-Mechanics/CLI/spells/mage-armor.md)\
    \ (self only), [Mage Hand](3-Mechanics/CLI/spells/mage-hand.md)\n\n1/day each:\
    \ [Telepathy](3-Mechanics/CLI/spells/telepathy.md), [Teleport](3-Mechanics/CLI/spells/teleport.md),\
    \ [Time Stop](3-Mechanics/CLI/spells/time-stop.md)\n\n2/day each: [Detect\
    \ Thoughts](3-Mechanics/CLI/spells/detect-thoughts.md), [Dispel Magic](3-Mechanics/CLI/spells/dispel-magic.md),\
    \ [Tongues](3-Mechanics/CLI/spells/tongues.md)"
  "name": "Spellcasting"
- "desc": "Whenever a creature on the same plane of existence as Alustriel speaks\
    \ Alustriel's name, Alustriel hears her name and the next nine words the speaker\
    \ utters."
  "name": "Ear of the Chosen"
- "desc": "If Alustriel fails a saving throw, she can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Alustriel carries a magic staff known as the Staff of Silverymoon. In the\
    \ hands of anyone other than Alustriel, the Staff of Silverymoon is a [Staff of\
    \ Power](3-Mechanics/CLI/items/staff-of-power.md)."
  "name": "Special Equipment"
"actions":
- "desc": "Alustriel makes three Staff of Silverymoon attacks or two Reproving Ray\
    \ attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +12 to hit, reach 5 ft., one target. Hit: 14 (2d8\
    \ + 5) bludgeoning damage plus 38 (7d10) radiant damage."
  "name": "Staff of Silverymoon"
- "desc": "Ranged Spell Attack: +14 to hit, range 120 ft., one target. Hit: 65\
    \ (9d12 + 7) force damage, and if the target is a creature, it must make a DC\
    \ 22 Charisma saving throw. On a failed save, the target has the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
    \ condition until the start of Alustriel's next turn. On a successful save, the\
    \ target's speed is reduced by 10 feet until the start of Alustriel's next turn."
  "name": "Reproving Ray"
- "desc": "Alustriel summons a 60-foot cone of silver fire. Each creature in that\
    \ area must make a DC 22 Dexterity saving throw, taking 77 (14d10) radiant damage\
    \ on a failed save or half as much damage on a successful one. Additionally, Alustriel\
    \ or one creature of her choice within 60 feet of her then regains 10 (3d6) hit\
    \ points."
  "name": "Argent Blaze (Requires Silver Fire)"
"bonus_actions":
- "desc": "Brilliant silver fire harmlessly wreathes Alustriel and empowers her. The\
    \ silver fire lasts for 1 hour or until she has the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
    \ condition or uses another bonus action to quench it. While wreathed in silver\
    \ fire, Alustriel gains truesight within 30 feet and can use her Argent Blaze\
    \ action. In addition, Alustriel is unaffected by magic that would ascertain her\
    \ alignment, creature type, thoughts, or truthfulness."
  "name": "Silver Fire (2/Day)"
"reactions":
- "desc": "Alustriel interrupts a creature she can see within 60 feet of herself that\
    \ is casting a spell. If the spell is 5th level or lower, it fails and has no\
    \ effect. If the spell is 6th level or higher, Alustriel makes an Intelligence\
    \ check (DC 10 plus the spell's level). On a successful check, the spell fails\
    \ and has no effect. Whatever the spell's level, the caster takes 11 (2d10) radiant\
    \ damage if the spell fails."
  "name": "Shining Counterspell"
"source":
- "VEoR"
"image": "3-Mechanics/CLI/bestiary/npc/token/alustriel-silverhand-veor.webp"
```
^statblock