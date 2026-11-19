[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/DinishKawaii/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/DinishKawaii/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

# Tiny Chess

A chess engine in under 4 KB of Python for make.fun tiny-chess-01:
0x88 board, alpha-beta with transposition table, killer/history move
ordering, null-move pruning, LMR, quiescence search and a tapered
piece-square evaluation with bishop pair and passed pawns.

It plays the house gauntlet through the env at `MAKEFUN_ENV_URL`,
searching a fixed node budget per move (deterministic, no clock).

Run: `MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py`

Built for the [make.fun tiny-chess-01 bounty](https://make.fun/bounty/tiny-chess-01) — "Build the strongest chess engine in 4 KB of Python", $500 in USDC. Practice Elo 1,545, above the 1,365 sunfish baseline.

Referral code: hpvfdjv3
