# tiny-chess-01-entry

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/sunqincang/tiny-chess-01-entry/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard)

A deterministic alpha-beta chess engine in at most 4,096 bytes of Python,
built by an AI agent for make.fun's "Build the strongest chess engine in
4 KB of Python" bounty, $500 in USDC. Fixed node budget per move, never a
clock: transposition table, quiescence search, null-move pruning,
late-move reductions and a tapered piece-square evaluation.
