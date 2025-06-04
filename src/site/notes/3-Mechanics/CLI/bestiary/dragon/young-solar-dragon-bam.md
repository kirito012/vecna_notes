---
{"dg-publish":true,"permalink":"/3-mechanics/cli/bestiary/dragon/young-solar-dragon-bam/","tags":["ttrpg-cli/compendium/src/5e/bam","ttrpg-cli/monster/cr/9","ttrpg-cli/monster/size/large","ttrpg-cli/monster/type/dragon"],"noteIcon":""}
---

# [Young Solar Dragon](3-Mechanics\CLI\bestiary\dragon/young-solar-dragon-bam.md)
*Source: Boo's Astral Menagerie p. 53, Light of Xaryxis*  

A solar dragon (also known as a radiant dragon or a sun dragon) is born in the heart of a star. It divides its time outside its lair between patrolling its territory and hunting for food. The dragon has a serpentine body, a pair of ventral limbs ending in long fins, nebulous wings that give off light, and gleaming, multicolored scales. It can see clearly even in blindingly bright light.

Solar dragons are fond of treasure just as all dragons are, but in the airless void of Wildspace, they value food even more. Solar dragons typically feed on kindori, scavvers, and other forms of space-dwelling wildlife. A solar dragon might mistake a distant spelljamming ship for possible prey and come within range of the vessel's weapons before realizing its error and veering away. A wise or experienced captain won't take the dragon's approach as a sign of hostility. Solar dragons that are fired upon have been known to batter the offending ships to flinders.

Solar dragons are territorial carnivores, and they behave accordingly. A young solar dragon might lay claim to an asteroid belt, where food is relatively plentiful, while an ancient solar dragon might consider an entire Wildspace system its hunting ground. They tend to give a wide berth to Humanoid folk, whom they find violent and tiresome. Trespassers who are detected in a solar dragon's lair can expect to be met with resistance, followed by hostility, especially if the lair contains eggs.

A solar dragon egg has an obsidian shell, shiny black and opaque. When an egg is close to hatching, the shell becomes translucent, allowing the light from the unborn wyrmling's wings to shine through.

```statblock
"name": "Young Solar Dragon (BAM)"
"size": "Large"
"type": "dragon"
"alignment": "typically  Neutral"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "178"
"hit_dice": "17d10 + 85"
"stats":
- !!int "20"
- !!int "15"
- !!int "20"
- !!int "13"
- !!int "14"
- !!int "12"
"speed": "20 ft., fly 60 ft. (hover)"
"saves":
  "Charisma": !!int "5"
  "Dexterity": !!int "6"
  "Wisdom": !!int "6"
  "Constitution": !!int "9"
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "10"
"damage_immunities": "radiant"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded)"
"senses": "darkvision 120 ft., passive Perception 20"
"languages": "Draconic"
"cr": "9"
"traits":
- "desc": "The dragon doesn't provoke opportunity attacks when it flies out of an\
    \ enemy's reach."
  "name": "Flyby"
- "desc": "The dragon doesn't require air."
  "name": "Unusual Nature"
"actions":
- "desc": "The dragon makes one Bite attack and one Tail attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 12\
    \ (2d6 + 5) piercing damage plus 7 (2d6) radiant damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +9 to hit, reach 15 ft., one target. Hit: 8\
    \ (1d6 + 5) bludgeoning damage."
  "name": "Tail"
- "desc": "The dragon exhales a flashing mote of radiant energy that travels to a\
    \ point the dragon can see within 120 feet of itself, then blossoms into a 20-foot-radius\
    \ sphere centered on that point. Each creature in the sphere must make a DC 17\
    \ Constitution saving throw, taking 44 (8d10) radiant damage on a failed save,\
    \ or half as much damage on a successful one."
  "name": "Photonic Breath (Recharge 5-6)"
"source":
- "BAM"
- "LoX"
"image": "3-Mechanics/CLI/bestiary/dragon/token/young-solar-dragon-bam.webp"
```
^statblock