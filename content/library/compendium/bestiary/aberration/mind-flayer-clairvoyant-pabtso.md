---
publish: true
aliases:
  - Mind Flayer Clairvoyant
created: 2026-01-27T15:31:09.135+11:00
modified: 2026-01-27T16:12:05.216+11:00
tags:
  - compendium/src/5e/pabtso
  - monster/cr/11
  - monster/size/medium
  - monster/type/aberration
cssclasses:
  - json5e-monster
---

# Mind Flayer Clairvoyant

_Source: Phandelver and Below: The Shattered Obelisk p. 209_

In pursuit of reconstructing their lost empire, a few mind flayers have turned to their home plane, the Far Realm, for answers. A mind flayer clairvoyant has peered into that realm's starless depths and been subsequently rewarded with extraordinary powers.

Instead of heeding an elder brain, a mind flayer clairvoyant listens to the whispers and whims of the voices of the Far Realm. In addition to feasting on brains, a mind flayer clairvoyant can summon tentacles that rip through the fabric of reality and distort the minds of enemies.

## Mind Flayers

Mind flayers, also known as illithids, feast on the brains of Humanoids across the multiverse. They are distinguished by their purple-toned skin and octopus-like heads, from which extend writhing tentacles.

## Statblock

```ad-statblock
title: Mind Flayer Clairvoyant
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PaBTSO/Mind%20Flayer%20Clairvoyant.webp#token)
*Medium aberration, typically  Lawful Evil*

- **Armor Class** 15 ([breastplate](compendium/items/breastplate.md))
- **Hit Points** 156 (`24d8 + 48`)
- **Speed** 30 ft., fly 60 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|12 (+1)|15 (+2)|21 (+5)|17 (+3)|18 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Intelligence +9, Wisdom +7, Charisma +8
- **Skills** [Arcana](rules/skills.md#Arcana) +9, [Insight](rules/skills.md#Insight) +7, [Perception](rules/skills.md#Perception) +7, [Stealth](rules/skills.md#Stealth) +5
- **Senses** [darkvision](rules/senses.md#Darkvision) 120 ft., [truesight](rules/senses.md#Truesight) 15 ft., passive Perception 17
- **Damage Resistances** psychic
- **Condition Immunities** [blinded](rules/conditions.md#Blinded), [charmed](rules/conditions.md#Charmed), [frightened](rules/conditions.md#Frightened)
- **Languages** Deep Speech, telepathy 120 ft., Undercommon
- **Challenge** 11

## Traits

***Legendary Resistance (3/Day).*** If the mind flayer fails a saving throw, it can choose to succeed instead.

***Magic Resistance.*** The mind flayer has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The mind flayer makes two Tentacle attacks.

***Tentacle.*** *Melee Weapon Attack:* +9 to hit, reach 5 ft., one creature. *Hit:* 21 (3d10 + 5) psychic damage. If the target is Medium or smaller, it has the [grappled](rules/conditions.md#Grappled) condition (escape DC 17) and must succeed on a DC 17 Intelligence saving throw or have the [incapacitated](rules/conditions.md#Incapacitated) condition until the grapple ends.

***Extract Brain.*** *Melee Weapon Attack:* +9 to hit, reach 5 ft., one [incapacitated](rules/conditions.md#Incapacitated) Humanoid [grappled](rules/conditions.md#Grappled) by the mind flayer. *Hit:* 55 (10d10) piercing damage. If this damage reduces the target to 0 hit points, the mind flayer kills it by extracting and devouring its brain.

***Unleash Void (Recharge 5-6).*** The mind flayer opens a rift into the Far Realm, centered on a point the mind flayer can see within 60 feet of itself, and a tentacle lashes across creatures near the rift. Each creature other than mind flayers within 30 feet of the rift must make a DC 17 Intelligence saving throw, after which the tentacle disappears and the rift closes. On a failed save, a creature takes 18 (4d8) cold damage from the rift plus 18 (4d8) psychic damage from the tentacle and has the [stunned](rules/conditions.md#Stunned) condition for 1 minute. On a successful save, a creature takes half as much damage only. A [stunned](rules/conditions.md#Stunned) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Spellcasting (Psionics).*** The mind flayer casts one of the following spells, requiring no spell components and using Intelligence as the spellcasting ability (spell save DC 17):

**At will:** [detect magic](compendium/spells/detect-magic.md), [detect thoughts](compendium/spells/detect-thoughts.md), [mage hand](compendium/spells/mage-hand.md) (the hand is invisible)

**3/day each:** [clairvoyance](compendium/spells/clairvoyance.md) (as an action), [dispel magic](compendium/spells/dispel-magic.md)

**1/day:** [plane shift](compendium/spells/plane-shift.md) (self only)

## Reactions

***Warp Reality.*** When hit by an attack roll, the mind flayer gains a +4 bonus to its AC against that attack roll, potentially causing it to miss. Then the mind flayer, along with any equipment it is wearing or carrying, magically teleports up to 60 feet to an unoccupied space it can see.
```

^statblock
