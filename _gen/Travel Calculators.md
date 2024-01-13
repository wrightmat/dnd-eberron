---
MilesPerHour: 12
SpeedMultiplier: 1
HoursPerDay: 24
TravelDistance: 1200
Environment: grassland
CostPer15Miles: 0.5
PeopleTraveling: 5
PartyLevel: 11-16
EncounterProbability: 18
---
 #generator 


### Travel Time
Updating the calculator below will flow the changes out to any notes that automatically calculate travel distances.

|  |  |  |
| ---- | ---- | ---- |
| **Travel Means:** | `INPUT[inlineSelect(option(3, On Foot), option(6, By Horse), option(7, By Magebred Coach), option(10, By Sailing Ship), option(12, By Elemental Galleon), option(20, By Airship), option(30, By Lightning Rail)):MilesPerHour]` | Max Travel Hours Per Day: `VIEW[{MilesPerHour}>=10 ? 24 : 8]` |
| **Travel Pace:** | `INPUT[inlineSelect(option(1.25, Fast), option(1, Normal), option(0.75, Slow)):SpeedMultiplier]` | `VIEW[{SpeedMultiplier}>1 ? "-5 penalty to passive Wisdom (Perception) scores" : {SpeedMultiplier}<1 ? "Able to use stealth" : ""]` |
| **Travel Hours Per Day:** | `INPUT[number:HoursPerDay]` | `VIEW[{HoursPerDay}>({MilesPerHour}>=10 ? 24 : 8) ? "DC (10 + 1 for each hour past 8) Constitution saving throw at the end of each hour to avoid exhaustion" : ""]` |
| **Miles To Travel:** | `INPUT[number:TravelDistance]` |  |
| **Distance Travelled Per Day:** | `VIEW[round({MilesPerHour}*{HoursPerDay},1)]` miles | Miles Per Hour: `VIEW[{MilesPerHour}*{SpeedMultiplier}]` |
| **Days Travel 🕓:** | `VIEW[round({TravelDistance} / (({MilesPerHour}*{HoursPerDay})*{SpeedMultiplier}),1)]` |  |

### Travel Costs

|  |  |
| ---- | ---- |
| **Travel Means:** | `INPUT[inlineSelect(option(0.4, By Magebred Coach), option(1, By Sailing Ship), option(0.5, By Lightning Rail or Elemental Galleon - Steerage), option(2, By Lightning Rail or Elemental Galleon - Second Class), option(6, By Lightning Rail or Elemental Galleon - First Class), option(5, By Airship - Second Class), option(10, By Airship - First Class)):CostPer15Miles]` |
| **Number of People:** | `INPUT[number:PeopleTraveling]` |
| **Travel Cost 💰:** | `VIEW[round((({TravelDistance} / 15) * {CostPer15Miles} * {PeopleTraveling}), 0)]` sp |
| **Rations Cost 🍖:** | `VIEW[round({TravelDistance} / (({MilesPerHour}*{HoursPerDay})*{SpeedMultiplier}),0) * {PeopleTraveling} * 5]` sp |

### Travel Encounters

|  |  |
| ---- | ---- |
| **Environment**: | `INPUT[inlineSelect(option(arctic, Arctic), option(coastal, Coastal), option(desert, Desert), option(forest, Forest), option(grassland, Grassland), option(hill, Hill), option(mountain, Mountain), option(swamp, Swamp), option(underdark, Underdark), option(underwater, Underwater), option(urban, Urban)):Environment]` |
| **Party Level:** | `INPUT[inlineSelect(option(1-4, 1 to 4), option(5-10, 5 to 10), option(11-16, 11 to 16), option(17-20, 17 to 20)):PartyLevel]` |
| **Travel Situation:** | `INPUT[inlineSelect(option(20, Safe route- low danger environment), option(18, Safe route- higher danger environment), option(15, Mildly dangerous route), option(11, Dangerous route)):EncounterProbability]` |
```dataviewjs
const environment = dv.current().Environment
const partyLevel = dv.current().PartyLevel
const daysTravel = dv.current().TravelDistance / ( ( dv.current().MilesPerHour * dv.current().HoursPerDay ) * dv.current().SpeedMultiplier )
const encounterProbability = dv.current().EncounterProbability
const diceRollerPlugin = app.plugins.getPlugin("obsidian-dice-roller");
var day = 0;
while (day <= daysTravel) {
  const diceRoller20 = await diceRollerPlugin.getRoller("1d20");
  const diceRoll20 = await diceRoller20.roll();
  if (diceRoll20 >= encounterProbability) {
    const diceRoller = await diceRollerPlugin.getRoller("[[Random Encounters#^encounter-" + environment + "-" + partyLevel + "]]");
    const diceRoll = await diceRoller.roll();
    dv.paragraph("**Day " + day + ":** " + diceRoll)
  } else {
    dv.paragraph("Day " + day + ": --")
  }
  day += 1
}
```

### References

* [[Movement]]
* [[Travel and Random Encounters]]
