---
publish: true
aliases:
  - False Lich
created: 2026-01-27T15:31:08.782+11:00
modified: 2026-01-27T16:12:04.985+11:00
tags:
  - compendium/src/5e/veor
  - monster/cr/21
  - monster/size/medium
  - monster/type/undead
cssclasses:
  - json5e-monster
---

# False Lich

_Source: Vecna: Eve of Ruin p. 220_

Occasionally, liches create nefarious magical copies of themselves to fool enemies, to guard treasure, or for other inscrutable reasons.

To create a false lich, a lich binds a shred of its life force to a corpse in a profane ritual. This transforms the corpse into a near-identical copy of the lich with immense necrotic power and some of its creator's arcane prowess. The creator then embeds enchanted gemstones into the corpse's eye sockets; the gems allow the false lich to trap creatures' souls and transfer the souls to its creator.

A false lich often gradually gains a sense of self-identity. While many false liches remain steadfastly loyal to their creators, others resent their creators for imprisoning and abandoning them.

```ad-statblock
title: False Lich
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/False%20Lich.webp#token)
*Medium undead, typically  Neutral Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 199 (`21d8 + 105`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|16 (+3)|20 (+5)|25 (+7)|19 (+4)|15 (+2)|

- **Proficiency Bonus** +7
- **Saving Throws** Constitution +12, Intelligence +14, Wisdom +11, Charisma +9
- **Skills** ⏤
- **Senses** [truesight](rules/senses.md#Truesight) 60 ft., passive Perception 14
- **Damage Immunities** necrotic; poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](rules/conditions.md#Charmed), [exhaustion](rules/conditions.md#Exhaustion), [frightened](rules/conditions.md#Frightened), [paralyzed](rules/conditions.md#Paralyzed), [poisoned](rules/conditions.md#Poisoned), [stunned](rules/conditions.md#Stunned)
- **Languages** Abyssal, Common, Draconic, Dwarvish, Elvish, Giant, Infernal, Primordial, Undercommon
- **Challenge** 21

## Traits

***Legendary Resistance (3/Day).*** If the false lich fails a saving throw, it can choose to succeed instead.

***Magic Resistance.*** The false lich has advantage on saving throws against spells and magical effects.

## Actions

***Multiattack.*** The false lich makes two Death Rend attacks and uses Bloodcurdling Lament if available.

***Death Rend.*** *Melee Spell Attack:* +14 to hit, reach 5 ft., one target. *Hit:* 23 (3d10 + 7) necrotic damage.

***Bloodcurdling Lament (Recharge 5-6).*** The false lich emits a hideous shriek charged with malignant energy. Each creature within 30 feet of the false lich must succeed on a DC 22 Wisdom saving throw or have the [frightened](rules/conditions.md#Frightened) condition for 1 minute. While [frightened](rules/conditions.md#Frightened) in this way, a creature also has the [unconscious](rules/conditions.md#Unconscious) condition. An affected creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Spellcasting.*** The false lich casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 22):

**At will:** [Detect Magic](compendium/spells/detect-magic.md), [Fly](compendium/spells/fly.md), [Mage Hand](compendium/spells/mage-hand.md), [Prestidigitation](compendium/spells/prestidigitation.md)

**3/day each:** [Dispel Magic](compendium/spells/dispel-magic.md), [Invisibility](compendium/spells/invisibility.md) (self only)

**1/day each:** [Globe of Invulnerability](compendium/spells/globe-of-invulnerability.md), [Hold Monster](compendium/spells/hold-monster.md)

## Bonus Actions

***Soul Siphon.*** The false lich targets one creature it can see within 120 feet of itself. The target must make a DC 22 Charisma saving throw; if the target has the [unconscious](rules/conditions.md#Unconscious) condition, it has disadvantage on this saving throw. The target takes 21 (6d6) force damage on a failed save or half as much damage on a successful one. The false lich then regains a number of hit points equal to the amount of force damage taken.

If this damage reduces the target to 0 hit points, the target immediately dies, its body disappears, and its soul is trapped inside one of the soul gems within the false lich's skull. After 24 hours, the gem transfers the soul to the false lich's creator.

When the false lich is reduced to 0 hit points, it is destroyed and disintegrates, leaving behind the gems. Crushing a gem releases any souls trapped within, at which point the soul's body re-forms in an unoccupied space nearest to the gem and in the same state as it was when its soul was trapped.

## Legendary Actions

Legendary Action Uses: 3. Immediately after another creature's turn, the false lich can expend a use to take one of the following actions. The false lich regains all expended uses at the start of each of its turns.

***Spiteful Teleport.*** The false lich, along with anything it is wearing or carrying, teleports to an unoccupied space it can see within 60 feet of itself. It then makes one Death Rend attack if possible.

***Cast a Spell (Costs 2 Actions).*** The false lich uses Spellcasting.
```

^statblock
