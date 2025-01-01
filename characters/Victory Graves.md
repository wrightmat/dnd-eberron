---
gender: Female
pronouns: she/her
race: Human
occupation: Thief
alignment: Neutral Evil
attitude: Indifferent
languages: Common, Thieves’ Cant, Telepathy
statblock: inline
---
#npc 

Victory "Vic" Graves grew up in a rough orphanage in Sarlona (probably Rhiavhaar) that forced her onto the streets as soon as the young human could feed and dress herself. Her childhood instilled what she considers life’s most valuable lesson: “The weak think someone will save them. The strong think others will fear them. The clever think everyone beneath them. In the end, it’s the ruthless who survive.”

Vic learned to fight as soon as she could lift a blade, and she honed her skills in vicious backroom fighting pits and bloody alleyway brawls. She delights in luring foes into one-on-one duels with her, where her sharp reflexes and precise strikes prove deadly. Vic always carries a powerful rapier forged from sentira known as *mindrazor*.

>[!info] **Mindrazor**
>*Weapon (Rapier), Very Rare (Requires Attunement)*
>
>This rapier was forged using shattered fragments of a powerful psionic crystal and ore from a falling star. You gain a +1 bonus to attack and damage rolls made with this magic weapon.
>This rapier has 3 charges and regains all expended charges daily at dawn. When you hit a creature with an attack roll using this weapon, you can expend 1 charge to attempt to inflict a psionic wound. The target must succeed on a DC 17 Intelligence saving throw or become vulnerable to psychic damage for 1 minute (save ends at end of turn).

### Stat Block

```statblock
source: FM
environment: [Urban]
name: Victory Graves
size: Medium
type: Humanoid
alignment: Neutral Evil
ac: 18
hp: 88
hit_dice: 16d8 + 16
speed: 40 ft.
stats: [16, 22, 12, 14, 13, 13]
saves:
  - DEX: 9
  - INT: 5
skillsaves:
  - Acrobatics: 9
  - Athletics: 6
  - Deception: 4
  - Intimidation: 4
  - Stealth: 9
senses: passive Perception 11
languages: Common, thieves’ cant, telepathy 120 ft.
cr: 5
traits:
  - name: Exploit Opening (3/Day).
    desc: "When Victory makes an attack, she has advantage on the attack roll."
  - name: Mind Link.
    desc: "Victory can communicate telepathically with any ally regardless of distance, provided they are on the same plane of existence."
  - name: Kinetic Buildup.
    desc: "When Victory hits a creature with a melee weapon attack, her speed increases by a cumulative 5 feet and she gains one additional reaction until the start of her next turn."
  - name: Psionic Wound (3/Day).
    desc: "When Victory hits a creature with a Mindrazor attack, she can attempt to inflict a psionic wound (no action required). The target must succeed on a DC 17 Intelligence saving throw or become vulnerable to psychic damage for 1 minute (save ends at end of turn)."
actions:
  - name: Multiattack.
    desc: "Victory makes three Mindrazor attacks and one Cheap Shot attack."
  - name: Mindrazor.
    desc: "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 11 (1d8 + 7) piercing damage."
  - name: Cheap Shot.
    desc: "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 8 (1d4 + 6) bludgeoning damage, and the target must make a DC 17 Dexterity saving throw. On a failed save, Victory can choose for the target to either be knocked prone or gain one of the following conditions until the end of the target’s next turn: blinded, dazed, or deafened."
reactions:
  - name: Shared Condition.
    desc: "When Victory is blinded, charmed, dazed, deafened, frightened, paralyzed, or stunned, she chooses a willing ally within 60 feet of her who doesn’t already have the condition or is immune to it. The chosen creature then gains the condition for the duration, and Victory loses the condition. She can use this reaction even while incapacitated."
```

### References

- Flee, Mortals!, pg. 374
- http://wizzle.tplinkdns.com:38090/index.php/apps/files/files/1651?dir=/TTRPGs/DD5e/DM%20Books&openfile=true
