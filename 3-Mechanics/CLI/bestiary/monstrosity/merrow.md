---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mm
- monster/cr/2
- monster/environment/coastal
- monster/environment/underwater
- monster/size/large
- monster/type/monstrosity
statblock: inline
aliases: ["Merrow"]
---
# [Merrow](3-Mechanics/CLI/bestiary/monstrosity/merrow.md)
*Source: Monster Manual p. 219. Available in the SRD.*  

Merrow haunt coastal waters, preying on fisherfolk, merfolk, and any other edible creature that crosses their path. These savage monsters snatch and devour unwary prey, hauling drowned corpses back to their underwater grottoes to feed.

## Transformed Merfolk

Long ago, a tribe of merfolk found an idol of Demogorgon at the bottom of the sea.

Not knowing what it was, they brought the artifact to their king. Everyone who touched the idol became afflicted with madness, including the king, who decreed that a sacrificial ritual be performed to open a gateway to the Abyss. The ocean turned red with the blood of slaughtered merfolk, but the ritual worked, and the king led the survivors through the underwater gate to Demogorgon's layer of the Abyss. The merfolk remained there for generations, fighting for their lives as the Abyss warped them completely, transforming them into hulking, evil monstrosities. Thus, the first merrow were born.

## Coastal Bullies

Whenever an opportunity presents itself, the Prince of Demons sends merrow back to the Material Plane to wreak havoc in the oceans. The merrow are bullies, attacking all creatures smaller and weaker than themselves.

Merrow dwell in undersea caves filled with treasures and trophies, taken from their victims and sunken ships. They tie the rotting corpses of dead enemies and drowned sailors to strands of kelp to mark the borders of their territory.

```statblock
"name": "Merrow"
"size": "Large"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "45"
"hit_dice": "6d10 + 12"
"stats":
- !!int "18"
- !!int "10"
- !!int "15"
- !!int "8"
- !!int "10"
- !!int "9"
"speed": "10 ft., swim 40 ft."
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Abyssal, Aquan"
"cr": "2"
"traits":
- "desc": "The merrow can breathe air and water."
  "name": "Amphibious"
"actions":
- "desc": "The merrow makes two attacks: one with its bite and one with its claws\
    \ or harpoon."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 9 (2d4\
    \ + 4) slashing damage."
  "name": "Claws"
- "desc": "Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 11 (2d6 + 4) piercing damage. If the target is a Huge\
    \ or smaller creature, it must succeed on a Strength contest against the merrow\
    \ or be pulled up to 20 feet toward the merrow."
  "name": "Harpoon"
"source":
- "MM"
- "PotA"
- "RoT"
- "SKT"
- "TftYP"
- "WDH"
- "GoS"
- "IDRotF"
- "WBtW"
- "DSotDQ"
- "DoDk"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MM/Merrow.webp"
```
^statblock

## Environment

underwater, coastal