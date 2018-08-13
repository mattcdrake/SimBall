# SimBall

## Goal

This project will be a baseball simulator that allows the player to really get
into the weeds as far as pitch selection, batting approach, and play strategy
is concerned.

## Systems

### Player Stats System

TODO

### Pitching System

Input to the pitching system will be a data structure (undecided at the time
of this writing) containing the player's intended pitch. Variables that the
player will be able to specify are:

- Pitch location
- Pitch type
- Speed
- Break

The system will take this data structure of intended pitch and do probabilistic
modeling to generate an outcome and delivered pitch. The deviation from intended
pitch will eventually depend on the stats of the pitcher, but the player stats
system has not been implemented yet.

The pitching system's output (the delivered pitch) will then be used as input
for the batting system which will run more probabilistic modeling based on
player stats to determine whether or not the ball is hit. The game system will
take over from there.

### Batting System

TODO

### Game System

TODO
