# tiny-chess-01-entry

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/KimLyNamHa/tiny-chess-01-entry/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/KimLyNamHa/tiny-chess-01-entry/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of Python: alpha-beta with iterative deepening, PVS, a transposition table, null-move pruning, LMR, killer moves and quiescence over captures and promotions, on a 0x88 board with sunfish piece-square tables, material and bishop-pair eval. A fixed node budget per move (no clock, no randomness), so every trial replays byte-identically.

Forked from [sunfish](https://github.com/thomasahle/sunfish) (`nnue_4k/pst_entry.py`, commit e396948acbd80cdcbad3dccfb07e878fba9df8f4) by Thomas Ahle and contributors, GPL-3.0-only — rewritten on a fast 0x88 board with make/unmake, so it searches far more nodes per move than the 50,000-node house baseline.

`main.py` is the kit's `makefun compress` pack (LZMA) of `src.py`; the readable source is uploaded beside the transcripts at submit time.

---

<sub>Entered on [make.fun](https://make.fun/?ref=qmq06e6v&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
