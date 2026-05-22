---
publish: true
aliases:
  - Hierophant Medusa
created: 2026-01-27T15:31:07.877+11:00
modified: 2026-01-27T16:12:04.719+11:00
tags:
  - compendium/src/5e/bmt
  - monster/cr/17
  - monster/size/large
  - monster/type/monstrosity
cssclasses:
  - json5e-monster
---

# Hierophant Medusa

_Source: The Book of Many Things p. 179_

Sometimes deeply devout people, usually either Humanoids or medusas, dedicate themselves to a cause and are transformed by a deity or magic into hierophant medusas—beings with powerful snakelike tails for their lower body, snakes for hair, and a petrifying gaze. The first hierophant medusa was transformed by the power of the Euryale card when that individual was inspired by Euryale's story and unwavering conviction.

These medusas are divinely empowered champions, drawing their power from a cosmic truth, the will of a deity, or the primal forces of nature. They gather and inspire followers, protecting their people and guiding them to fulfill the medusa's divine purpose. The Divine Purpose table offers suggestions for motivations. Roll on the table, or use the entries as inspiration to create your own.

`dice: [](hierophant-medusa-bmt.md#^purpose)`

| dice: d6 | Purpose |
|----------|---------|
| 1 | Protect a sanctuary that hides martyrs' remains until the martyrs are called back to life to oppose a world-changing foe. |
| 2 | Gather the lost shards of a dead god's petrified body, and reunite them on the altar in the medusa's lair. |
| 3 | Maintain a planar crossing from which great power flows while also curtailing the effects of that power as it infuses the world. |
| 4 | Seek out a new generation of champions, and train them to fight in a war. |
| 5 | Tend a sacred beacon fed by the Outer Planes, sending embers of that beacon to the corners of the world to maintain a divine shroud. |
| 6 | Watch the entrance to a slumbering titan's tomb for any sign the titan might awaken, and repel the forces that seek to break the tomb's seal. |
^purpose

## A Medusa's Lair

A medusa's lair is often decorated with the petrified bodies of creatures that raised arms against the medusa or its followers. The lair is typically a rich repository of knowledge, with lore both worldly and esoteric filling books, scrolls, tablets, or stranger archives—such as magical crystals that hold captured memories or the voices of those long dead. You can use this lair and the lair actions described for any medusa, including the hierophant medusa or the medusa in the Monster Manual.

## Statblock

```ad-statblock
title: Hierophant Medusa
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BMT/Hierophant%20Medusa.webp#token)
*Large monstrosity, Any alignment*

- **Armor Class** 17 (natural armor)
- **Hit Points** 237 (`25d10 + 100`)
- **Speed** 40 ft., climb 40 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)|20 (+5)|18 (+4)|15 (+2)|23 (+6)|22 (+6)|

- **Proficiency Bonus** +6
- **Saving Throws** Constitution +10, Wisdom +12
- **Skills** [Insight](rules/skills.md#Insight) +12, [Perception](rules/skills.md#Perception) +12, [Persuasion](rules/skills.md#Persuasion) +12, [Religion](rules/skills.md#Religion) +8, [Stealth](rules/skills.md#Stealth) +11
- **Senses** passive Perception 22
- **Damage Immunities** poison
- **Condition Immunities** [charmed](rules/conditions.md#Charmed), [frightened](rules/conditions.md#Frightened), [petrified](rules/conditions.md#Petrified), [poisoned](rules/conditions.md#Poisoned)
- **Languages** Common plus any three languages (Abyssal, Celestial, Druidic, or Infernal recommended)
- **Challenge** 17

## Traits

***Devotion's Call (1/Day).*** The medusa can cast the [Resurrection](compendium/spells/resurrection.md) spell, requiring no material components and using Wisdom as the spellcasting ability.

***Legendary Resistance (4/Day).*** If the medusa fails a saving throw, it can choose to succeed instead.

## Actions

***Multiattack.*** The medusa makes one Constrict attack, one Final Blade attack, and one Snake Hair attack. Alternatively, it makes two Wrathful Strike attacks.

***Constrict.*** *Melee Weapon Attack:* +12 to hit, reach 10 ft., one target. *Hit:* 16 (3d6 + 6) bludgeoning damage, and if the target is a Medium or smaller creature, it has the [grappled](rules/conditions.md#Grappled) condition (escape DC 20). Until this grapple ends, the target has the [restrained](rules/conditions.md#Restrained) condition, and the medusa can't constrict another creature.

***Final Blade.*** *Melee Weapon Attack:* +12 to hit, reach 5 ft., one target. *Hit:* 13 (2d6 + 6) slashing damage plus 21 (6d6) force damage. If the target has at least one head and the medusa rolled a 20 on the attack roll, the target is decapitated and dies if it fails a DC 20 Constitution saving throw and can't survive without that head. A target is immune to this effect if it takes none of the damage, has legendary actions, or is Huge or larger. Such a creature takes an extra 28 (8d6) force damage from the hit.

***Snake Hair.*** *Melee Weapon Attack:* +12 to hit, reach 5 ft., one target. *Hit:* 11 (1d10 + 6) piercing damage plus 5 (1d10) poison damage.

***Wrathful Strike.*** *Ranged Spell Attack:* +12 to hit, range 120 ft., one creature. *Hit:* 22 (3d10 + 6) radiant damage, and the target has the [blinded](rules/conditions.md#Blinded) condition until the end of its next turn.

***Spellcasting.*** The medusa casts one of the following spells, requiring no material components and using Wisdom as the spellcasting ability (spell save DC 20):

**At will:** [Light](compendium/spells/light.md), [Spare the Dying](compendium/spells/spare-the-dying.md), [Thaumaturgy](compendium/spells/thaumaturgy.md)

**2/day:** [Mass Cure Wounds](compendium/spells/mass-cure-wounds.md) (cast at 8th level)

**1/day each:** [Blade Barrier](compendium/spells/blade-barrier.md), [Divination](compendium/spells/divination.md), [Greater Restoration](compendium/spells/greater-restoration.md)

## Bonus Actions

***Petrifying Gaze (Recharge 4-6).*** The medusa unleashes petrifying magic from its eyes in a 30-foot cone. Each creature in that area must make a DC 18 Constitution saving throw if it doesn't have the [blinded](rules/conditions.md#Blinded) condition. If the saving throw fails by 5 or more, the creature has the [petrified](rules/conditions.md#Petrified) condition. Otherwise, on a failed save, the creature takes 10 (3d6) force damage, begins to turn to stone, and has the [restrained](rules/conditions.md#Restrained) condition. The [restrained](rules/conditions.md#Restrained) creature must repeat the saving throw at the end of its next turn. On a failed save, it has the [petrified](rules/conditions.md#Petrified) condition, and on a successful save, the effect ends on it. The petrification lasts until the creature is freed by the [Greater Restoration](compendium/spells/greater-restoration.md) spell or other magic.

A creature can use its reaction, if available, to shut its eyes to avoid the saving throw. If the creature does so, it has the [blinded](rules/conditions.md#Blinded) condition until the end of its next turn.

## Legendary Actions

Legendary Action Uses: 3. Immediately after another creature's turn, the hierophant medusa can expend a use to take one of the following actions. The hierophant medusa regains all expended uses at the start of each of its turns.

***Move.*** The medusa moves up to its speed without provoking opportunity attacks.

***Wrathful Blast (Costs 2 Actions).*** The medusa makes one Wrathful Strike attack.

***Final Slash (Costs 3 Actions).*** The medusa makes one Final Blade attack with advantage.

![Hierophant Medusa](compendium/bestiary/legendary-group/hierophant-medusa-bmt.md)
```

^statblock
