---
statblock: inline
---
 #monster 

```statblock
name: Arcane Devourer
size: Large
type: Construct
alignment: Unaligned
ac: 18
hp: 195
hit_dice: 17d10 + 102
speed: 40 ft., climb 20 ft.
stats: [14, 16, 20, 22, 18, 18]
saves:
  - Int: 11
  - Wis: 9
  - Cha: 9
skillsaves:
  - Arcana: 11
  - Perception: 9
damage_resistances: Force, Psychic
senses: Truesight 60 ft., Darkvision 120 ft., Passive Perception 19
languages: Understands all languages but cannot speak
cr: 12
spells:
  - "Innate Spellcasting (Psionics). The arcane devourer’s innate spellcasting ability is Intelligence (spell save DC 19). It can innately cast the following spells, requiring no material components:"
  - At will: Counterspell, Detect Magic, Shield
  - 3/day each: Globe of Invulnerability, Resilient Sphere, Wall of Force
traits:
  - name: Magic Resistance.
    desc: The arcane devourer has Advantage on saving throws against spells and other magical effects.
actions:
  - name: Multiattack.
    desc: "The arcane devourer makes two Void Tendril attacks."
  - name: Void Tendril.
    desc: "Melee Weapon Attack: +10 to hit, reach 15 ft., one target. Hit: 21 (3d8 + 6) force damage. If the target is concentrating on a spell, they make a DC 19 Constitution saving throw or lose concentration."
bonus_actions:
  - name: Antimagic Cone.
    desc: "The arcane devourer emits an antimagic wave in a 150-foot Cone. Until the start of the arcane devourer’s next turn, that area acts as an Antimagic Field spell but does not suppress the arcane devourer’s own abilities."
reactions:
  - name: Arcane Consumption.
    desc: When a creature within 120 feet casts a spell, the arcane devourer can use its reaction to force the caster to make a DC 19 Constitution saving throw. On a failure, the spell fails and is consumed, and the arcane devourer regains hit points equal to twice the spell’s level.
```

### References

- https://www.aonprd.com/MonsterDisplay.aspx?ItemName=Arcanaton
- https://www.dndbeyond.com/monsters/5194923-beholder
- https://mtg.fandom.com/wiki/Eldrazi
