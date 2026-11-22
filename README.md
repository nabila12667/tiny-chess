# tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/nabila12667/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/nabila12667/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4 KB Python chess engine: 0x88 board, iterative-deepening alpha-beta with a transposition table, killer moves and quiescence search, material plus piece-square-table evaluation with a bishop-pair bonus, and a fixed 220,000-node budget per move — fully deterministic, no clock, no randomness. Practice trials: Elo 1,364 / 1,191 / 1,099, mean 1,218.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
```

## Practice trials

Local 6-game practice trials against the house gauntlet (each trial plays the six weakest anchors):

| Trial | Result | Elo |
|---|---|---|
| trial-0 | 2W / 3D / 1L | 1,364 |
| trial-1 | 1W / 3D / 2L | 1,191 |
| trial-2 | 1W / 2D / 3L | 1,099 |

Mean Elo 1,218 — above the 1,154 practice floor. v3.1 documents the piece-square-table encoding; the engine itself is unchanged from v3.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
