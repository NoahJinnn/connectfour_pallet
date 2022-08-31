# Balances Module

The Connect-four module provides functionality for connect four gameplay logic.

## Overview

The Connect-four module provides functions for:

- Challenge and accept challenge to/from different users.
- Create game board.
- Play with turns.
- Find random game.


## Dispatchable Functions

- `find_game` - Find random game  within a certain range of point diff.
- `cancel_queue` - Remove account from matching queue.
- `challenge` - Challenge other users.
- `resp_challenge` - Response to the challenge.
- `cancel_challenge` - Remove the old challenge.
- `play_turn` - Play the game in turns.
## Results

The following examples show how the game occurs using [this](https://polkadot.js.org/apps).

### Challenge process

Start challenge

![](./assets/challenge.png)

Respond to challenge

![](/assets/respond.png)

Both users join the same board game

![](/assets/c-result.png)

![](/assets/c-result2.png)

Cancel old challenge

![](/assets/cancel-challenge.png)

### Game play in turns

Alice's turn

![](./assets/alice-turn.png)

Bob's turn

![](./assets/bob-turn.png)

Game state between turns

![](./assets/game-state.png)

Alice makes wrong turn

![](./assets/wrong-turn.png)

Game's result

![](/assets/game-result.png)

### Find random game

Alice finds

![](/assets/alice-find.png)

Bob finds

![](/assets/bob-find.png)

Not match condition so Alice and Bob can't start a new game

![](/assets/fail-find.png)

Charlie finds

![](/assets/charlie-find.png)

Match condition and start a new game

![](/assets/success-find.png)