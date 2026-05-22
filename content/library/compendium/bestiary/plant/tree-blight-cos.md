---
publish: true
aliases:
  - Tree Blight
created: 2026-01-27T15:31:08.820+11:00
modified: 2026-01-27T16:12:05.021+11:00
tags:
  - compendium/src/5e/cos
  - monster/cr/7
  - monster/size/huge
  - monster/type/plant
cssclasses:
  - json5e-monster
---

# Tree Blight

_Source: Curse of Strahd p. 230, The Wild Beyond the Witchlight_

Blights (as described in the Monster Manual) are evil, ambulatory plant creatures, and a tree blight is a particularly enormous variety. It looks like a dead tree or treant, 30 feet tall, with spongy wooden flesh, thorny branches, and rubbery roots that trail behind it. It has blood for sap and is so saturated with blood that it doesn't catch fire easily.

## Vicious Carnivore

A tree blight feeds on warm-blooded prey and takes perverse delight in causing carnage. It strikes with its heavy branches and crushes prey to death with its roots. It can open its gaping, tooth-filled mouth and bite a creature caught in its roots. The roots of a tree blight can be severed, though cutting them causes the blight no harm.

## Blight Animosity

A tree blight will often fight alongside other kinds of blights, but it hates other tree blights and will attack them given the chance. Tree blights also hate treants, and the feeling is mutual.

## Statblock

```ad-statblock
title: Tree Blight
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoS/Tree%20Blight.webp#token)
*Huge plant, Neutral Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 92 (`8d12 + 40`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|10 (+0)|20 (+5)| 6 (-2)|10 (+0)| 3 (-4)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** [blindsight](rules/senses.md#Blindsight) 60 ft. (blind beyond this radius), passive Perception 10
- **Condition Immunities** [blinded](rules/conditions.md#Blinded), [deafened](rules/conditions.md#Deafened)
- **Languages** understands Common and Druidic but doesn't speak
- **Challenge** 7

## Traits

***False Appearance.*** While the blight remains motionless, it is indistinguishable from a dead tree.

***Siege Monster.*** The blight deals double damage to objects and structures.

## Actions

***Multiattack.*** The blight makes one Branch attack and one Grasping Root attack.

***Branch.*** *Melee Weapon Attack:* +9 to hit, reach 15 ft., one target. *Hit:* 16 (3d6 + 6) bludgeoning damage.

***Grasping Root.*** *Melee Weapon Attack:* +9 to hit, reach 15 ft., one creature not [grappled](rules/conditions.md#Grappled) by the blight. *Hit:* The target is [grappled](rules/conditions.md#Grappled) (escape DC 15). Until the grapple ends, the target takes 9 (1d6 + 6) bludgeoning damage at the start of each of its turns. The root has AC 15 and can be severed by dealing 6 slashing damage or more to it at once. Cutting the root doesn't hurt the blight, but ends the grapple.

## Bonus Actions

***Bite.*** *Melee Weapon Attack:* +9 to hit, reach 5 ft., one creature [grappled](rules/conditions.md#Grappled) by the blight. *Hit:* 19 (3d8 + 6) piercing damage.
```

^statblock
