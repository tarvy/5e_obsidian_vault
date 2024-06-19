---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mm
- monster/cr/9
- monster/environment/urban
- monster/size/medium
- monster/type/aberration/shapechanger
statblock: inline
aliases: ["Gray Slaad"]
---
# [Gray Slaad](3-Mechanics/CLI/bestiary/aberration/gray-slaad.md)
*Source: Monster Manual p. 277*  

Outside of Limbo, gray slaadi act as living extensions of the will of their masters, the death slaadi. A gray slaad journeys to the Material Plane on errands of doom, often taking humanoid form. A gray slaad learns how to master the use of a greatsword and imbue it with its own innate magic.

A gray slaad that eats the entire corpse of a dead death slaad instantly transforms into a death slaad.

## Slaadi

In the Ever-Changing Chaos of Limbo, bits of forest and meadow, ruined castles, and isolated islands drift through a tumult of fire, water, earth, and wind. The foremost inhabitants of this inhospitable plane are the toad-like slaadi. Slaadi are undisciplined and have no formal hierarchy, although weaker slaadi obey stronger ones under threat of annihilation.

### The Spawning Stone

Long ago, Primus, overlord of the modrons, created a gigantic, geometrically complex stone imbued with the power of law. He then cast it adrift in Limbo, believing that the stone would bring order to the chaos of that plane and halt the spread of chaos to other planes. As the stone's power grew, it became possible for creatures with ordered minds, such as modrons and githzerai, to create enclaves in Limbo. However, Primus's creation had an unforeseen side effect: the chaotic energy absorbed by the stone spawned the horrors that came to be known as slaadi. Sages refer to Primus's massive creation as the Spawning Stone for this reason.

The slaadi wiped out every last modron enclave in Limbo. As creatures of utter chaos, slaadi loathe modrons and attack them on sight. Nonetheless, Primus stands by his creation and either doesn't perceive the slaadi as threats or chooses to ignore them.

### Birth and Transformation

Slaadi have horrific cycles of reproduction. Slaadi reproduce either by implanting humanoid hosts with eggs or by infecting them with a transformative disease called chaos phage. Each color of slaad reproduces or transforms in a different way, with red slaadi spawning blue and green slaadi, and blue slaadi spawning red and green. Each green slaad undergoes a lifelong cycle of transformation into the more powerful gray and death slaadi. With each transformation, the slaad retains its memories.

### Shapechangers

Some slaadi can transform into the humanoid creatures from which they were originally spawned. These slaadi return to the Material Plane to sow discord in the guise of their former selves.

> [!note] Variant: Slaad Control Gems
> 
> As a slaad emerges from the Spawning Stone, the stone magically implants a fragment of itself in the slaad's brain. This fragment takes the form of a magic gem roughly the size and shape of a human child's fist. The gem is the same color as the slaad. Another creature can use magic to draw forth a slaad's gem and use it to subjugate the slaad. The slaad must obey whoever possesses its gem. If a slaad's gem is destroyed, the slaad can no longer be controlled in this way.
> 
> A slaad born from something other than the Spawning Stone has no gem in its brain, but it gains one if it ever comes into contact with the Spawning Stone. Slaadi on Limbo are attracted to the Spawning Stone, so most end up with a gem. A slaad with a control gem in its brain has the following additional trait.
> 
> **Control Gem.** Implanted in the slaad's brain is a magic control gem. The slaad must obey whoever possesses the gem and is immune to being [charmed](/3-Mechanics/CLI/rules/conditions.md#charmed) while so controlled.
> 
> Certain spells can be used to acquire the gem. If the slaad fails its saving throw against imprisonment, the spell can transfer the gem to the spellcaster's open hand, instead of imprisoning the slaad. A [wish](/3-Mechanics/CLI/spells/wish.md) spell, if cast in the slaad's presence, can be worded to acquire the gem.
> 
> A [greater restoration](/3-Mechanics/CLI/spells/greater-restoration.md) spell cast on the slaad destroys the gem without harming the slaad.
> 
> Someone who is proficient in Wisdom ([Medicine](/3-Mechanics/CLI/rules/skills.md#Medicine)) can remove the gem from an [incapacitated](/3-Mechanics/CLI/rules/conditions.md#incapacitated) slaad. Each try requires 1 minute of uninterrupted work and a successful DC 20 Wisdom ([Medicine](/3-Mechanics/CLI/rules/skills.md#Medicine)) check. Each failed attempt deals 22 (`4d10`) psychic damage to the slaad.
^variant-slaad-control-gems

> [!quote]-  
> 
> Embedded in a slaad's brain is a magic gem. Acquire it, and the slaad is yours to command.


```statblock
"name": "Gray Slaad"
"size": "Medium"
"type": "aberration"
"subtype": "shapechanger"
"alignment": "Chaotic Neutral"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "127"
"hit_dice": "17d8 + 51"
"stats":
- !!int "17"
- !!int "17"
- !!int "16"
- !!int "13"
- !!int "8"
- !!int "14"
"speed": "30 ft."
"skillsaves":
  "Perception": !!int "7"
  "Arcana": !!int "5"
"damage_resistances": "acid, cold, fire, lightning, thunder"
"senses": "blindsight 60 ft., darkvision 60 ft., passive Perception 17"
"languages": "Slaad, telepathy 60 ft."
"cr": "9"
"traits":
- "desc": "The slaad's innate spellcasting ability is Charisma (spell save DC 14).\
    \ The slaad can innately cast the following spells, requiring no material components:\n\
    \nAt will: [detect magic](/3-Mechanics/CLI/spells/detect-magic.md), [detect\
    \ thoughts](/3-Mechanics/CLI/spells/detect-thoughts.md), [invisibility](/3-Mechanics/CLI/spells/invisibility.md)\
    \ (self only), [mage hand](/3-Mechanics/CLI/spells/mage-hand.md), [major image](/3-Mechanics/CLI/spells/major-image.md)\n\
    \n1/day: [plane shift](/3-Mechanics/CLI/spells/plane-shift.md) (self only)\n\
    \n2/day each: [fear](/3-Mechanics/CLI/spells/fear.md), [fly](/3-Mechanics/CLI/spells/fly.md),\
    \ [fireball](/3-Mechanics/CLI/spells/fireball.md), [tongues](/3-Mechanics/CLI/spells/tongues.md)"
  "name": "Innate Spellcasting"
- "desc": "The slaad can use its action to polymorph into a Small or Medium humanoid,\
    \ or back into its true form. Its statistics, other than its size, are the same\
    \ in each form. Any equipment it is wearing or carrying isn't transformed. It\
    \ reverts to its true form if it dies."
  "name": "Shapechanger"
- "desc": "The slaad has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The slaad's weapon attacks are magical."
  "name": "Magic Weapons"
- "desc": "The slaad regains 10 hit points at the start of its turn if it has at least\
    \ 1 hit point."
  "name": "Regeneration"
"actions":
- "desc": "The slaad makes three attacks: one with its bite and two with its claws\
    \ or greatsword."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage."
  "name": "Bite (Slaad Form Only)"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 8 (1d10\
    \ + 3) slashing damage."
  "name": "Claws (Slaad Form Only)"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) slashing damage."
  "name": "Greatsword"
"source":
- "MM"
- "ToA"
- "WDMM"
- "WBtW"
- "KftGV"
- "PaBTSO"
- "ToFW"
- "BMT"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MM/Gray%20Slaad.webp"
```
^statblock

## Environment

urban