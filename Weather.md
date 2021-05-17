# Weather

The weather applies over the entire width of the map, but is prone to change 
between northern and southern sections; there might be a snowstorm up north 
while it's completely dry in the south.

## Aspects

Each turn, roll per row of the [world](Cards/World.md) for: 

### Clouds

Roll for clouds:

Add 1 to the 1D6 roll for every section south of the top one. (0-3)

1. Dark clouds (-1 on rain roll)
1. Grey clouds
1. Fully clouded (+1 on rain roll)
1. Cloudy (+2 on rain roll)
1. Light clouds (+3 on rain roll)
1. Occasional clouds (+4 on rain roll)
1. Occasional tiny cloud (+6 on rain roll)
1. (or more) Straight blue sky (no rain)

### Precipitation

Roll for precipitation:

Add (or subtract) the `+x on rain roll` amount to (or from) the 1D6 roll. 
In case of `no rain`, no need to roll, it's definitely [dry](#dry).

1. (or less) [Snowstorm](#snowstorm)
1. [Hailstorm](#hailstorm)
1. [Snow](#snow)
1. [Hail](#hail)
1. [Heavy rain](#heavy-rain)
1. [Light rain](#light-rain)
1. [Occasional light rain](#occasional-light-rain)
1. [Occasional drops](#occasional-drops)
1. (or more) [Dry](#dry)

## Consequences

Consequences apply to all [characters](Cards/Characters.md) and [enemies](Cards/Enemies.md) 
(and the [world](Cards/World.md) itself) in any section with this weather.

### Snowstorm

Rule changes:
- [Fields produce](Gameplay.md#resource-rate) nothing.
- [Visibility](Gameplay.md#visibility) reduced by 3.
- [Speed](Gameplay.md#speed) reduced by 2.
- [Morale](Gameplay.md#morale) reduced by 1.

### Hailstorm

Rule changes:
- [Fields produce](Gameplay.md#resource-rate) nothing.
- [Visibility](Gameplay.md#visibility) reduced by 2.
- [Speed](Gameplay.md#speed) reduced by 2.
- [Morale](Gameplay.md#morale) reduced by 1.

### Snow

Rule changes:
- [Field production](Gameplay.md#resource-rate) reduced by 2.
- [Visibility](Gameplay.md#visibility) reduced by 1.
- [Speed](Gameplay.md#speed) reduced by 1.
- [Morale](Gameplay.md#morale) reduced by 1 if last turn was hail or snow.

### Hail

Rule changes:
- [Field production](Gameplay.md#resource-rate) reduced by 2.
- [Visibility](Gameplay.md#visibility) reduced by 2.
- [Morale](Gameplay.md#morale) reduced by 1 if last turn was hail or snow.

### Heavy rain

Rule changes:
- [Field production](Gameplay.md#resource-rate) increased by 2.
- [Visibility](Gameplay.md#visibility) reduced by 1.
- [Morale](Gameplay.md#morale) reduced by 1 if last 2 turns were light- or heavy 
  rain.

### Light rain

Rule changes:
- [Field production](Gameplay.md#resource-rate) increased by 1.
- [Morale](Gameplay.md#morale) reduced by 1 if last 2 turns were light- or heavy 
  rain.

### Occasional light rain

Rule changes:
- [Field production](Gameplay.md#resource-rate) increased by 1.

### Occasional drops

Rule changes:
- None!

### Dry

Rule changes:
- [Field production](Gameplay.md#resource-rate) reduced by the amount of 
  previous turns with dry whether.
- [Thirst](Gameplay.md#thirst) increased by 1.
