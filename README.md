# crafting-computer-chess

Learn computer chess by building its concepts, algorithms, data structures, and systems from first principles.

Personal research repo. Not a product, not a Stockfish competitor.

## Structure

```text
board/           board representation: arrays/mailbox, 0x88, bitboards, occupancy, attack maps
moves/           move representation and generation: pseudo-legal/legal moves, make/unmake
representation/  notation and identity: FEN, EPD, PGN, SAN, position identity, game/search trees
search/          minimax, negamax, alpha-beta, iterative deepening, move ordering, pruning
evaluation/      material, piece-square tables, mobility, pawn structure, static evaluation
hashing/         Zobrist hashing, transposition tables, repetition detection
engine/          mini-engine: board + moves + evaluation + search + hashing combined
testing/         perft, divide, regression tests, engine-vs-engine testing, SPRT
protocols/       UCI and other engine-to-GUI communication
tablebases/      retrograde analysis, WDL/DTM/DTZ, Syzygy, small educational tablebases
openings/        opening books, opening trees, Polyglot, book formats
learning/        NNUE, reinforcement learning, self-play, Texel tuning, SPSA
performance/     profiling, cache locality, SIMD, multithreading, benchmark methodology
experiments/     isolated, reproducible benchmarks and investigations
```

Each area has its own `README.md` describing its scope. This is the full study map, not a phased or deferred plan — areas are populated as study reaches them.

See `AGENTS.md` for the principles guiding work in this repo.
