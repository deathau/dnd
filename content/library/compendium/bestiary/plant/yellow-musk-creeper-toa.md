---
publish: true
aliases:
  - Yellow Musk Creeper
created: 2026-01-27T15:31:07.862+11:00
modified: 2026-01-27T16:12:04.694+11:00
tags:
  - compendium/src/5e/toa
  - monster/cr/2
  - monster/size/medium
  - monster/type/plant
cssclasses:
  - json5e-monster
---

# Yellow Musk Creeper

_Source: Tomb of Annihilation p. 237_

A yellow musk creeper is an unholy vine whose flowers resemble an orchid's. Bright yellow with splashes of purple, these flowers expel a musk that attracts prey. A yellow musk creeper clings to walls, pillars, gravestones, door frames, or statuary in shadowy locations, remaining motionless until it strikes.

## Humanoid Hosts

A yellow musk creeper destroys the minds of humanoids, then implants bulbs in those it kills. Twenty-four hours after being implanted, a bulb sprouts a creeper vine that magically animates the host corpse, turning it into a yellow musk zombie under the young vine's control. In addition to protecting the defenseless plant, the zombie acts as fertilizer for the young creeper vine, which grows to full size in seven days. Once it is fully grown, the new yellow musk creeper becomes mobile and bursts from its zombie host, whereupon the zombie collapses into a mound of dead offal. If the zombie is destroyed before the creeper emerges, the creeper withers and dies.

## Small Yellow Musk Zombies

A Medium humanoid transformed into a yellow musk zombie uses the stat block presented in this section. A Small humanoid transformed into a yellow musk zombie becomes a Small undead with `dice:6d6+6|noform|noparens|avg|text(27)` (`6d6 + 6`) hit points, but otherwise has the same statistics.

## Statblock

```ad-statblock
title: Yellow Musk Creeper
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Yellow%20Musk%20Creeper.webp#token)
*Medium plant, Unaligned*

- **Armor Class** 6
- **Hit Points** 60 (`11d8 + 11`)
- **Speed** 5 ft., climb 5 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)| 3 (-4)|12 (+1)| 1 (-5)|10 (+0)| 3 (-4)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** [blindsight](rules/senses.md#Blindsight) 30 ft., passive Perception 10
- **Condition Immunities** [blinded](rules/conditions.md#Blinded), [deafened](rules/conditions.md#Deafened), [exhaustion](rules/conditions.md#Exhaustion), [prone](rules/conditions.md#Prone)
- **Languages** —
- **Challenge** 2

## Traits

***False Appearance.*** While the creeper remains motionless, it is indistinguishable from an ordinary flowering vine.

***Regeneration.*** The creeper regains 10 hit points at the start of its turn. If the creeper takes fire, necrotic, or radiant damage, this trait doesn't function at the start of its next turn. The creeper dies only if it starts its turn with 0 hit points and doesn't regenerate.

## Actions

***Touch.*** *Melee Weapon Attack:* +3 to hit, reach 5 ft., one creature. *Hit:* 13 (3d8) psychic damage. If the target is a humanoid that drops to 0 hit points as a result of this damage, it dies and is implanted with a yellow musk creeper bulb. Unless the bulb is destroyed, the corpse animates as a yellow musk zombie after being dead for 24 hours. The bulb is destroyed if the creature is raised from the dead before it can transform into a yellow musk zombie, or if the corpse is targeted by a [remove curse](compendium/spells/remove-curse.md) spell or similar magic before it animates.

***Yellow Musk (3/Day).*** The creeper's flowers release a strong musk that targets all humanoids within 30 feet of it. Each target must succeed on a DC 11 Wisdom saving throw or be [charmed](rules/conditions.md#Charmed) by the creeper for 1 minute. A creature [charmed](rules/conditions.md#Charmed) in this way does nothing on its turn except move as close as it can to the creeper. A creature [charmed](rules/conditions.md#Charmed) by the creeper can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
```

^statblock
