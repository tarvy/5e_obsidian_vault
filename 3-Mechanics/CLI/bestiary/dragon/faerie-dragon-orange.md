---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mm
- monster/cr/1
- monster/environment/forest
- monster/size/tiny
- monster/type/dragon
statblock: inline
aliases: ["Faerie Dragon (Orange)"]
---
# [Faerie Dragon (Orange)](3-Mechanics/CLI/bestiary/dragon/faerie-dragon-orange.md)
*Source: Monster Manual p. 133*  

A faerie dragon is a cat-sized dragon with butterfly wings. It wears a sharp-toothed grin and expresses its delight by the twitching of its tail, its merriment fading only if it is attacked.

## Invisible Tricksters

The only warning of a faerie dragon's presence is a stifled giggle. The dragon stays out of sight, watching invisibly as its victims contend with its pranks. When its fun is done, the dragon might reveal itself, depending on the disposition of its "prey."

## Friendly and Bright

A faerie dragon has a sharp mind, a fondness for treasure and good company, and a puckish sense of humor. Travelers can play to a faerie dragon's draconic nature by offering it "treasure" in the form of sweets, baked goods, and baubles in exchange for information or safe passage through its territory.

## The Colors of Age

A faerie dragon's scales change hue as it ages, moving through all the colors of the rainbow. All faerie dragons have innate spellcasting ability, gaining new spells as they mature.

| Dragon Color | Age Range |
|--------------|-----------|
| Red | 5 years or less |
| Orange | 6–10 years |
| Yellow | 11–20 years |
| Green | 21–30 years |
| Blue | 31–40 years |
| Indigo | 41–50 years |
| Violet | 51 years or more |
^dragon-color-age-range

CR 1 (200 XP) For a red, orange, or yellow faerie dragon; 2 (450 XP) for a green, blue, indigo, or violet faerie dragon

```statblock
"name": "Faerie Dragon (Orange)"
"size": "Tiny"
"type": "dragon"
"alignment": "Chaotic Good"
"ac": !!int "15"
"hp": !!int "14"
"hit_dice": "4d4 + 4"
"stats":
- !!int "3"
- !!int "20"
- !!int "13"
- !!int "14"
- !!int "12"
- !!int "16"
"speed": "10 ft., fly 60 ft."
"skillsaves":
  "Stealth": !!int "7"
  "Perception": !!int "3"
  "Arcana": !!int "4"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Draconic, Sylvan"
"cr": "1"
"traits":
- "desc": "The dragon's innate spellcasting ability is Charisma (spell save DC 13).\
    \ It can innately cast a number of spells, requiring no material components:\n\
    \n1/day each: [color spray](/3-Mechanics/CLI/spells/color-spray.md), [dancing\
    \ lights](/3-Mechanics/CLI/spells/dancing-lights.md), [mage hand](/3-Mechanics/CLI/spells/mage-hand.md),\
    \ [minor illusion](/3-Mechanics/CLI/spells/minor-illusion.md)"
  "name": "Innate Spellcasting"
- "desc": "A faerie dragon's scales change hue as it ages, moving through all the\
    \ colors of the rainbow. All faerie dragons have innate spellcasting ability,\
    \ gaining new spells as they mature.\n\nRed—5 years or less\n\nOrange—6–10 years\n\
    \nYellow—11–20 years\n\nGreen—21–30 years\n\nBlue—31–40 years\n\nIndigo—41–50\
    \ years\n\nViolet—51 years or more\n\nA green or older faerie dragon's CR increases\
    \ to 2."
  "name": "The Colors of Age"
- "desc": "As a bonus action, the dragon can magically turn [invisible](/3-Mechanics/CLI/rules/conditions.md#invisible)\
    \ until its [concentration](/3-Mechanics/CLI/rules/conditions.md#concentration)\
    \ ends (as if concentrating on a spell). Any equipment the dragon wears or carries\
    \ is [invisible](/3-Mechanics/CLI/rules/conditions.md#invisible) with it."
  "name": "Superior Invisibility"
- "desc": "Using telepathy, the dragon can magically communicate with any other faerie\
    \ dragon within 60 feet of it."
  "name": "Limited Telepathy"
- "desc": "The faerie dragon has advantage on saving throws against spells and other\
    \ magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. Hit: 1\
    \ piercing damage."
  "name": "Bite"
- "desc": "The dragon exhales a puff of euphoria gas at one creature within 5 feet\
    \ of it. The target must succeed on a DC 11 Wisdom saving throw, or for 1 minute,\
    \ the target can't take reactions and must roll a d6 at the start of each of\
    \ its turns to determine its behavior during the turn:\n\n1–4. The target takes\
    \ no action or bonus action and uses all of its movement to move in a random direction.\n\
    \n5–6. The target doesn't move, and the only thing it can do on its turn is make\
    \ a DC 11 Wisdom saving throw, ending the effect on itself on a success."
  "name": "Euphoria Breath (Recharge 5-6)"
"source":
- "MM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MM/Faerie%20Dragon%20%28Orange%29.webp"
```
^statblock

## Environment

forest