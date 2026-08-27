# crafting-computer-chess

Learn computer chess by building its concepts, algorithms, data structures, and systems from first principles.

Personal research repo. Not a product, not a Stockfish competitor.

## Structure

```
engine/           educational chess engine development, evaluation, UCI, engine architecture
board/            board representations, move generation, bitboards, related structures
search/           minimax, negamax, alpha-beta, iterative deepening, pruning, search techniques
representation/   FEN, EPD, PGN, SAN, position identity, move trees, related representations
tablebases/       retrograde analysis, WDL, DTM, DTZ, small tablebase implementations
experiments/      isolated benchmarks and investigations (e.g. Stockfish depth, MultiPV, nodes, Threads, reproducibility)
```

New structure is added only when a real study needs it.

See `AGENTS.md` for the principles guiding work in this repo.
