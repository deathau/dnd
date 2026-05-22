---
publish: true
aliases:
  - Witherbloom Pledgemage
created: 2026-01-27T15:31:07.841+11:00
modified: 2026-01-27T16:12:04.684+11:00
tags:
  - compendium/src/5e/scc
  - monster/cr/4
  - monster/size/small-or-medium
  - monster/type/humanoid/druid
cssclasses:
  - json5e-monster
---

# Witherbloom Pledgemage

_Source: Strixhaven: A Curriculum of Chaos p. 222_

Deep in the fog and muck of the swamp, the students of Witherbloom College—first as apprentices and then as pledgemages—study the cycle of life and death. Their magic is fueled by what they call life essence: the ubiquitous energy that runs through living things.

Witherbloom students learn how to concoct magical potions and talismans, in addition to their spellcasting studies. Their magic ranges from necrotic shadows and withering bursts of poison to flourishing bursts of plant life.

## Witherbloom Scholars

Witherbloom College studies the magic inherent in the natural cycle of life and death. Witherbloom professors approach the philosophy from different directions, with one methodology focusing on decay and the other dealing with growth.

## Statblock

```ad-statblock
title: Witherbloom Pledgemage
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/SCC/Witherbloom%20Pledgemage.webp#token)
*Small or Medium humanoid (druid), Any alignment*

- **Armor Class** 12 (15 with vociferous form)
- **Hit Points** 66 (`12d8 + 12`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|15 (+2)|13 (+1)|14 (+2)|17 (+3)|11 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** Constitution +3, Wisdom +5
- **Skills** [Medicine](rules/skills.md#Medicine) +5, [Nature](rules/skills.md#Nature) +6, [Perception](rules/skills.md#Perception) +7
- **Senses** passive Perception 17
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](rules/conditions.md#Poisoned)
- **Languages** Common plus any two languages
- **Challenge** 4

## Traits

***Regeneration.*** As long as the pledgemage has at least 1 hit point remaining, the pledgemage regains 5 hit points at the start of its turn.

***Verdant Talisman.*** At the end of a 10-minute ritual, the pledgemage can touch one willing creature (including itself) and bestow upon it a small talisman imbued with magic. Upon receiving the talisman, the creature gains 10 temporary hit points, and it can add 1d6 to its initiative rolls while it wears the talisman. These benefits last for 1 hour or until the pledgemage conducts another ritual to bestow another talisman. When the benefits expire, the talisman crumbles to dust.

## Actions

***Briar Vine.*** *Melee Spell Attack:* +5 to hit, reach 15 ft., one target. *Hit:* 8 (1d10 + 3) piercing damage plus 18 (4d8) poison damage. If the target is a Large or smaller creature, the apprentice can pull it up to 10 feet closer to itself.

***Spellcasting.*** The apprentice casts one of the following spells, requiring no material components and using Wisdom as the spellcasting ability:

**At will:** [druidcraft](compendium/spells/druidcraft.md), [spare the dying](compendium/spells/spare-the-dying.md)

**1/day each:** [death ward](compendium/spells/death-ward.md), [pass without trace](compendium/spells/pass-without-trace.md), [speak with plants](compendium/spells/speak-with-plants.md)

## Bonus Actions

***Vociferous Form (1/Day).*** The pledgemage transforms into an avatar of plants and shadow. While in this form, the pledgemage adds its Wisdom modifier to its AC if it isn't wearing armor or wielding a shield, and it has advantage on attack rolls against any creature missing hit points. This form lasts for 1 minute or until the pledgemage is reduced to 0 hit points.

## Reactions

***Wither Burst.*** When the pledgemage sees a creature within 30 feet of itself drop to 0 hit points, the pledgemage channels the expended life essence and targets another creature it can see within 30 feet of itself. The target must succeed on a DC 13 Constitution saving throw or become [poisoned](rules/conditions.md#Poisoned) for 1 minute. While [poisoned](rules/conditions.md#Poisoned) in this way, the target takes 3 (1d6) poison damage at the start of each of its turns. The target can repeat the save at the end of each of its turns, ending the effect on itself on a success.
```

^statblock
