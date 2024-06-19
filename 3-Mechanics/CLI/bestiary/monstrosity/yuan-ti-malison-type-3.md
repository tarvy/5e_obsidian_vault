---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mm
- monster/cr/3
- monster/environment/desert
- monster/environment/forest
- monster/environment/swamp
- monster/size/medium
- monster/type/monstrosity/shapechanger
- monster/type/monstrosity/yuan-ti
statblock: inline
aliases: ["Yuan-ti Malison (Type 3)"]
---
# [Yuan-ti Malison (Type 3)](3-Mechanics/CLI/bestiary/monstrosity/yuan-ti-malison-type-3.md)
*Source: Monster Manual p. 309*  

A malison is a hideous blend of human and serpentine features. Three different types of malisons are known to exist, and other types are possible. Malisons form the middle caste of yuan-ti society and hunt with arrows tipped with their own venom. They use their magical powers of suggestion to force their enemies' surrender.

## Yuan-ti

Yuan-ti are devious serpent folk devoid of compassion. From remote temples in jungles, swamps, and deserts, the yuan-ti plot to supplant and dominate all other races and to make themselves gods.

### Forsaken Humanity

The yuan-ti were once humans who thrived in the earliest days of civilization and worshiped serpents as totem animals. They lauded the serpent's sinuous flexibility, its calculated poise, and its deadly strike. Their advanced philosophy taught the virtue of detachment from emotion and of clear, focused thought.

Yuan-ti culture was among the richest in the mortal world. Their warriors were legendary, their empires always expanding. Yuan-ti temples stood at the centers of ancient metropolises, reaching ever higher in prayer to the gods they longed to emulate. In time, the serpent gods heard those prayers, their sibilant voices responding from the darkness as they told the yuan-ti what they must do. The yuan-ti religion grew more fanatical in its devotion. Cults bound themselves to the worship of the serpent gods and imitated their ways, indulging in cannibalism and humanoid sacrifice. Through foul sorcery, the yuan-ti bred with snakes, utterly sacrificing their humanity to become like the serpent gods in form, as well as in thought and emotion.

Yuan-ti know that the world they hope to rule can't be bound for long by brute force, and that many creatures will refuse to serve. As a result, yuan-ti first influence other creatures with the promise of wealth and power. Time and again, humanoid cultures make the fatal mistake of trusting the yuan-ti. They forget that a yuan-ti that acts honorably or lends aid in a time of trouble does so only as part of a grander design.

Yuan-ti leaders are cunning and ruthless tacticians who readily sacrifice lesser yuan-ti if potential victory justifies such losses. They have no sense of honorable combat and strike first in decisive ambush if they can.

### Serpent Kings of Fallen Empires

The yuan-ti view their physical transformation as a transcendent moment for their race, allowing them to shed their frail humanity like dead skin. Those that did not transform eventually became slaves or food for the blessed of the serpent gods. The yuan-ti empires withered or were defeated by those who fought against their cannibalism and slavery, and the serpent folk were left in the ruins of their great capitals, far removed from other races.

### Cold of Heart

Humanoid emotions are foreign to most yuan-ti, which understand sentiment only as unexploitable weakness. A yuan-ti views the world and the events of its own life with such extreme pragmatism that it is nearly impossible to manipulate, influence, or control by nonmagical means, even as it seeks to control other creatures through terror, pleasure, and awe.

### False Worship

Yuan-ti life revolves around their temples, yet yuan-ti don't love the gods they worship. Instead, they see worship as a means to attain power. A yuan-ti believes an individual who attains enough power can devour and replace one of the yuan-ti gods. The yuan-ti strive for ascension and are willing to commit the darkest atrocities to achieve it.

> [!note] Serpent Gods
> 
> The yuan-ti revere a number of powerful entities as gods, including the following.
> 
> **Dendar, the Night Serpent.** Dendar's followers say that one day she will grow so large from feasting on the fears and nightmares of the world that she will devour it whole. Yuan-ti that serve Dendar terrorize other creatures in any way they can, growing and nurturing the fears of humanoids to feed the Night Serpent.
> 
> **Merrshaulk, Master of the Pit.** Merrshaulk is the long slumbering chief deity of the yuan-ti. As worship of Merrshaulk waned, he went into slumber. Merrshaulk's priests are yuan-ti abominations that maintain traditions of living sacrifice and cause suffering in the god's name. With enough vile acts, the abominations believe that Merrshaulk will reawaken and restore the yuan-ti to their rightful place.
> 
> **Sseth, the Sibilant Death.** Sseth appeared to the yuan-ti of antiquity in the form of a winged yuan-ti claiming to be an avatar of Merrshaulk. Speaking with Merrshaulk's voice, Sseth vowed to pull the yuan-ti out of decline and build a new empire. Many of Merrshaulk's devout turned to the worship of Sseth. Some yuan-ti have long suspected Sseth as an usurper taking advantage of Merrshaulk's slumber to make himself a god. They believe that Sseth might even have devoured Merrshaulk, and now answers the prayers of Merrshaulk's followers, as his priests convert or consume Merrshaulk's more stubborn adherents.
^serpent-gods

> [!quote]- A quote from From Masters of the Forbidden City by Codo Vidak  
> 
> The yuan-ti cast off their humanity long ago, and with it, their sanity.


```statblock
"name": "Yuan-ti Malison (Type 3)"
"size": "Medium"
"type": "monstrosity"
"subtype": "shapechanger, yuan-ti"
"alignment": "Neutral Evil"
"ac": !!int "12"
"hp": !!int "66"
"hit_dice": "12d8 + 12"
"stats":
- !!int "16"
- !!int "14"
- !!int "13"
- !!int "14"
- !!int "12"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "5"
  "Stealth": !!int "4"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/3-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Abyssal, Common, Draconic"
"cr": "3"
"traits":
- "desc": "The yuan-ti's innate spellcasting ability is Charisma (spell save DC 13).\
    \ The yuan-ti can innately cast the following spells, requiring no material components:\n\
    \nAt will: [animal friendship](/3-Mechanics/CLI/spells/animal-friendship.md)\
    \ (snakes only)\n\n3/day: [suggestion](/3-Mechanics/CLI/spells/suggestion.md)"
  "name": "Innate Spellcasting (Yuan-ti Form Only)"
- "desc": "The yuan-ti can use its action to polymorph into a Medium snake, or back\
    \ into its true form. Its statistics are the same in each form. Any equipment\
    \ it is wearing or carrying isn't transformed. It doesn't change form if it dies."
  "name": "Shapechanger"
- "desc": "The yuan-ti has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The yuan-ti has one of the following types:\n\n- Type 1. Human body\
    \ with snake head  \n- Type 2. Human head and body with snakes for arms  \n\
    - Type 3. Human head and upper body with a serpentine lower body instead of\
    \ legs  "
  "name": "Malison Type"
"actions":
- "desc": "The yuan-ti makes two ranged attacks or two melee attacks, but can constrict\
    \ only once."
  "name": "Multiattack (Yuan-ti Form Only)"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. Hit: 5\
    \ (1d4 + 3) piercing damage plus 7 (2d6) poison damage."
  "name": "Bite (Snake Form Only)"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) bludgeoning damage, and the target is [grappled](/3-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 13). Until this grapple ends, the target is [restrained](/3-Mechanics/CLI/rules/conditions.md#restrained),\
    \ and the yuan-ti can't constrict another target."
  "name": "Constrict"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Scimitar (Yuan-ti Form Only)"
- "desc": "Ranged Weapon Attack: +4 to hit, range 150/600 ft., one target. Hit:\
    \ 6 (1d8 + 2) piercing damage."
  "name": "Longbow (Yuan-ti Form Only)"
"source":
- "MM"
- "HotDQ"
- "RoT"
- "SKT"
- "ToA"
- "CM"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MM/Yuan-ti%20Malison%20%28Type%203%29.webp"
```
^statblock

## Environment

forest, swamp, desert