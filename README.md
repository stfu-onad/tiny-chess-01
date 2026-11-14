# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/stfu-onad/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/stfu-onad/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A deterministic chess engine — negamax search with alpha-beta pruning, quiescence (with check evasions), killer moves and piece-square tables — packed into a single Python file under 4 KB. It plays the make.fun house gauntlet over HTTP, searching a fixed 100,000 nodes per move, never a clock.

## Run it

```sh
MAKEFUN_ENV_URL=<env url> python3 main.py
```

---
<sub>Entered on [make.fun](https://make.fun/?ref=hwzvnj8a&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
