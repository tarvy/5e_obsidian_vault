---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mm
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/gith
statblock: inline
aliases: ["Githzerai Monk"]
---
# [Githzerai Monk](3-Mechanics/CLI/bestiary/humanoid/githzerai-monk.md)
*Source: Monster Manual p. 161*  

Focused philosophers and austere ascetics, the githzerai pursue lives of rigid order. Lean and muscular, they wear unadorned clothing free of ornamentation, keeping their own counsel and trusting few creatures outside of their own kind. Having turned their backs on their warlike githyanki kin, the githzerai maintain a strict monastic lifestyle, dwelling on islands of order in the vast sea of chaos that is the plane of Limbo.

## Psionic Adepts

The progenitors of the githzerai adapted to—and were transformed by—the psychic environment imposed on them by their illithid overlords. Under the teachings of Zerthimon, who called on his people to abandon the warlike ambitions of Gith, the githzerai focused their mental energy on creating physical and psychic barriers to protect them from attack, psychic or otherwise. Fighting is personal to a githzerai, which uses its mind to daze and incapacitate opponents, leaving them vulnerable to physical punishment.

## Order amid Chaos

The githzerai willingly dwell in the heart of utter chaos in Limbo—a twisting, mercurial plane prone to manipulation and subjugation by githzerai minds strong enough to master it. Limbo is a maelstrom of primal matter and energy, its terrain a storm of rock and earth swept up in torrents of murky liquid, buffeted by strong winds, blasted by fire, and chilled by crushing walls of ice.

The forces of Limbo react to sentience, however. Using the power of their minds, the githzerai tame the plane's chaotic elements, causing them to settle into fixed and survivable forms and creating oases and sanctuaries within the maelstrom.

Githzerai fortress-monasteries stand resolute against the chaos that surrounds them, virtually impervious to the turmoil of their surroundings, because the githzerai will it. Each monastery is overseen by monks that impose a strict schedule of chants, meals, martial arts training, and devotions according to their own philosophy. Behind their psionically fortified walls, the githzerai embrace thought, learning, psionic power, order, and discipline above all other things.

The social hierarchy of the githzerai is based on merit, and those githzerai who are the wisest teachers and the most skilled at physical and mental combat become leaders. The githzerai revere great heroes and teachers of the past, emulating those figures' virtues in their everyday lives.

## Disciples of Zerthimon

Githzerai revere Zerthimon, the founder of their race. Although Gith won their people's freedom, Zerthimon saw her as unfit to lead. He believed that her warmongering would soon make her a tyrant no better than the [mind flayers](/3-Mechanics/CLI/bestiary/aberration/mind-flayer.md).

Skilled githzerai monks that best exemplify the teachings and principles of Zerthimon are called zerths.

These powerful and disciplined monks can shift their bodies from one plane to another using only the power of their minds.

## Beyond Limbo

Though githzerai rarely deal with the realms beyond Limbo, advanced monks of other races sometimes seek out a githzerai monastery and attempt to gain admittance as students. More rarely, a githzerai master establishes a hidden monastery on the Material Plane to train young githzerai or to spread the philosophy and teachings of Zerthimon.

As disciplined as they are, the githzerai have never forgotten their long imprisonment by the mind flayers.

As a special devotion, they organize a rrakkma—an illithid hunting party—to other planes, not returning to their monasteries until they slay at least as many illithids as there are hunters in the party.

## Gith

The warlike githyanki and the contemplative githzerai are a sundered people-two cultures that utterly despise one another. Before there were githyanki or githzerai, these creatures were a single race enslaved by the [mind flayers](/3-Mechanics/CLI/bestiary/aberration/mind-flayer.md). Although they attempted to overthrow their masters many times, their rebellions were repeatedly crushed until a great leader named Gith arose.

After much bloodshed, Gith and her followers threw off the yoke of their illithid masters, but another leader named Zerthimon emerged in the aftermath of battle.

Zerthimon challenged Gith's motives, claiming that her strict martial leadership and desire for vengeance amounted to little more than another form of slavery for her people. A rift erupted between followers of each leader, and they eventually became the two races whose enmity endures to this day.

Whether these tall, gaunt creatures were peaceful or savage, cultured or primitive before the [mind flayers](/3-Mechanics/CLI/bestiary/aberration/mind-flayer.md) enslaved and changed them, none can say. Not even the original name of their race remains from that distant time.

> [!quote]- A quote from Aristul the Yellow, master of planar lore  
> 
> The githyanki and the githzerai were so profoundly scarred by their enslavement to the mind flayers that they forget they were one race, united. Having won their freedom, they wage war against each other with a hatred none can fully comprehend.


```statblock
"name": "Githzerai Monk"
"size": "Medium"
"type": "humanoid"
"subtype": "gith"
"alignment": "Lawful Neutral"
"ac": !!int "14"
"hp": !!int "38"
"hit_dice": "7d8 + 7"
"stats":
- !!int "12"
- !!int "15"
- !!int "12"
- !!int "13"
- !!int "14"
- !!int "10"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "4"
  "Wisdom": !!int "4"
  "Intelligence": !!int "3"
  "Strength": !!int "3"
"skillsaves":
  "Insight": !!int "4"
  "Perception": !!int "4"
"senses": "passive Perception 14"
"languages": "Gith"
"cr": "2"
"traits":
- "desc": "The githzerai's innate spellcasting ability is Wisdom. It can innately\
    \ cast the following spells, requiring no components:\n\nAt will: [mage hand](/3-Mechanics/CLI/spells/mage-hand.md)\
    \ (the hand is invisible)\n\n3/day each: [feather fall](/3-Mechanics/CLI/spells/feather-fall.md),\
    \ [jump](/3-Mechanics/CLI/spells/jump.md), [see invisibility](/3-Mechanics/CLI/spells/see-invisibility.md),\
    \ [shield](/3-Mechanics/CLI/spells/shield.md)"
  "name": "Innate Spellcasting (Psionics)"
- "desc": "While the githzerai is wearing no armor and wielding no shield, its AC\
    \ includes its Wisdom modifier."
  "name": "Psychic Defense"
"actions":
- "desc": "The githzerai makes two unarmed strikes."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) bludgeoning damage plus 9 (2d8) psychic damage. This is a magic weapon\
    \ attack."
  "name": "Unarmed Strike"
"source":
- "MM"
- "SatO"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MM/Githzerai%20Monk.webp"
```
^statblock