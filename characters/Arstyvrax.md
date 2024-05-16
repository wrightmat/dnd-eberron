---
gender: Male
race: Dragon
subrace: Gem (Obsidian)
occupation: Tribe Leader, Necromancer
alignment: Chaotic Neutral
attitude: Hostile
languages: Abyssal, Common, Draconic
image: "![https://i.redd.it/62qpj1yvywgb1.jpg|300](https://i.redd.it/62qpj1yvywgb1.jpg)"
statblock: inline
---
 #npc #monster [[Draconic Factions]]


> [!infobox]
> # `=this.file.name`
> `=this.image`
> ###### Basic Information
> |  |  |
> | ---- | ---- |
> | **Gender** | `=this.gender` |
> | **Race** | `=this.race` |
> | **Subrace** | `=this.subrace` |
> | **Occupation** | `=this.occupation` |
> | **Alignment** | `=this.alignment` |
> | **Attitude** | `=this.attitude` |
> | **Languages** | `=this.languages` |
> ###### Comments
> `=this.comments`


>"I am predictable only in my unpredictability."

The practice of necromancy is forbidden among the dragons of Argonnessen, but Arstyvrax is one of this land’s foremost practitioners of the dark art. He is the  leader of the Shadowmasters — a cabal of a dozen necromancer dragons who share lore and maintain secret libraries scattered across the Vast.

Like most Argonnessen dragons, the Shadowmasters share a steadfast enmity for the Undying Court of Aerenal. Unlike their so-called elders in the Conclave, however, these dragon necromancers believe that understanding the power of The Shadow is the only way to ultimately prevail against the Aereni and their undying lords. What not even the other Shadowmasters suspect is that Arstyvrax has a very different purpose to his studies. He is secretly a vampiric dragon who has ties to the Blood of Vol, and seeks to advance his power even further by taking on the Sovereign Archetype of the Loredrake and ascending to The Shadow.

Arstyvrax joined the ranks of the undead some two hundred years past, becoming the first and only Obsidian Gem Dragon (with all of his followers being Topaz Gem Dragons). Already an initiate into the necromantic arts, he was doing fieldwork in Xen’drik (in the Obsidian City) when he fell to a vampiric wyrm’s assault. That foul undead was the servant of a Blood of Vol high priest operating secretly out of Stormreach. In his tortured mental state, Arstyvrax quickly latched onto the teachings of the cult as a means to accept and justify his horrid transformation.

#### Loredrake

Magic flows through every dragon’s blood. The loredrake devotes their life to harnessing this power and understanding the mysteries of magic. The most accomplished priests of the Dragon Gods and students of the draconic Prophecy are typically loredrakes, and it is the dragons of this path that uncovered the greatest mysteries of arcane magic. Most dragons have great respect for loredrakes, but not all loredrakes are noble creatures. Darkness abides in magic along with light, and a loredrake must decide whether he answers the call of the Shadow.
**Sovereigns**: Aureon, The Shadow.

### Stat Block

```statblock
image: https://i.redd.it/62qpj1yvywgb1.jpg
name: Arstyvrax
size: Gargantuan
type: Dragon
subtype: (Gem)
alignment: Chaotic Neutral
ac: 20
hp: 280
hit_dice: 17d20 + 102
speed: 40 ft., fly 80 ft., swim 40 ft.
stats: [23, 12, 23, 20, 19, 20]
saves:
  - DEX: 7
  - CON: 12
  - WIS: 10
  - CHA: 11
skillsaves:
  - Intimidation: 17
  - Perception: 16
  - Stealth: 7
damage_resistances: Cold, Necrotic
senses: Blindsight 60 ft., Darkvision 120 ft., Passive Perception 26
languages: Common, Draconic, Telepathy 120 ft.
cr: 20
spells:
  - "(Psionics) The dragon casts one of the following spells, requiring no spell components and using Intelligence as the spellcasting ability (spell save DC 19):"
  - 1/day each: antilife shell, bane, control water, create or destroy water
traits:
  - name: Amphibious.
    desc: "The dragon can breathe both air and water."
  - name: Fabricate (1/Day).
    desc: "The dragon can cast fabricate, requiring no spell components and using Intelligence as the spellcasting ability."
  - name: Legendary Resistance (3/Day).
    desc: "If the dragon fails a saving throw, it can choose to succeed instead."
  - name: Vampire Weaknesses.
    desc: "The dragon has the following flaws: - Forbiddance. The dragon can’t enter a residence without an invitation from one of the occupants. - Stake to the Heart. If a piercing weapon made of wood is driven into the dragon’s heart while the dragon is incapacitated in its lair, the dragon is paralyzed until the stake is removed. - Sunlight Hypersensitivity. The dragon takes 20 radiant damage when it starts its turn in sunlight. While in sunlight, it has disadvantage on attack rolls and ability checks."
actions:
  - name: Multiattack.
    desc: "The dragon makes one Bite attack and two Claw attacks."
  - name: Bite.
    desc: "Melee Weapon Attack: +12 to hit, reach 15 ft., one target. Hit: 17 (2d10 + 6) piercing damage plus 10 (3d6) necrotic damage. The target’s hit point maximum is reduced by an amount equal to the necrotic damage taken, and the dragon regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0. A humanoid slain in this way and then buried in the ground rises the following night as a vampire spawn under the dragon’s control."
  - name: Charm.
    desc: "The dragon targets one humanoid it can see within 30 feet of it. If the target can see the dragon, the target must succeed on a DC 17 Wisdom saving throw against this magic or be charmed by the dragon. The charmed target regards the dragon as a trusted friend to be heeded and protected. Although the target isn’t under the dragon’s control, it takes the dragon’s requests or actions in the most favorable way it can, and it is a willing target for the dragon’s bite attack. Each time the dragon or the dragon’s companions do anything harmful to the target, it can repeat the saving throw, ending the effect on itself on a success. Otherwise, the effect lasts 24 hours or until the dragon is destroyed, is on a different plane of existence than the target, or takes a bonus action to end the effect."
  - name: Claw.
    desc: "Melee Weapon Attack: +12 to hit, reach 10 ft., one target. Hit: 13 (2d6 + 6) slashing damage."
  - name: Desiccating Breath (Recharge 5–6).
    desc: "The dragon exhales yellowish necrotic energy in a 90-foot cone. Each creature in that area must make a DC 20 Constitution saving throw. On a failed save, the creature takes 49 (14d6) necrotic damage and is weakened until the end of its next turn. A weakened creature has disadvantage on Strength-based ability checks and Strength saving throws, and the creature’s weapon attacks that rely on Strength deal half damage. On a successful save, the creature takes half as much damage and isn’t weakened."
legendary_actions:
  - name: Claw.
    desc: "The dragon makes one Claw attack."
  - name: Psionics (Costs 2 Actions).
    desc: "The dragon uses Psychic Step or Spellcasting."
  - name: Essential Reduction (Costs 3 Actions).
    desc: "The dragon targets a creature or an object not being worn or carried that it can see within 60 feet of it. The target must succeed on a DC 19 Constitution saving throw or take 40 (9d8) necrotic damage. If this damage reduces the target to 0 hit points, it crumbles to dust."
bonus_actions:
  - name: Change Shape.
    desc: "The dragon magically transforms into any creature that is Medium or Small, while retaining its game statistics (other than its size). This transformation ends if the dragon is reduced to 0 hit points or uses a bonus action to end it."
  - name: Psychic Step.
    desc: "The dragon magically teleports to an unoccupied space it can see within 60 feet of it."
```

**Legendary Actions**. The dragon can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature’s turn. The dragon regains spent legendary actions at the start of its turn.

Arstyvrax is the one and only Obsidian Gem Dragon, whose followers are all Topaz Gem Dragons. Arstyvrax is an Ancient Topaz Dragon with additional Vampire abilities (and weaknesses).

### References

* https://kanka.io/en-US/campaign/6529/characters/99065
* https://forgottenrealms.fandom.com/wiki/Topaz_dragon
* Dragons of Eberron, pg 31 (Sovereign Archetypes section)
* https://www.dndbeyond.com/monsters/2059698-ancient-topaz-dragon
* https://www.dndbeyond.com/monsters/17043-vampire
