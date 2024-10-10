---
gender: Male
pronouns: he/him
race: Dwarf
occupation: Thief
alignment: Neutral Evil
attitude: 
languages: Common, Dwarvish, Thieves’ Cant, Telepathy
---
#npc 

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

>Thieves? No. Thieves dream of doing one big, easy job. If they pull it off, they go into hiding and retire. We are not thieves. We’re architects

Though Jutkarr Flintfingers is a devotee of Kol Korran, the Sovereign venerated by thieves and assassins, he doesn’t consider himself a scoundrel. In fact, the grandfatherly dwarf actively dislikes most thieves, calling them lazy cheats and cocky liars. Jutkarr instead considers himself a 'problem solver' and believes that any true follower of Kol Korran is the same. To him, there’s little difference between solving the daily word puzzle in the city broadsheet and 'solving' a guarded mansion, a warded treasure vault, or the social complexities of a street gang war. Each is merely a pleasant distraction and chance to keep his wits sharp.

>[!info] **Amethyst Die**
>*Wondrous Item, Rare (Requires Attunement)*
>
>This gaming die is carved from a fragment of powerful psionic crystal and resonates with a remnant of its power. This die has 3 charges and regains all expended charges daily at dawn. When you make an ability check, attack roll, or saving throw, you can expend 1 charge to roll a d6 and add the number rolled to the d20 roll. Immediately after the ability check, attack roll, or saving throw is resolved, you take psychic damage equal to twice the number you rolled on the d6

### Stat Block

```statblock
source: FM
environment: [Urban]
name: Jutkarr Flintfingers
size: Medium
type: Humanoid
subtype: (Dwarf)
alignment: Neutral Evil
ac: 16
hp: 91
hit_dice: 14d8 + 28
speed: 25 ft.
stats: [13, 15, 14, 22, 16, 7]
saves:
  - CON: 5
  - INT: 9
skillsaves:
  - History: 9
  - Investigation: 9
  - Perception: 6
  - Religion: 9
damage_resistances: Poison, Psychic
senses: darkvision 60 ft., passive Perception 16
languages: Common, Dwarvish, Thieves’ Cant, Telepathy 120 ft.
cr: 5
traits:
  - name: Amethyst Die (3/Day).
    desc: "When Jutkarr makes an ability check, saving throw, or attack roll, he can roll a d6 and add the number rolled to the number rolled on the d20 roll. He then takes psychic damage equal to twice the number rolled on the d6."
  - name: Mind Link.
    desc: "Jutkarr can communicate telepathically with any ally regardless of distance, provided they are on the same plane of existence."
  - name: Poison Resistant.
    desc: "Jutkarr has advantage on saving throws he makes to avoid or end the poisoned condition on himself."
actions:
  - name: Multiattack.
    desc: "Jutkarr makes two Deserved Transfer attacks."
  - name: Deserved Transfer.
    desc: "Melee or Ranged Spell Attack: +9 to hit, reach 5 ft. or range 30 ft., one creature. Hit: 13 (2d6 + 6) psychic damage, and one creature Jutkarr can see within 30 feet of him gains temporary hit points equal to half the damage dealt."
  - name: Psionic Resilience (2/Day).
    desc: "Jutkarr touches a willing creature and gives them immunity to one of the following conditions for 1 hour: blinded, charmed, dazed, deafened, frightened, paralyzed, petrified, poisoned, or stunned. Additionally, if the target suffers from the chosen condition, that condition is suppressed for 1 hour"
reactions:
  - name: Shared Condition.
    desc: "When Jutkarr is blinded, charmed, dazed, deafened, frightened, paralyzed, or stunned, he chooses a willing ally within 60 feet of him who doesn’t already have the condition or is immune to it. The chosen creature then gains the condition for the duration, and Jutkarr loses the condition. He can use this reaction even while incapacitated."
```

### References

- Flee, Morals!, pg. 376