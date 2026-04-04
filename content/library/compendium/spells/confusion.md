---
publish: true
aliases:
  - Confusion
created: 2026-01-27T14:36:20.395+11:00
modified: 2026-01-27T15:31:07.781+11:00
tags:
  - compendium/src/5e/phb
  - spell/background/rakdos-cultist
  - spell/background/silverquill-student
  - spell/class/bard/magical-secrets
  - spell/class/druid
  - spell/class/sorcerer
  - spell/class/wizard
  - spell/level/4th-level
  - spell/optfeature/dreadful-word
  - spell/school/enchantment
  - spell/subclass/arcane-trickster
  - spell/subclass/circle-of-spores
  - spell/subclass/eldritch-knight
  - spell/subclass/knowledge-domain
  - spell/subclass/lunar-sorcery/full-moon
  - spell/subclass/oathbreaker
  - spell/subrace/gnome-mark-of-scribing
cssclasses:
  - json5e-spell
---

# Confusion

_4th-level, Enchantment_

- **Casting time:** 1 Action
- **Range:** 90 feet
- **Components:** V, S, M (three nut shells)
- **Duration:** Concentration, up to 1 minute

This spell assaults and twists creatures' minds, spawning delusions and provoking uncontrolled action. Each creature in a 10-foot-radius sphere centered on a point you choose within range must succeed on a Wisdom saving throw when you cast this spell or be affected by it.

An affected target can't take reactions and must roll a `dice:d10|noform|noparens|avg` (`d10`) at the start of each of its turns to determine its behavior for that turn.

**Confusion Behavior**

`dice: [](confusion.md#^confusion-behavior)`

| dice: d10 | Behavior |
|-----------|----------|
| 1 | The creature uses all its movement to move in a random direction. To determine the direction, roll a `dice:d8\|noform\|noparens\|avg` (`d8`) and assign a direction to each die face. The creature doesn't take an action this turn. |
| 2-6 | The creature doesn't move or take actions this turn. |
| 7-8 | The creature uses its action to make a melee attack against a randomly determined creature within its reach. If there is no creature within its reach, the creature does nothing this turn. |
| 9-10 | The creature can act and move normally. |
^confusion-behavior

At the end of each of its turns, an affected target can make a Wisdom saving throw. If it succeeds, this effect ends for that target.

**At Higher Levels.** When you cast this spell using a spell slot of 5th level or higher, the radius of the sphere increases by 5 feet for each slot level above 4th.

**Classes**: [Bard (Magical Secrets)](compendium/lists/list-spells-classes-bard.md); [Cleric (Knowledge Domain)](compendium/lists/list-spells-classes-knowledge-domain.md); [Druid (Circle of Spores)](compendium/lists/list-spells-classes-circle-of-spores-tce.md "subclass=TCE"); [Druid](compendium/lists/list-spells-classes-druid.md); [Fighter (Eldritch Knight)](compendium/lists/list-spells-classes-eldritch-knight.md); [Paladin (Oathbreaker)](compendium/lists/list-spells-classes-oathbreaker-dmg.md "subclass=DMG"); [Rogue (Arcane Trickster)](compendium/lists/list-spells-classes-arcane-trickster.md); [Sorcerer (Lunar Sorcery, Full Moon)](compendium/lists/list-spells-classes-lunar-sorcery-dsotdq.md "subclass=DSotDQ"); [Sorcerer](compendium/lists/list-spells-classes-sorcerer.md); [Wizard](compendium/lists/list-spells-classes-wizard.md)

_Source: Player's Handbook p. 224. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>_
