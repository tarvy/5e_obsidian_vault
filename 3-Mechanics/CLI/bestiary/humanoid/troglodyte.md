---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mm
- monster/cr/1-4
- monster/environment/underdark
- monster/size/medium
- monster/type/humanoid/troglodyte
statblock: inline
aliases: ["Troglodyte"]
---
# [Troglodyte](3-Mechanics/CLI/bestiary/humanoid/troglodyte.md)
*Source: Monster Manual p. 290*  

The savage, degenerate troglodytes squat in the shallow depths of the Underdark in a constant state of war against their neighbors and one another. They mark the borders of their territories with cracked bones and skulls, or with pictographs painted in blood or dung.

Perhaps the most loathsome of all humanoids, troglodytes eat anything they can stomach. They dwell in filth. The walls of their cavern homes are smeared with grime, oily secretions, and the debris of their foul feasting.

## Simpleminded Brutes

Troglodytes have a simple, communal culture devoted almost entirely to procuring food. Too simple to plan more than a few days into the future, troglodytes rely on constant raids and hunting to survive. They take sadistic pleasure in hunting intelligent creatures weaker than themselves and show no mercy toward those they capture and drag back to their lairs to be devoured. The largest and toughest troglodytes lead the hunt and become the leaders of their tribes. However, if a leader shows any weakness or hesitation, other troglodytes attack and eat it in a frenzy.

Troglodytes make little and build less, scavenging their possessions from their prey. They understand the value of metal weapons and armor, and fight among one another for the right to have such items. A troglodyte tribe might be torn apart by battles over a single longsword.

## Devotees of Laogzed

Some troglodytes venerate Laogzed, a demonic, monstrously fat toad-lizard that slumbers in the Abyss. Laogzed offers the troglodytes nothing in return except aspiration, for it is the dream of his troglodyte worshipers to become as fat, well-fed, and wearily content as he seems to be.

> [!quote]- A quote from Last words of Arlack Hammermantle, dwarf spelunker  
> 
> Smells liek an orc's loincloth in here!


```statblock
"name": "Troglodyte"
"size": "Medium"
"type": "humanoid"
"subtype": "troglodyte"
"alignment": "Chaotic Evil"
"ac": !!int "11"
"ac_class": "natural armor"
"hp": !!int "13"
"hit_dice": "2d8 + 4"
"stats":
- !!int "14"
- !!int "10"
- !!int "14"
- !!int "6"
- !!int "10"
- !!int "6"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "2"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Troglodyte"
"cr": "1/4"
"traits":
- "desc": "The troglodyte has advantage on Dexterity ([Stealth](/3-Mechanics/CLI/rules/skills.md#Stealth))\
    \ checks made to hide."
  "name": "Chameleon Skin"
- "desc": "Any creature other than a troglodyte that starts its turn within 5 feet\
    \ of the troglodyte must succeed on a DC 12 Constitution saving throw or be [poisoned](/3-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ until the start of the creature's next turn. On a successful saving throw, the\
    \ creature is immune to the stench of all troglodytes for 1 hour."
  "name": "Stench"
- "desc": "While in sunlight, the troglodyte has disadvantage on attack rolls, as\
    \ well as on Wisdom ([Perception](/3-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "The troglodyte makes three attacks: one with its bite and two with its\
    \ claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) slashing damage."
  "name": "Claw"
"source":
- "MM"
- "HotDQ"
- "PotA"
- "TftYP"
- "WDH"
- "WDMM"
- "HftT"
- "PaBTSO"
- "SatO"
- "BMT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MM/Troglodyte.webp"
```
^statblock

## Environment

underdark