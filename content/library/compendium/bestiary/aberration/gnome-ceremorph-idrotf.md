---
publish: true
aliases:
  - Gnome Ceremorph
created: 2026-01-27T15:31:08.926+11:00
modified: 2026-01-27T16:12:05.083+11:00
tags:
  - compendium/src/5e/idrotf
  - monster/cr/5
  - monster/size/small
  - monster/type/aberration
cssclasses:
  - json5e-monster
---

# Gnome Ceremorph

_Source: Icewind Dale: Rime of the Frostmaiden p. 303_

Mind flayers, which are described in the Monster Manual, are created through ceremorphosis, a process that begins with the implantation of an illithid tadpole in the brain of a humanoid host. After about seven days in its new home, the tadpole transforms its host into a mind flayer. The new creation typically retains no memory of its previous existence.

For reasons unknown, ceremorphosis can go awry when an illithid tadpole is implanted in the brain of a gnome. This deviation might be due to the quasi-magical nature of gnomes, or simply a facet of how their minds work. When the process is warped only slightly, the mind flayer remains gnome-sized and is called a gnome ceremorph. It retains its knowledge of the Gnomish language while becoming able to speak Deep Speech and Undercommon. It retains fragmented memories of its previous life and previous alignment, not to mention a propensity for invention.

## Laser Pistol

A gnome ceremorph often carries a home-built device that functions as a [laser pistol](compendium/items/laser-pistol.md) (see ""Firearms"" in the "Dungeon Master's Guide"). This weapon is powered by an [energy cell](compendium/items/energy-cell.md), which enables the weapon to fire 50 shots. After its last shot is expended, the device becomes inoperable. The [energy cell](compendium/items/energy-cell.md) can't be removed without destroying the weapon.

## Statblock

```ad-statblock
title: Gnome Ceremorph
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IDRotF/Gnome%20Ceremorph.webp#token)
*Small aberration, Any alignment*

- **Armor Class** 16 ([breastplate](compendium/items/breastplate.md))
- **Hit Points** 58 (`13d6 + 13`)
- **Speed** 25 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 6 (-2)|14 (+2)|12 (+1)|19 (+4)|17 (+3)|17 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Intelligence +7, Wisdom +6, Charisma +6
- **Skills** [Arcana](rules/skills.md#Arcana) +7, [Deception](rules/skills.md#Deception) +6, [Insight](rules/skills.md#Insight) +6, [Perception](rules/skills.md#Perception) +6, [Persuasion](rules/skills.md#Persuasion) +6, [Stealth](rules/skills.md#Stealth) +5
- **Senses** [darkvision](rules/senses.md#Darkvision) 120 ft., passive Perception 16
- **Gear** [laser pistol](compendium/items/laser-pistol.md)
- **Languages** Deep Speech, Gnomish, telepathy 120 ft., Undercommon
- **Challenge** 5

## Traits

***Innate Spellcasting (Psionics).*** The ceremorph's innate spellcasting ability is Intelligence (spell save DC 15). It can innately cast the following spells, requiring no components:

**At will:** [detect thoughts](compendium/spells/detect-thoughts.md), [levitate](compendium/spells/levitate.md)

**1/day each:** [dominate monster](compendium/spells/dominate-monster.md), [plane shift](compendium/spells/plane-shift.md) (self only)

***Magic Resistance.*** The ceremorph has advantage on saving throws against spells and other magical effects.

## Actions

***Tentacles.*** *Melee Weapon Attack:* +7 to hit, reach 5 ft., one creature. *Hit:* 15 (2d10 + 4) psychic damage. If the target is Medium or smaller, it is [grappled](rules/conditions.md#Grappled) (escape DC 9) and must succeed on a DC 15 Intelligence saving throw or be [stunned](rules/conditions.md#Stunned) until this grapple ends.

***Extract Brain.*** *Melee Weapon Attack:* +7 to hit, reach 5 ft., one [incapacitated](rules/conditions.md#Incapacitated) humanoid [grappled](rules/conditions.md#Grappled) by the ceremorph. *Hit:* 55 (10d10) piercing damage. If this damage reduces the target to 0 hit points, the ceremorph kills the target by extracting and devouring its brain.

***Laser Pistol.*** *Ranged Weapon Attack:* +5 to hit, range 40/120 ft., one target. *Hit:* 12 (3d6 + 2) radiant damage.

***Mind Blast (Recharge 5-6).*** The ceremorph magically emits psychic energy in a 60-foot cone. Each creature in that area must succeed on a DC 15 Intelligence saving throw or take 22 (4d8 + 4) psychic damage and be [stunned](rules/conditions.md#Stunned) for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
```

^statblock
