# Tiny Chess

A chess engine in under 4 KB of Python for make.fun tiny-chess-01:
0x88 board, alpha-beta with transposition table, killer/history move
ordering, null-move pruning, LMR, quiescence search and a tapered
piece-square evaluation with bishop pair and passed pawns.

It plays the house gauntlet through the env at `MAKEFUN_ENV_URL`,
searching a fixed node budget per move (deterministic, no clock).

Run: `MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py`
