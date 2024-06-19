---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mm
- monster/cr/2
- monster/environment/underdark
- monster/size/large
- monster/type/undead
statblock: inline
aliases: ["Minotaur Skeleton"]
---
# [Minotaur Skeleton](3-Mechanics/CLI/bestiary/undead/minotaur-skeleton.md)
*Source: Monster Manual p. 273. Available in the SRD.*  

Skeletons arise when animated by dark magic. They heed the summons of spellcasters who call them from their stony tombs and ancient battlefields, or rise of their own accord in places saturated with death and loss, awakened by stirrings of necromantic energy or the presence of corrupting evil.

## Animated Dead

Whatever sinister force awakens a skeleton infuses its bones with a dark vitality, adhering joint to joint and reassembling dismantled limbs. This energy motivates a skeleton to move and think in a rudimentary fashion, though only as a pale imitation of the way it behaved in life. An animated skeleton retains no connection to its past, although resurrecting a skeleton restores it body and soul, banishing the hateful undead spirit that empowers it.

While most skeletons are the animated remains of dead humans and other humanoids, skeletal undead can be created from the bones of other creatures besides humanoids, giving rise to a host of terrifying and unique forms.

## Obedient Servants

Skeletons raised by spell are bound to the will of their creator. They follow orders to the letter, never questioning the tasks their masters give them, regardless of the consequences. Because of their literal interpretation of commands and unwavering obedience, skeletons adapt poorly to changing circumstances. They can't read, speak, emote, or communicate in any way except to nod, shake their heads, or point. Still, skeletons are able to accomplish a variety of relatively complex tasks.

A skeleton can fight with weapons and wear armor, can load and fire a catapult or trebuchet, scale a siege ladder, form a shield wall, or dump boiling oil. However, it must receive careful instructions explaining how such tasks are accomplished.

Although they lack the intellect they possessed in life, skeletons aren't mindless. Rather than break its limbs attempting to batter its way through an iron door, a skeleton tries the handle first. If that doesn't work, it searches for another way through or around the obstacle.

## Habitual Behaviors

Independent skeletons temporarily or permanently free of a master's control sometimes pantomime actions from their past lives, their bones echoing the rote behaviors of their former living selves. The skeleton of a miner might lift a pick and start chipping away at stone walls. The skeleton of a guard might strike up a post at a random doorway. The skeleton of a dragon might lie down on a pile of treasure, while the skeleton of a horse crops grass it can't eat. Left alone in a ballroom, the skeletons of nobles might continue an eternally unfinished dance.

When skeletons encounter living creatures, the necromantic energy that drives them compels them to kill unless they are commanded by their masters to refrain from doing so. They attack without mercy and fight until destroyed, for skeletons possess little sense of self and even less sense of self-preservation.

## Undead Nature

A skeleton doesn't require air, food, drink, or sleep.

```statblock
"name": "Minotaur Skeleton"
"size": "Large"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "67"
"hit_dice": "9d10 + 18"
"stats":
- !!int "18"
- !!int "11"
- !!int "15"
- !!int "6"
- !!int "8"
- !!int "5"
"speed": "40 ft."
"damage_vulnerabilities": "bludgeoning"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/rules/conditions.md#exhaustion),\
  \ [poisoned](/3-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "understands Abyssal but can't speak"
"cr": "2"
"traits":
- "desc": "If the skeleton moves at least 10 feet straight toward a target and then\
    \ hits it with a gore attack on the same turn, the target takes an extra 9 (2d8)\
    \ piercing damage. If the target is a creature, it must succeed on a DC 14 Strength\
    \ saving throw or be pushed up to 10 feet away and knocked [prone](/3-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Charge"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 17\
    \ (2d12 + 4) slashing damage."
  "name": "Greataxe"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 13\
    \ (2d8 + 4) piercing damage."
  "name": "Gore"
"source":
- "MM"
- "ToA"
- "WDH"
- "WDMM"
- "GoS"
- "DIP"
- "SDW"
- "BGDIA"
- "IMR"
- "DSotDQ"
- "KftGV"
- "AATM"
- "VEoR"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MM/Minotaur%20Skeleton.webp"
```
^statblock

## Environment

underdark