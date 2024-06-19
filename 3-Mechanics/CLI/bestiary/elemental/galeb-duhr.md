---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mm
- monster/cr/6
- monster/environment/hill
- monster/environment/mountain
- monster/size/medium
- monster/type/elemental
statblock: inline
aliases: ["Galeb Duhr"]
---
# [Galeb Duhr](3-Mechanics/CLI/bestiary/elemental/galeb-duhr.md)
*Source: Monster Manual p. 139*  

The galeb duhr is a boulder-like creature with stumpy appendages that act as arms and legs. It has the ability to animate the rocks and boulders around it, and is thus usually encountered in rocky terrain.

Powerful magic allows a spellcaster to summon a galeb duhr from the Plane of Earth. Some galeb duhr also form naturally in places touched by that plane. The galeb duhr is imbued with greater intelligence than most elementals, allowing it to better assess threats and to communicate with creatures entering its guarded area.

## Stone Guardian

A galeb duhr doesn't age or require sustenance, making it an excellent sentinel. A powerful druid might charge a galeb duhr with protecting a stone circle or sacred hilltop. Another galeb duhr might be created to guard an underground tomb or a wizard's tower. When it chooses to, the galeb duhr can make itself look like an ordinary boulder, remaining perfectly still for years at a time.

A galeb duhr is permanently bound to the Material Plane, so that when it dies, it doesn't return to the Plane of Earth. It has an excellent memory and is more than happy to share information regarding its environment with creatures it doesn't regard as threats.

## Stone Connection

A galeb duhr can become one with the earth around it, allowing it to imbue nearby rocks and boulders with a semblance of life. The galeb duhr uses its animated boulders to frighten away interlopers and defend whatever it has been charged to protect. When it needs to move close to those intruders, it presses its limbs tight to its body and rolls forward at a furious pace.

```statblock
"name": "Galeb Duhr"
"size": "Medium"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "85"
"hit_dice": "9d8 + 45"
"stats":
- !!int "20"
- !!int "14"
- !!int "20"
- !!int "11"
- !!int "12"
- !!int "11"
"speed": "15 ft. (30 ft. when rolling, 60 ft. rolling downhill)"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/rules/conditions.md#exhaustion),\
  \ [paralyzed](/3-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/3-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/3-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., tremorsense 60 ft., passive Perception 11"
"languages": "Terran"
"cr": "6"
"traits":
- "desc": "While the galeb duhr remains motionless, it is indistinguishable from a\
    \ normal boulder."
  "name": "False Appearance"
- "desc": "If the galeb duhr rolls at least 20 feet straight toward a target and then\
    \ hits it with a slam attack on the same turn, the target takes an extra 7 (2d6)\
    \ bludgeoning damage. If the target is a creature, it must succeed on a DC 16\
    \ Strength saving throw or be knocked [prone](/3-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Rolling Charge"
"actions":
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 12\
    \ (2d6 + 5) bludgeoning damage."
  "name": "Slam"
- "desc": "The galeb duhr magically animates up to two boulders it can see within\
    \ 60 feet of it. A boulder has statistics like those of a galeb duhr, except it\
    \ has Intelligence 1 and Charisma 1, it can't be [charmed](/3-Mechanics/CLI/rules/conditions.md#charmed)\
    \ or [frightened](/3-Mechanics/CLI/rules/conditions.md#frightened), and it lacks\
    \ this action option. A boulder remains animated as long as the galeb duhr maintains\
    \ [concentration](/3-Mechanics/CLI/rules/conditions.md#concentration), up to 1\
    \ minute (as if concentrating on a spell)."
  "name": "Animate Boulders (1/Day)"
"source":
- "MM"
- "PotA"
- "WDMM"
- "TCE"
- "WBtW"
- "KftGV"
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MM/Galeb%20Duhr.webp"
```
^statblock

## Environment

mountain, hill