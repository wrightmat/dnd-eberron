---
statblock: inline
---
 #monster 

```statblock
name: Malakar Draksang
size: Medium
type: Humanoid
subtype: Blood Mage
alignment: Neutral Evil
ac: 17
hp: 152
hit_dice: 16d8 + 90
speed: 30 ft.
stats: [11, 14, 20, 16, 12, 20]
saves:
  - CON: 10
  - INT: 8
  - WIS: 6
  - CHA: 10
skillsaves:
  - Deception: 15
  - Persuasion: 15
  - Survival: 6
damage_resistances: Necrotic, Bludgeoning, Piercing, and Slashing from magical and nonmagical attacks, Damage from Spells
damage_immunities: Psychic
condition_immunities: Charmed, Exhaustion, Frightened
senses: Passive Perception 11
languages: Abyssal, Celestial, Common, Draconic, Infernal, Sylvan
cr: 16
spells:
  - "As an action, Extus casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 17):"
  - At will: Detect Magic, Detect Thoughts, Disguise Self, Invisibility, Light, Mage Armor (included in AC), Mage Hand, Prestidigitation, Sapping Sting (level 11)
  - 2/Day Each: Magnify Gravity, Immovable Object, Gravity Sinkhole, Pulse Wave
  - 1/Day Each: Gravity Fissure, Dark Star, Ravenous Void, Time Ravage, Reality Break
traits:
  - name: Blood Aegis.
    desc: "Malakar's AC includes his Constitution modifier while he isn't wearing armor or wielding a shield (included above)."
  - name: Legendary Resistance (3/Day).
    desc: "If Malakar fails a saving throw, he can choose to succeed instead."
  - name: Magic Resistance.
    desc: "Malakar has Advantage on saving throws against spells and other magical effects."
  - name: Oriq Mask. 
    desc: "Malakar wears an Oriq mask. While wearing the mask, he can't be targeted by any divination magic or perceived through magical scrying sensors and he adds double his proficiency bonus to Charisma (Deception) checks (included above)."
  - name: Sanguine Sense.
    desc: "While Malakar isn't blinded he can see any creature that isn't an Undead or a Construct within 60 feet of himself, even thought total cover, heavily obscured areas, invisibility, or any other phenomena that would prevent sight."
actions:
  - name: Multiattack.
    desc: "Malakar makes two Blood Lash attacks."
  - name: Blood Lash.
    desc: "Melee Spell Attack: +10 to hit, reach 15ft., one target. Hit: 27 (4d10+5) necrotic damage. If the target is a creature it cannot regain hit points until the start of Malakar's next turn."
  - name: Blood Boil (Recharge 4-6).
    desc: "Malakar chooses a point within 150 feet of himself, and a 20-foot radius sphere centered on that point fills with a burst of searing, blood-red mist. Each creature of Malakar's choice that he can see in that area must make a DC 18 Constitution saving throw. On a failed save, a creature takes 44 (8d10) necrotic damage and is ncapacitated until the end of its next turn. On a success, a creature takes half as much damage and isn’t incapacitated. A creature dies if reduced to 0 hit points by this necrotic damage."
bonus_actions:
  - name: Misty Step (3/Day).
    desc: "Malakar casts Misty Step, using the same spellcasting ability as Spellcasting."
reactions:
  - name: Summon Blood Avatar.
    desc: "Upon falling below 70 HP, Malakar takes all of his lost blood and uses it to summon the Blood Avatar. He loses half of his remaining hit points as he uses it as a component in the summoning. The Blood Avatar considers Malakar and any other creatures to be enemies and DMs are encouraged to randomly select its targets. Should Malakar live until his next turn he should cast etherealness and attempt to flee."
```

### References

- https://www.dndbeyond.com/monsters/5194902-archmage
- https://dnd5e.wikidot.com/spells:dunamancy
