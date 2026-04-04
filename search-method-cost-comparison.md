# Comparison of different search methods in model complexity and computational cost

**Table.** Comparison of different search methods in terms of model complexity and computational cost on the sintering task under the chronological evaluation setting (mean ± std).

| Search Method | Avg. Params (K) ↓ | Avg. Search Time (h) ↓ | Selected Params (K) ↓ | Selected Inference Time (s) ↓ |
|---|---:|---:|---:|---:|
| PHMOEA-searched | **142.8 ± 0.84** | **17.6 ± 0.2** | **52.7** | **42.5 ± 0.4** |
| SMAC3-searched | 433.5 ± 12.1 | 53.8 ± 2.7 | 310.0 | 121.1 ± 10.8 |
| AutoDL-searched | 490.4 ± 16.8 | 56.4 ± 4.1 | 71.8 | 71.7 ± 2.7 |

*Note:* “Selected” refers to the single final model used for testing in each run, i.e., the best model for single-objective search methods and the most suitable representative solution chosen from the Pareto set for PHMOEA.
