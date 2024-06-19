---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mm
- monster/cr/4
- monster/environment/urban
- monster/size/medium
- monster/type/fiend/shapechanger
statblock: inline
aliases: ["Succubus"]
---
# [Succubus](3-Mechanics/CLI/bestiary/fiend/succubus.md)
*Source: Monster Manual p. 285. Available in the SRD.*  

Succubi and incubi inhabit all of the Lower Planes, and the lascivious dark-winged fiends can be found in service to devils, demons, night hags, rakshasas, and yugoloths. Asmodeus, ruler of the Nine Hells, uses these fiends to tempt mortals to perform evil acts. The demon lord Graz'zt keeps succubi and incubi as advisers and consorts.

Though legend speaks of them separately, any succubus can become an incubus, and vice versa. Most of these fiends do have a preference for one form or the other. Mortals only rarely see a succubus or incubus in its true form, however, for the fiend typically begins its corruption in veiled, insidious ways.

## Beautiful Corrupters

A succubus or incubus first appears in ethereal form, passing through walls like a ghost to lurk next to a mortal's bedside and whisper forbidden pleasures. Sleeping victims are tempted to give in to their darkest desires, indulge in taboos, and feed forbidden appetites. As the fiend fills the victim's dreams with debauched images, the victim becomes more susceptible to temptation in everyday life.

Inevitably, the fiend enters the mortal realm in tempting form to directly influence a creature's actions. Appearing in the guise of a humanoid who has previously appeared only in the victim's dreams, the succubus or incubus seduces or befriends its victim, indulging all its desires so that it performs evil acts of its own free will.

A mortal bequeaths its soul to the fiend not by formal pledge or contract. Instead, when a succubus or incubus has corrupted a creature completely-some say by causing the victim to commit the three betrayals of thought, word, and deed-the victim's soul belongs to the fiend. The more virtuous the fiend's prey, the longer the corruption takes, but the more rewarding the downfall. After successfully corrupting a victim, the succubus or incubus kills it, and the tainted soul descends into the Lower Planes.

The succubus or incubus resorts to charming a victim magically only when necessary, usually as a form of self-defense. A [charmed](/3-Mechanics/CLI/rules/conditions.md#charmed) creature isn't responsible for its actions, so forcing it to behave against its will won't bring the fiend closer to the ultimate prize: the victim's soul.

## Deadly Kiss

The kiss of a succubus or incubus is an echo of the emptiness that is the fiend's longing for a corrupted soul. Likewise, the recipient of the fiend's kiss gains no satisfaction from it, experiencing only pain and the profound emptiness that the fiend imparts. The kiss is nothing short of an attack, usually delivered as a final farewell before the fiend escapes.

## Fiendish Offspring

Succubi and incubi can reproduce with one another to spawn more of their kind. Less commonly, a succubus or incubus reproduces with a humanoid. From this unholy union, a [cambion](/3-Mechanics/CLI/bestiary/fiend/cambion.md) child is conceived. Invariably, the fiendish offspring is as wicked as its fiendish parent.

```statblock
"name": "Succubus"
"size": "Medium"
"type": "fiend"
"subtype": "shapechanger"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "66"
"hit_dice": "12d8 + 12"
"stats":
- !!int "8"
- !!int "17"
- !!int "13"
- !!int "15"
- !!int "12"
- !!int "20"
"speed": "30 ft., fly 60 ft."
"skillsaves":
  "Deception": !!int "9"
  "Stealth": !!int "7"
  "Insight": !!int "5"
  "Perception": !!int "5"
  "Persuasion": !!int "9"
"damage_resistances": "cold; fire; lightning; poison; bludgeoning, piercing, slashing\
  \ from nonmagical attacks"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Abyssal, Common, Infernal, telepathy 60 ft."
"cr": "4"
"traits":
- "desc": "The fiend ignores the range restriction on its telepathy when communicating\
    \ with a creature it has [charmed](/3-Mechanics/CLI/rules/conditions.md#charmed).\
    \ The two don't even need to be on the same plane of existence."
  "name": "Telepathic Bond"
- "desc": "The fiend can use its action to polymorph into a Small or Medium humanoid,\
    \ or back into its true form. Without wings, the fiend loses its flying speed.\
    \ Other than its size and speed, its statistics are the same in each form. Any\
    \ equipment it is wearing or carrying isn't transformed. It reverts to its true\
    \ form if it dies."
  "name": "Shapechanger"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Claw (Fiend Form Only)"
- "desc": "One humanoid the fiend can see within 30 feet of it must succeed on a DC\
    \ 15 Wisdom saving throw or be magically [charmed](/3-Mechanics/CLI/rules/conditions.md#charmed)\
    \ for 1 day. The [charmed](/3-Mechanics/CLI/rules/conditions.md#charmed) target\
    \ obeys the fiend's verbal or telepathic commands. If the target suffers any harm\
    \ or receives a suicidal command, it can repeat the saving throw, ending the effect\
    \ on a success. If the target successfully saves against the effect, or if the\
    \ effect on it ends, the target is immune to this fiend's Charm for the next 24\
    \ hours.\n\nThe fiend can have only one target [charmed](/3-Mechanics/CLI/rules/conditions.md#charmed)\
    \ at a time. If it charms another, the effect on the previous target ends."
  "name": "Charm"
- "desc": "The fiend kisses a creature [charmed](/3-Mechanics/CLI/rules/conditions.md#charmed)\
    \ by it or a willing creature. The target must make a DC 15 Constitution saving\
    \ throw against this magic, taking 32 (5d10 + 5) psychic damage on a failed\
    \ save, or half as much damage on a successful one. The target's hit point maximum\
    \ is reduced by an amount equal to the damage taken. This reduction lasts until\
    \ the target finishes a long rest. The target dies if this effect reduces its\
    \ hit point maximum to 0."
  "name": "Draining Kiss"
- "desc": "The fiend magically enters the Ethereal Plane from the Material Plane,\
    \ or vice versa."
  "name": "Etherealness"
"source":
- "MM"
- "RoT"
- "SKT"
- "TftYP"
- "ToA"
- "BGDIA"
- "ERLW"
- "EGW"
- "TCE"
- "CRCotN"
- "SatO"
- "BMT"
- "GHLoE"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MM/Succubus.webp"
```
^statblock

## Environment

urban