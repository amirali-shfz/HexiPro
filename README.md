# HexiPro

A fun and exciting way to experience the board game Risk! This multiplayer hexagonal board game is inspired by risk, play and see if you can take over the hexagonal world. [Click here to play version one](https://guarded-springs-60488.herokuapp.com/).

## Here are the rules:

1. In every round, there are two stages. Attack and Scheme.
2. In the attack stage, you attack or move your troops. Simply click on any of your tiles that have more than 1 troop, and you can either move it to an empty tile or click on an enemy tile to attack it.
3. Once you are done attacking, click "END ATTACK". In the Scheme stage, you are scheming against the enemy. You are given X troops to allocate to one of the tiles that you've captured. This number is shown in the top left by "Power". Your Power increases with the more tiles you capture.
4. After you are done allocating troops, click "END TURN" to give control back to your enemy!

## Attacking Mechanism

1. You can only attack an enemy tile that shares a border with the tile you want to attack from.
2. Every tile needs to have at least 1 troop on it, this means that you can only attack from a tile with more than one troop on it.
3. So what happens when you click on a neighboring enemy tile? Well, we want to keep the exact mechanism secret, but the higher your number is than theirs, the higher your chances of victory!
4. You can only remove one of your enemy's troops at a time. So say you are attacking an enemy tile with 3 troops on it. If you win every fight, it will look like: (3) -> (2) -> (1) -> (Yours!)

And that is about it. Go have fun and tell me if you have any questions :)

## Future Improvements

- There currently is no Game Over mechanism. This is in the works and will soon be a part of the game. For now, if one player has no more tiles on the board, then the other player has won.

- Another future improvement is allowing the players to pick their own names and colors.

Thanks for playing!
