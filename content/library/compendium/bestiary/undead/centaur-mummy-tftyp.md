---
publish: true
aliases:
  - Centaur Mummy
created: 2026-01-27T15:31:08.484+11:00
modified: 2026-01-27T16:12:04.804+11:00
tags:
  - compendium/src/5e/tftyp
  - monster/cr/6
  - monster/size/large
  - monster/type/undead
cssclasses:
  - json5e-monster
---

# Centaur Mummy

_Source: Tales from the Yawning Portal p. 231_

In The Hidden Shrine of Tamoachan, characters must contend with a mummified centaur that wants to prevent them from moving any farther into the dungeon. Combining the most lethal features of two creature types, the centaur mummy can attack nearby targets with its melee weapons while trying to use its Dreadful Glare against enemies that hold back.

```ad-statblock
title: Centaur Mummy
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TftYP/Centaur%20Mummy.webp#token)
*Large undead, Lawful Evil*

- **Armor Class** 13 (natural armor)
- **Hit Points** 85 (`10d10 + 30`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|12 (+1)|16 (+3)| 5 (-3)|14 (+2)|12 (+1)|

- **Proficiency Bonus** +3
- **Saving Throws** Wisdom +5
- **Skills** ⏤
- **Senses** [darkvision](rules/senses.md#Darkvision) 60 ft., passive Perception 12
- **Damage Vulnerabilities** fire
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](rules/conditions.md#Charmed), [exhaustion](rules/conditions.md#Exhaustion), [frightened](rules/conditions.md#Frightened), [paralyzed](rules/conditions.md#Paralyzed), [poisoned](rules/conditions.md#Poisoned)
- **Gear** [pike](compendium/items/pike.md)
- **Languages** Common, Sylvan
- **Challenge** 6

## Traits

***Charge.*** If the centaur mummy moves at least 20 feet straight toward a target and then hits it with a pike attack on the same turn, the target takes an extra 10 (3d6) piercing damage.

## Actions

***Multiattack.*** The centaur mummy makes two melee attacks, one with its pike and one with its hooves, or it attacks with its pike and uses Dreadful Glare.

***Pike.*** *Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:* 10 (1d10 + 5) piercing damage.

***Hooves.*** *Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) piercing damage plus 10 (3d6) necrotic damage. If the target is a creature, it must succeed on a DC 14 Constitution saving throw or be cursed with mummy rot. The cursed target can't regain hit points, and its hit point maximum decreases by 10 (3d6) for every 24 hours that elapse. If the curse reduces the target's hit point maximum to 0, the target dies, and its body turns to dust. The curse lasts until removed by the [remove curse](compendium/spells/remove-curse.md) spell or similar magic.

***Dreadful Glare.*** The centaur mummy targets one creature it can see within 60 feet of it. If the target can see the mummy, the target must succeed on a DC 12 Wisdom saving throw against this magic or become [frightened](rules/conditions.md#Frightened) until the end of the mummy's next turn. If the target fails the saving throw by 5 or more, it is also [paralyzed](rules/conditions.md#Paralyzed) for the same duration. A target that succeeds on the saving throw is immune to the Dreadful Glare of all mummies (but not mummy lords) for the next 24 hours.
```

^statblock
