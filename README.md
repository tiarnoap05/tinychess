# tinychess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/tiarnoap05/tinychess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/tiarnoap05/tinychess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 3,996 bytes of Python: 0x88 board, negamax with alpha-beta, transposition table, killer moves, late-move reductions and quiescence, searching a fixed 100,000-node budget per move. The source is packed with lzma and unpacked at startup. Practice Elo about 1,580 against the kit's house engines, well above the 1,154 floor.

## Run it

The harness sets `MAKEFUN_ENV_URL` and runs the engine; it plays every game through the env API.

```sh
python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=310ssgcx&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
