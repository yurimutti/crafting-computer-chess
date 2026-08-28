# experiments

Isolated, reproducible investigations and benchmarks. Experimental code stays here, separate from the canonical educational implementations in the other areas.

Each experiment answers a concrete question. Prefer this shape:

```text
experiments/
└── multipv-cost/
    ├── README.md
    ├── code/
    └── results/
```

Each experiment README covers: question, hypothesis, method, variables, measurements, results, findings, limitations, references.

Possible topics:

- board representation comparisons
- bitboards vs arrays
- move-generation benchmarks
- minimax vs alpha-beta node counts
- move-ordering impact
- transposition-table impact
- evaluation comparisons
- Stockfish depth experiments
- depth vs nodes vs movetime
- MultiPV 1 vs 2 vs 3
- Threads and reproducibility
- Hash size impact
- search stability
- engine configuration comparisons
- benchmark methodology
