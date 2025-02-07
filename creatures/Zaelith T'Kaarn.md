---
statblock: inline
---
 #monster 

```statblock
name: Zaelith T'Kaarn
size: Medium
type: Humanoid
subtype: Wizard
alignment: Neutral Evil
ac: 17
hp: 170
hit_dice: 31d8 + 31
speed: 30 ft.
stats: [10, 14, 12, 20, 15, 16]
skillsaves:
  - Arcana: 13
  - Deception: 13
  - History: 9
  - Perception: 6
damage_immunities: Psychic
condition_immunities: Charmed
senses: Passive Perception 16
languages: Abyssal, Celestial, Common, Draconic, Infernal, Sylvan
cr: 14
spells:
  - "As an action, Extus casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 17):"
  - At will: Detect Magic, Detect Thoughts, Disguise Self, Invisibility, Light, Mage Armor (included in AC), Mage Hand, Prestidigitation, Chaos Bolt
  - 2/Day Each: Entropic Damage Field, Frenzied Bolt, Mist of Wonders, Timely Distraction, Undermind Armor, Unruly Item, Wild Trajectory
  - 1/Day Each: Chaotic World, Misfortune, Paragon of Chaos, Uncontrollable Transformation
traits:
  - name: Legendary Resistance (3/Day).
    desc: "If Zaelith fails a saving throw, he can choose to succeed instead."
  - name: Magic Resistance.
    desc: "Zaelith has Advantage on saving throws against spells and other magical effects."
  - name: Oriq Mask. 
    desc: "Zaelith wears an Oriq mask. While wearing the mask, he can't be targeted by any divination magic or perceived through magical scrying sensors and he adds double his proficiency bonus to Charisma (Deception) checks (included above)."
actions:
  - name: Multiattack.
    desc: "Zaelith makes four Arcane Burst attacks."
  - name: Arcane Burst.
    desc: "Melee or Ranged Attack Roll: +9, reach 5 ft. or range 150 ft. Hit: 27 (4d10 + 5) Force damage."
  - name: Chaos Cloud (Recharge 4-6).
    desc: "Zaelith shoots forth a knot of roiling ethereal light that explodes at a point they can see within 60 feet of them. Each creature in a 20-foot-radius sphere centered on that point must succeed on a DC 14 Charisma saving throw or be stunned until the end of its next turn."
bonus_actions:
  - name: Misty Step (3/Day).
    desc: "Zaelith casts Misty Step, using the same spellcasting ability as Spellcasting."
reactions:
  - name: Protective Magic (3/Day).
    desc: "Zaelith casts Counterspell or Shield in response to the spell’s trigger, using the same spellcasting ability as Spellcasting."
```

### References

- https://www.dndbeyond.com/monsters/5194902-archmage
- Deep Magic (Kobold Press): Chaos Magic
