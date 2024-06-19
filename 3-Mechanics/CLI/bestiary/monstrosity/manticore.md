---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mm
- monster/cr/3
- monster/environment/arctic
- monster/environment/coastal
- monster/environment/grassland
- monster/environment/hill
- monster/environment/mountain
- monster/size/large
- monster/type/monstrosity
statblock: inline
aliases: ["Manticore"]
---
# [Manticore](3-Mechanics/CLI/bestiary/monstrosity/manticore.md)
*Source: Monster Manual p. 213. Available in the SRD and the Basic Rules.*  

A monster in every sense of the word, a manticore has a vaguely humanoid head, the body of a lion, and the wings of a dragon. A bristling mane stretches down the creature's back, and its long tail ends in a cluster of deadly spikes that can impale prey at impressive range.

## Evil Predators

Manticores are fierce killers that hunt far and wide for prey. They work together to take down particularly large or dangerous creatures, sharing the meal once a kill is made. A manticore begins its attack with a volley of tail spikes, then lands and uses its claws and bite. When outdoors and outnumbered, it uses its wings to stay aloft, attacking from a distance until its spikes are depleted.

A manticore isn't particularly bright, but it possesses a malevolent nature and the ability to converse. In the course of attacking, it denigrates its foes and offers to kill them swiftly if they beg for their lives. If a manticore sees an advantage to be gained by sparing a creature's life, it does so, asking for a tribute or sacrifice equal to its loss of food.

## Monstrous Relationships

Manticores serve wicked masters that treat them well and provide regular prey. A manticore might provide aerial support for an orc horde or a hobgoblin army. Another could serve as a hunting companion for a hill giant chief, or guard the entrance to a lamia's lair.

The manticores' greatest territorial rivals include chimeras, griffons, perytons, and wyverns. Manticores hunting as a pack often have the advantage of greater numbers. In addition to these creatures, manticores fear dragons and avoid them.

> [!quote]- A quote from Marthok Uldarr, dwarf copper merchant  
> 
> Manticores love the taste of human flesh. That's why, on trips through the mountains, I always travel with human guards.


```statblock
"name": "Manticore"
"size": "Large"
"type": "monstrosity"
"alignment": "Lawful Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "68"
"hit_dice": "8d10 + 24"
"stats":
- !!int "17"
- !!int "16"
- !!int "17"
- !!int "7"
- !!int "12"
- !!int "8"
"speed": "30 ft., fly 50 ft."
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common"
"cr": "3"
"traits":
- "desc": "The manticore has twenty-four tail spikes. Used spikes regrow when the\
    \ manticore finishes a long rest."
  "name": "Tail Spike Regrowth"
"actions":
- "desc": "The manticore makes three attacks: one with its bite and two with its claws\
    \ or three with its tail spikes."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Claw"
- "desc": "Ranged Weapon Attack: +5 to hit, range 100/200 ft., one target. Hit:\
    \ 7 (1d8 + 3) piercing damage."
  "name": "Tail Spike"
"source":
- "MM"
- "PotA"
- "SKT"
- "TftYP"
- "WDH"
- "WDMM"
- "GoS"
- "DIP"
- "SLW"
- "BGDIA"
- "MOT"
- "JttRC"
- "DSotDQ"
- "SatO"
- "BMT"
- "DoDk"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MM/Manticore.webp"
```
^statblock

## Environment

mountain, grassland, hill, coastal, arctic