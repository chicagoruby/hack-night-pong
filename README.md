# Pong

Pong is a classic computer game, similar to table tennis (aka ping pong).

![Pong in action](/images/pong.gif)

## Gameplay

The classic version of Pong is a two player game, in which each player operates a bi-directional paddle on either end of the surface of play, hitting the ball between the players.

The player "hits" a ball off of their paddle and to the other player's side. If the player fails to maneuver his paddle to receive the opponent's hit ball, then the ball hits the wall behind the paddle, and the opposing player scores a point. Balls that bounce off of side walls are still in play.

A better starting point for this would be to consider a single player option, where you have three walls in play and only the wall behind your paddle is off limits.

This challenge is heavily visual. In addition to setting the size of static objects like the ball, field of play and paddles, we also have to make considerations about the actions in the game:

- How do the paddles move?
- How does the ball move? At what angle? Start off simple her, save the heavy math for a stretch goal.
- How does the ball first enter the field of play?
- Does speed change? HINT: It probably doesn't for a 3 hour hack night!
- How do you show continuous play?

## Stretch

Here are some options for how to take your game to the next level:

- Once you have the single player action down, work on your two player game.
- How are you deciding at what angle the ball moves? Could that be more precise?
- Encorporate speed changes
- Add randomly placed bumpers in the field of play
- Reduce the scoring window (more like air hockey vs table tennis)
