---
publish: true
aliases:
  - Sleep
created: 2026-01-27T14:36:20.428+11:00
modified: 2026-01-27T15:31:08.758+11:00
tags:
  - compendium/src/5e/phb
  - spell/background/dimir-operative
  - spell/class/bard/magical-secrets
  - spell/class/sorcerer
  - spell/class/wizard
  - spell/feat/aberrant-dragonmark
  - spell/feat/fey-touched
  - spell/feat/magic-initiate/wizard-spells
  - spell/feat/strixhaven-initiate/witherbloom-3
  - spell/level/1st-level
  - spell/school/enchantment
  - spell/subclass/arcane-trickster
  - spell/subclass/eldritch-knight
  - spell/subclass/oath-of-redemption
  - spell/subclass/the-archfey
  - spell/subclass/twilight-domain
  - spell/subrace/halfling-mark-of-hospitality
cssclasses:
  - json5e-spell
---

# Sleep

_1st-level, Enchantment_

- **Casting time:** 1 Action
- **Range:** 90 feet
- **Components:** V, S, M (a pinch of fine sand, rose petals, or a cricket)
- **Duration:** 1 minute

This spell sends creatures into a magical slumber. Roll `dice:5d8|noform|noparens|avg` (`5d8`); the total is how many hit points of creatures this spell can affect. Creatures within 20 feet of a point you choose within range are affected in ascending order of their current hit points (ignoring [unconscious](rules/conditions.md#Unconscious) creatures).

Starting with the creature that has the lowest current hit points, each creature affected by this spell falls [unconscious](rules/conditions.md#Unconscious) until the spell ends, the sleeper takes damage, or someone uses an action to shake or slap the sleeper awake. Subtract each creature's hit points from the total before moving on to the creature with the next lowest hit points. A creature's hit points must be equal to or less than the remaining total for that creature to be affected.

Undead and creatures immune to being [charmed](rules/conditions.md#Charmed) aren't affected by this spell.

**At Higher Levels.** When you cast this spell using a spell slot of 2nd level or higher, roll an additional `dice:2d8|noform|noparens|avg|text(2d8)` for each slot level above 1st.

**Classes**: [Bard (Magical Secrets)](compendium/lists/list-spells-classes-bard.md); [Cleric (Twilight Domain)](compendium/lists/list-spells-classes-twilight-domain-tce.md "subclass=TCE"); [Fighter (Eldritch Knight)](compendium/lists/list-spells-classes-eldritch-knight.md); [Paladin (Oath of Redemption)](compendium/lists/list-spells-classes-oath-of-redemption-xge.md "subclass=XGE"); [Rogue (Arcane Trickster)](compendium/lists/list-spells-classes-arcane-trickster.md); [Sorcerer](compendium/lists/list-spells-classes-sorcerer.md); [Warlock (The Archfey)](compendium/lists/list-spells-classes-the-archfey.md); [Wizard](compendium/lists/list-spells-classes-wizard.md)

_Source: Player's Handbook p. 276. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)_
