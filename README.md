# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/SUNJIAN709/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/SUNJIAN709/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4 KB Python chess engine for make.fun's tiny-chess-01 bounty. Alpha-beta search with iterative deepening, a transposition table, history heuristics, null move pruning and late move reductions. Search uses a fixed node budget, never a wall clock.

## Run it

```sh
python3.13 -u main.py
```

The engine talks to the competition env at `$MAKEFUN_ENV_URL` (`POST /game`, `/move`, `/resign`) and plays UCI moves.

---

<sub>Entered on [make.fun](https://make.fun/?ref=y65az621&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
