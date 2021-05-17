# Battle

Each player has a battle deck, consisting of anywhere between 6 and 12 Battle 
cards, plus a shuffle card.

Battle cards can be added and removed over time (either by the player or by 
external forces) - thus influencing the players' chances in combat.

Each battle card has 3 sections: one for melee attacks, one for ranged attacks
and one for magical attacks.

## Drawable Battle Cards

Most battle cards can be drawn from a shuffled stack at semi-regular intervals 
during the game. The following cards are available:

### Missing all marks
- Melee: miss
- Ranged: miss
- Magic: miss
### Melee hit
- Melee: hit
- Ranged: miss
- Magic: backfire
### Ranged hit
- Melee: miss
- Ranged: hit
- Magic: backfire
### Magic hit
- Melee: backfire
- Ranged: backfire
- Magic: hit
### Critical melee
- Melee: critical
- Ranged: backfire
- Magic: backfire
### Critical ranged
- Melee: backfire
- Ranged: critical
- Magic: backfire
### Critical magic
- Melee: critical backfire
- Ranged: critical backfire
- Magic: critical
### Traditional mastery
- Melee: critical
- Ranged: critical
- Magic: critical backfire
### Bad luck
- Melee: backfire
- Ranged: backfire
- Magic: backfire

## Special Battle Cards

Some cards can only be added as a result of some in-game event, like completing 
a quest or becoming the target of a curse. These cards are:

### Very bad luck
- Melee: critical backfire
- Ranged: critical backfire
- Magic: critical backfire
### Cursed
Lose 5% of remaining HP
- Melee: backfire
- Ranged: backfire
- Magic: backfire
### Doomed
Lose 10% of remaining HP
- Melee: critical backfire
- Ranged: critical backfire
- Magic: critical backfire
### Divine sacrifice
Lose 5% of remaining HP
- Melee: hit
- Ranged: hit
- Magic: hit
### Diabolical sacrifice
Lose 10% of remaining HP
- Melee: critical
- Ranged: critical
- Magic: critical
### Decent hit
- Melee: hit
- Ranged: hit
- Magic: miss
### Blessed
- Melee: hit
- Ranged: hit
- Magic: hit
### Divine guidance
- Melee: critical
- Ranged: critical
- Magic: hit
### Shuffle
Shuffle the battle deck and draw a new card.
Can't be removed from or added to a deck.

## Default Battle Deck

Players start with a battle deck with 6 battle cards and a shuffle. Characters' 
[classes](Characters.md#classes) and [species](Characters.md#species) may modify 
the starting deck; by default, the deck contains the following cards:
- [Critical melee](#critical-melee)
- [Melee hit](#melee-hit)
- [Ranged hit](#ranged-hit)
- [Magic hit](#magic-hit)
- [Missing all marks](#missing-all-marks)
- [Bad luck](#bad-luck)
- [Shuffle](#shuffle)
