---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mm
- monster/cr/2
- monster/environment/arctic
- monster/environment/coastal
- monster/environment/desert
- monster/environment/forest
- monster/environment/hill
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid/any-race
statblock: inline
aliases: ["Bandit Captain"]
---
# [Bandit Captain](3-Mechanics/CLI/bestiary/humanoid/bandit-captain.md)
*Source: Monster Manual p. 344. Available in the SRD.*  

It takes a strong personality, ruthless cunning, and a silver tongue to keep a gang of bandits in line. The bandit captain has these qualities in spades.

In addition to managing a crew of selfish malcontents, the pirate captain is a variation of the bandit captain, with a ship to protect and command. To keep the crew in line, the captain must mete out rewards and punishment on a regular basis.

More than treasure, a bandit captain or pirate captain craves infamy. A prisoner who appeals to the captain's vanity or ego is more likely to be treated fairly than a prisoner who does not or claims not to know anything of the captain's colorful reputation.

```statblock
"name": "Bandit Captain"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any Non-Lawful alignment"
"ac": !!int "15"
"ac_class": "[studded leather](/3-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"stats":
- !!int "15"
- !!int "16"
- !!int "14"
- !!int "14"
- !!int "11"
- !!int "14"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "5"
  "Wisdom": !!int "2"
  "Strength": !!int "4"
"skillsaves":
  "Athletics": !!int "4"
  "Deception": !!int "4"
"senses": "passive Perception 10"
"languages": "any two languages"
"cr": "2"
"actions":
- "desc": "The captain makes three melee attacks: two with its scimitar and one with\
    \ its dagger. Or the captain makes two ranged attacks with its daggers."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Scimitar"
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 5 (1d4 + 3) piercing damage."
  "name": "Dagger"
"reactions":
- "desc": "The captain adds 2 to its AC against one melee attack that would hit it.\
    \ To do so, the captain must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "MM"
- "PotA"
- "SKT"
- "ToA"
- "WDH"
- "WDMM"
- "GoS"
- "DC"
- "DIP"
- "SLW"
- "BGDIA"
- "IMR"
- "EGW"
- "MOT"
- "IDRotF"
- "CM"
- "CoS"
- "CRCotN"
- "LoX"
- "DSotDQ"
- "KftGV"
- "SatO"
- "ToFW"
- "BMT"
- "DoDk"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MM/Bandit%20Captain.webp"
```
^statblock

## Environment

coastal, hill, arctic, urban, forest, desert