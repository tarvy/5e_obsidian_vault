---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mm
- monster/cr/9
- monster/size/large
- monster/type/fiend/yugoloth
statblock: inline
aliases: ["Nycaloth"]
---
# [Nycaloth](3-Mechanics/CLI/bestiary/fiend/nycaloth.md)
*Source: Monster Manual p. 314*  

The elite airborne shock troops of the yugoloths, nycaloths look like muscular gargoyles. Powerful bat wings bear them swiftly aloft in battle, and the razorsharp claws of their hands and feet cut through flesh and bone with ease. A nightmarish foe, a nycaloth strikes hard and fast without warning, then teleports away. It uses its innate magic to turn [invisible](/3-Mechanics/CLI/rules/conditions.md#invisible) or create illusory doubles of itself, further confounding its enemies.

Nycaloths are the most loyal of the yugoloths. When they find an evil master that treats them well, they are unlikely to break their agreement unless the reward for doing so is extreme.

## Yugoloths

Yugoloths are fickle fiends that inhabit the planes of Acheron, Gehenna, Hades, and Carceri. They act as mercenaries and are notorious for their shifting loyalties. They are the embodiments of avarice. Before serving under anyone's banner, a yugoloth asks the only question on its mind: *What's in it for me?*

### Spawn of Gehenna

The first yugoloths were created by a sisterhood of night hags on Gehenna. It is widely believed that Asmodeus, Lord of the Nine Hells, commissioned the work, in the hope of creating an army of fiends that were not bound to the Nine Hells. In the course of making this new army, the hags crafted four magic tomes and recorded the true names of every yugoloth they created, save one, the General of Gehenna. These tomes were called the Books of Keeping. Since knowing a fiend's true name grants power over it, the hags used the books to ensure the yugoloths' loyalty. They also used the books to capture the true names of other fiends that crossed them. It is rumored that the Books of Keeping contain the true names of a few demon lords and archdevils as well.

Petty jealousies and endless bickering caused the sisterhood to dissolve, and in the ensuing power grab, the Books of Keeping were lost or stolen. No longer indentured to anyone, the yugoloths gained independence, and they now offer their services to the highest bidder.

### Fiendish Mercenaries

Summoned yugoloths demand much for their time and loyalty. Whatever promises a yugoloth makes are quickly broken when a better opportunity presents itself. Unlike demons, yugoloths can be reasoned with, but unlike devils, they are rarely true to their word.

Yugoloths can be found anywhere, but the high cost of maintaining a yugoloth army's loyalty typically exceeds what any warlord on the Material Plane can pay. Being self-serving creatures, yugoloths quarrel among themselves constantly. A yugoloth army is more organized than a ravening horde of demons, but far less orderly and regimented than a legion of devils. Without a powerful leader to keep them in line, yugoloths fight simply to indulge their violent predilections, and only as long as it benefits them to do so.

### Back to Gehenna

When a yugoloth dies, it dissolves into a pool of ichor and reforms at full strength on the Bleak Eternity of Gehenna. Only on its native plane can a yugoloth be destroyed permanently. A yugoloth knows this and acts accordingly. When summoned to other planes, a yugoloth fights without concern for its own well-being. On Gehenna, it is more apt to retreat or plead for mercy if its demise seems imminent.

When a yugoloth is permanently destroyed, its name vanishes from every Book of Keeping. If a yugoloth is re-created by way of an unholy ritual requiring the expenditure of souls, its name reappears in the books.

### The Books of Keeping

When all four copies of the Books of Keeping disappeared, Asmodeus and the night hags lost control of their yugoloth creations. Each Book of Keeping still exists, drifting from plane to plane, where the brave and the foolish occasionally stumble upon them. A yugoloth summoned using its true name, as inscribed in the Books of Keeping, is forced to serve its summoner obediently. The yugoloth hates being controlled in this manner and isn't shy about making its displeasure known. Like a petulant child, it will follow its instructions to the letter while looking for opportunities to misinterpret them.

### The General of Gehenna

Somewhere in the brimstone wastes of Gehenna, there roams an ultroloth so strong that none contests his power: the General of Gehenna. Many yugoloths search for this great general in the hope of serving with him. They believe that service with the General of Gehenna grants power and prestige among lower planar entities.

Whatever the case, no fiend finds the General unless the General desires it. His personal name is unknown, and even the Books of Keeping contain no mention of this powerful, thoroughly evil entity.

> [!note] Variant: Yugoloth Summoning
> 
> Some yugoloths can have an action option that allows them to summon other yugoloths.
> 
> **Summon Yugoloth (1/Day).** The yugoloth chooses what to summon and attempts a magical summoning.
> 
> - An arcanaloth has a 40% chance chance of summoning one arcanaloth.  
> - A mezzoloth has a 30% chance chance of summoning one mezzoloth.  
> - A nycaloth has a 50% chance chance of summoning `1d4` mezzoloths or one nycaloth.  
> - An ultroloth has a 50% chance chance of summoning `1d6` mezzoloths, `1d4` nycaloths, or one ultroloth.  
> 
> A summoned yugoloth appears in an unoccupied space within 60 feet of its summoner, does as it pleases (unless its summoner is an ultroloth, in which case it acts as an ally of its summoner), and can't summon other yugoloths. The summoned yugoloth remains for l minute, until it or its summoner dies, or until its summoner takes a bonus action to dismiss it
^variant-yugoloth-summoning

> [!quote]- A quote from Shemeshka the Marauder  
> 
> Power. We all crave it, but only a select few of us deserve it.


```statblock
"name": "Nycaloth"
"size": "Large"
"type": "fiend"
"subtype": "yugoloth"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "123"
"hit_dice": "13d10 + 52"
"stats":
- !!int "20"
- !!int "11"
- !!int "19"
- !!int "12"
- !!int "10"
- !!int "15"
"speed": "40 ft., fly 60 ft."
"skillsaves":
  "Intimidation": !!int "6"
  "Stealth": !!int "4"
  "Perception": !!int "4"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "acid, poison"
"condition_immunities": "[poisoned](/3-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "blindsight 60 ft., darkvision 60 ft., passive Perception 14"
"languages": "Abyssal, Infernal, telepathy 60 ft."
"cr": "9"
"traits":
- "desc": "The nycaloth's innate spellcasting ability is Charisma. The nycaloth can\
    \ innately cast the following spells, requiring no material components:\n\nAt\
    \ will: [darkness](/3-Mechanics/CLI/spells/darkness.md), [detect magic](/3-Mechanics/CLI/spells/detect-magic.md),\
    \ [dispel magic](/3-Mechanics/CLI/spells/dispel-magic.md), [invisibility](/3-Mechanics/CLI/spells/invisibility.md)\
    \ (self only), [mirror image](/3-Mechanics/CLI/spells/mirror-image.md)"
  "name": "Innate Spellcasting"
- "desc": "The nycaloth has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The nycaloth's weapon attacks are magical."
  "name": "Magic Weapons"
"actions":
- "desc": "The nycaloth makes two melee attacks, or it makes one melee attack and\
    \ teleports before or after the attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 12\
    \ (2d6 + 5) slashing damage. If the target is a creature, it must succeed on\
    \ a DC 16 Constitution saving throw or take 5 (2d4) slashing damage at the start\
    \ of each of its turns due to a fiendish wound. Each time the nycaloth hits the\
    \ wounded target with this attack, the damage dealt by the wound increases by\
    \ 5 (2d4). Any creature can take an action to stanch the wound with a successful\
    \ DC 13 Wisdom ([Medicine](/3-Mechanics/CLI/rules/skills.md#Medicine)) check.\
    \ The wound also closes if the target receives magical healing."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 18\
    \ (2d12 + 5) slashing damage."
  "name": "Greataxe"
- "desc": "The nycaloth magically teleports, along with any equipment it is wearing\
    \ or carrying, up to 60 feet to an unoccupied space it can see."
  "name": "Teleport"
"source":
- "MM"
- "PotA"
- "RoT"
- "ToA"
- "WDMM"
- "BGDIA"
- "TCE"
- "KftGV"
- "PaBTSO"
- "SatO"
- "ToFW"
"image": "https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MM/Nycaloth.webp"
```
^statblock