---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mm
- monster/cr/8
- monster/environment/grassland
- monster/size/huge
- monster/type/beast
statblock: inline
aliases: ["Tyrannosaurus Rex"]
---
# [Tyrannosaurus Rex](3-Mechanics/CLI/bestiary/beast/tyrannosaurus-rex.md)
*Source: Monster Manual p. 80. Available in the SRD and the Basic Rules.*  

This enormous predator terrorizes all other creatures in its territory. Despite its size and weight, a tyrannosaurus is a swift runner. It chases anything it thinks it can eat, and there are few creatures it won't try to devour whole. While prowling for substantial prey, a tyrannosaurus subsists on carrion, and on any smaller creatures that try to dart in to steal its meal.

## Dinosaurs

Dinosaurs, or behemoths, are among the oldest reptiles in the world. Predatory dinosaurs are savage, territorial hunters. Herbivorous dinosaurs are less aggressive, but they might attack to defend their young, or if startled or harassed.

Dinosaurs come in many sizes and shapes. Larger varieties often have drab coloration, while smaller dinosaurs have colorful markings akin to birds. Dinosaurs roam rugged and isolated areas that humanoids seldom visit, including remote mountain valleys, inaccessible plateaus, tropical islands, and deep fens.

```statblock
"name": "Tyrannosaurus Rex"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "13d12 + 52"
"stats":
- !!int "25"
- !!int "10"
- !!int "19"
- !!int "2"
- !!int "12"
- !!int "9"
"speed": "50 ft."
"skillsaves":
  "Perception": !!int "4"
"senses": "passive Perception 14"
"languages": ""
"cr": "8"
"actions":
- "desc": "The tyrannosaurus makes two attacks: one with its bite and one with its\
    \ tail. It can't make both attacks against the same target."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 33\
    \ (4d12 + 7) piercing damage. If the target is a Medium or smaller creature,\
    \ it is [grappled](/3-Mechanics/CLI/rules/conditions.md#grappled) (escape DC 17).\
    \ Until this grapple ends, the target is [restrained](/3-Mechanics/CLI/rules/conditions.md#restrained),\
    \ and the tyrannosaurus can't bite another target."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 20\
    \ (3d8 + 7) bludgeoning damage."
  "name": "Tail"
"source":
- "MM"
- "ToA"
- "EGW"
- "SatO"
- "DoDk"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MM/Tyrannosaurus%20Rex.webp"
```
^statblock

## Environment

grassland