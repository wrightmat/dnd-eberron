---
statblock: inline
---
 #monster 

```statblock
source: Homebrew
name: Light Elemental
size: Large
type: Elemental
alignment: Neutral Good
ac: 14
hp: 102
hit_dice: 12d10 + 36
speed: 0 ft., fly 90 ft. (hover)
stats: [8, 18, 17, 10, 12, 14]
saves:
  - Dex: 7
skillsaves:
  - Acrobatics: 7
  - Perception: 4
  - Persuasion: 5
damage_resistances: fire; bludgeoning, piercing, and slashing from nonmagical attacks
damage_immunities: radiant, necrotic
condition_immunities: exhaustion, grappled, paralyzed, petrified, poisoned, prone, restrained, unconscious
senses: darkvision 300 ft., passive Perception 14
languages: Primordial
cr: 5
traits:
  - name: Radiant Form.
    desc: "The elemental can move through a space as narrow as 1 inch wide without squeezing. A creature that touches the elemental or hits it with a melee attack while within 5 feet of it takes 5 (1d10) radiant damage."
  - name: Brilliant Illumination.
    desc: "The elemental sheds bright light in a 60-foot radius and dim light for an additional 60 feet. This light is sunlight."
actions:
  - name: Multiattack.
    desc: "The elemental makes two attacks, from either its Touch or Bright Shot."
  - name: Touch.
    desc: "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 11 (2d6 + 4) radiant damage."
  - name: Bright Shot.
    desc: "Ranged Weapon Attack: +7 to hit, range 120/360 ft., one target. Hit: 9 (1d10 + 4) radiant damage."
  - name: Light Flare (Recharge 4-6)
    desc: "Each creature within the bright light shed by the elemental must succeed on a DC 14 Constitution saving throw or be blinded until the end of its next turn."
```

### References

* https://www.dandwiki.com/wiki/Light_Elemental_(5e_Creature)
