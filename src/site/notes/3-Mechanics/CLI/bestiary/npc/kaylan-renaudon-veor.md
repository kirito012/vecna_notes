---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/npc/kaylan-renaudon-veor/","tags":["ttrpg-cli/compendium/src/5e/veor","ttrpg-cli/monster/cr/13","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/undead/shapechanger"],"noteIcon":""}
---

# [Kaylan Renaudon](3-Mechanics\CLI\bestiary\npc/kaylan-renaudon-veor.md)
*Source: Vecna: Eve of Ruin*  

```statblock
"name": "Kaylan Renaudon (VEoR)"
"size": "Medium"
"type": "undead"
"subtype": "shapechanger"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "144"
"hit_dice": "17d8 + 68"
"stats":
- !!int "18"
- !!int "18"
- !!int "18"
- !!int "17"
- !!int "15"
- !!int "18"
"speed": "30 ft."
"saves":
  "Charisma": !!int "9"
  "Dexterity": !!int "9"
  "Wisdom": !!int "7"
"skillsaves":
  "Stealth": !!int "9"
  "Perception": !!int "7"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "darkvision 120 ft., passive Perception 17"
"languages": "the languages it knew in life"
"cr": "13"
"traits":
- "desc": "If Kaylan isn't in sunlight or running water, it can use its action to\
    \ polymorph into a Tiny bat or a Medium cloud of mist, or back into its true form.\n\
    \nWhile in bat form, Kaylan can't speak, its walking speed is 5 feet, and it has\
    \ a flying speed of 30 feet. Its statistics, other than its size and speed, are\
    \ unchanged. Anything it is wearing transforms with it, but nothing it is carrying\
    \ does. It reverts to its true form if it dies.\n\nWhile in mist form, Kaylan\
    \ can't take any actions, speak, or manipulate objects. It is weightless, has\
    \ a flying speed of 20 feet, can hover, and can enter a hostile creature's space\
    \ and stop there. In addition, if air can pass through a space, the mist can do\
    \ so without squeezing, and it can't pass through water. It has advantage on Strength,\
    \ Dexterity, and Constitution saving throws, and it is immune to all nonmagical\
    \ damage, except the damage it takes from sunlight."
  "name": "Shapechanger"
- "desc": "If Kaylan fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "When it drops to 0 hit points outside its resting place, Kaylan transforms\
    \ into a cloud of mist (as in the Shapechanger trait) instead of falling [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious),\
    \ provided that it isn't in sunlight or running water. If it can't transform,\
    \ it is destroyed.\n\nWhile it has 0 hit points in mist form, it can't revert\
    \ to its vampire form, and it must reach its resting place within 2 hours or be\
    \ destroyed. Once in its resting place, it reverts to its vampire form. It is\
    \ then [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed) until it regains\
    \ at least 1 hit point. After spending 1 hour in its resting place with 0 hit\
    \ points, it regains 1 hit point."
  "name": "Misty Escape"
- "desc": "Kaylan regains 20 hit points at the start of its turn if it has at least\
    \ 1 hit point and isn't in sunlight or running water. If Kaylan takes radiant\
    \ damage or damage from holy water, this trait doesn't function at the start of\
    \ Kaylan's next turn."
  "name": "Regeneration"
- "desc": "Kaylan can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
- "desc": "Kaylan has the following flaws:\n\nForbiddance. Kaylan can't enter a\
    \ residence without an invitation from one of the occupants.\n\nHarmed by Running\
    \ Water. Kaylan takes 20 acid damage if it ends its turn in running water.\n\n\
    Stake to the Heart. If a piercing weapon made of wood is driven into Kaylan's\
    \ heart while Kaylan is [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
    \ in its resting place, Kaylan is [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed)\
    \ until the stake is removed.\n\nSunlight Hypersensitivity. Kaylan takes 20\
    \ radiant damage when it starts its turn in sunlight. While in sunlight, it has\
    \ disadvantage on attack rolls and ability checks."
  "name": "Vampire Weaknesses"
"actions":
- "desc": "Kaylan makes two attacks, only one of which can be a bite attack."
  "name": "Multiattack (Vampire Form Only)"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one creature. Hit: 8 (1d8\
    \ + 4) bludgeoning damage. Instead of dealing damage, Kaylan can grapple the target\
    \ (escape DC 18)."
  "name": "Unarmed Strike (Vampire Form Only)"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one willing creature, or\
    \ a creature that is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
    \ by Kaylan, [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated),\
    \ or [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained). Hit: 7 (1d6\
    \ + 4) piercing damage plus 10 (3d6) necrotic damage. The target's hit point maximum\
    \ is reduced by an amount equal to the necrotic damage taken, and Kaylan regains\
    \ hit points equal to that amount. The reduction lasts until the target finishes\
    \ a long rest. The target dies if this effect reduces its hit point maximum to\
    \ 0. A humanoid slain in this way and then buried in the ground rises the following\
    \ night as a [vampire spawn](3-Mechanics/CLI/bestiary/undead/vampire-spawn.md)\
    \ under Kaylan's control."
  "name": "Bite (Bat or Vampire Form Only)"
- "desc": "Kaylan targets one humanoid it can see within 30 feet of it. If the target\
    \ can see Kaylan, the target must succeed on a DC 17 Wisdom saving throw against\
    \ this magic or be [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed) by Kaylan.\
    \ The [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed) target regards Kaylan\
    \ as a trusted friend to be heeded and protected. Although the target isn't under\
    \ Kaylan's control, it takes Kaylan's requests or actions in the most favorable\
    \ way it can, and it is a willing target for Kaylan's bite attack.\n\nEach time\
    \ Kaylan or Kaylan's companions do anything harmful to the target, it can repeat\
    \ the saving throw, ending the effect on itself on a success. Otherwise, the effect\
    \ lasts 24 hours or until Kaylan is destroyed, is on a different plane of existence\
    \ than the target, or takes a bonus action to end the effect."
  "name": "Charm"
- "desc": "Kaylan magically calls 2d4 swarms of [bats](3-Mechanics/CLI/bestiary/beast/swarm-of-bats.md)\
    \ or [rats](3-Mechanics/CLI/bestiary/beast/swarm-of-rats.md), provided that the\
    \ sun isn't up. While outdoors, Kaylan can call 3d6 [wolves](3-Mechanics/CLI/bestiary/beast/wolf.md)\
    \ instead. The called creatures arrive in 1d4 rounds, acting as allies of Kaylan\
    \ and obeying its spoken commands. The beasts remain for 1 hour, until Kaylan\
    \ dies, or until Kaylan dismisses them as a bonus action."
  "name": "Children of the Night (1/Day)"
"legendary_actions":
- "desc": "Kaylan moves up to its speed without provoking opportunity attacks."
  "name": "Move"
- "desc": "Kaylan makes one unarmed strike."
  "name": "Unarmed Strike"
- "desc": "Kaylan makes one bite attack."
  "name": "Bite (Costs 2 Actions)"
"source":
- "VEoR"
"image": "3-Mechanics/CLI/bestiary/npc/token/kaylan-renaudon-veor.webp"
```
^statblock