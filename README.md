# nim
AI that plays the game of Nim using reinforcement learning (Q-Learning)


## Description

In the game Nim, we begin with some number of piles, each with some number of objects. Players take turns: on a player’s turn, the player removes any non-negative number of objects from any one non-empty pile. Whoever removes the last object loses.

The AI uses Q-learning and learns to reward each state/action pair, meaning that for a specific state of the game when the AI performs a specific action it should know if the action is good.  

## Example

```
python play.py
    Playing training game 1
    Playing training game 2
    Playing training game 3
    ...
    Playing training game 9999
    Playing training game 10000
    Done training

    Piles:
    Pile 0: 1
    Pile 1: 3
    Pile 2: 5
    Pile 3: 7

    AI's Turn
    AI chose to take 1 from pile 2.
```