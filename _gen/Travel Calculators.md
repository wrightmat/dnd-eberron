---
MilesPerHour: 30
SpeedMultiplier: 1
HoursPerDay: 24
TravelDistance: 1200
Environment: grassland_xge
CostPer15Miles: 6
PeopleTraveling: 5
---
 #generator 

Updating the calculator below will flow the changes out to any notes that automatically calculate travel distances. You need to refresh this note in order to see calculated changes. 

### Travel Time
|  |  |  |
| ---- | ---- | ---- |
| **Travel Means:** | `INPUT[inlineSelect(option(3, On Foot), option(6, By Horse), option(7, By Magebred Coach), option(10, By Sailing Ship), option(12, By Elemental Galleon), option(20, By Airship), option(30, By Lightning Rail)):MilesPerHour]` | Max Travel Hours Per Day: `VIEW[{MilesPerHour}>=10 ? 24 : 8]` |
| **Travel Pace:** | `INPUT[inlineSelect(option(1.25, Fast), option(1, Normal), option(0.75, Slow)):SpeedMultiplier]` | `VIEW[{SpeedMultiplier}>1 ? "-5 penalty to passive Wisdom (Perception) scores" : {SpeedMultiplier}<1 ? "Able to use stealth" : ""]` |
| **Environment:** | `INPUT[inlineSelect(option(arctic_xge, Arctic), option(coastal_xge, Coastal), option(desert_xge, Desert), option(forest_xge, Forest), option(grassland_xge, Grassland), option(hill_xge, Hill), option(mountain_xge, Mountain), option(open%20water_gos, Open Water), option(swamp_xge, Swamp), option(underdark_xge, Underdark), option(underwater_xge, Underwater), option(urban_xge, Urban)):Environment]` |  |
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


### References

* [[Movement]]
* [[Travel and Random Encounters]]
