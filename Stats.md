# Stats

@todo prune stats?

## Character Stats

Character stats can be influenced by many aspects of the game, such as the
[weather](Weather.md), the character's [species](Cards/Characters.md#species),
the [terrain type](Cards/World.md), in-game events, or combinations of those.

### Hunger

- 0 - 20.
- Start at 4.
- Death by starvation at 20.
- Automatically increases by 2 each turn.

### Thirst

- 0 - 20.
- Start at 4.
- Death by dehydration at 20.
- Automatically increases by 2 each turn.
- At 16 or more, lose 1 [health](#health) per turn.

### Fatigue

- 0 - 10
- Start at 0
- At 7 or more, reduce the amount of [actions per turn](Turns.md#actions) by 1.
- At 10, your character falls asleep for the turn.
- Automatically increases by 2 each turn.

### Morale

- 0 - 10.
- Start at 8.
- At 0, sit brooding for 3 turns, then gain 1 morale.
  No actions are possible for the character while they're brooding.
- At 5 or lower, roll a morale check at the start of your turn:
  - If you roll higher than your morale, add a darkness point for the difference.

### Karma

- 0 - 10.
- Start at 6.
- At 10, when drawing a [critical or regular backfire](Cards/Battle.md) for your
  attack, redraw.
- At 9, when drawing a [critical backfire](Cards/Battle.md) for your attack,
  redraw.
- At 5 or lower, roll a karma check at the start of your turn:
    - If you roll higher than your karma, add a darkness point for the difference.

### Darkness

- 0 - 10.
- Start at 0.
- At 10, your character is forever lost to the demons.

### Visibility

- 0 - 6.
- Defaults to 4, unless specified otherwise.
- Determines from how far off enemies and such are sighted.

### Speed

- 0 - 6.
- Defaults to 4, unless specified otherwise.
- Determines how far the character can move each turn.

### Strength

@todo

### Intelligence

@todo

### Health

- 0 - 20.
- Start at 20.
- At 0, your character is dead.

## Section Stats

### Resource Rate
