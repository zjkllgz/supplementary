# Comparison of different search methods in model complexity and computational cost

**Table.** Comparison of different search methods in terms of model complexity and computational cost on the sintering and water treatment plant tasks under the chronological evaluation setting (mean ± std).

---

## Sintering

| Search Method | Avg. Params (K) ↓ | Avg. Search Time (h) ↓ | Selected Params (K) ↓ | Selected Inference Time (s) ↓ |
|---|---:|---:|---:|---:|
| PHMOEA-searched | **142.8 ± 0.84** | **17.6 ± 0.5** | **42.7** | **52.5 ± 0.4** |
| SMAC3-searched | 433.5 ± 12.1 | 53.8 ± 2.7 | 310.0 | 121.1 ± 10.8 |
| AutoDL-searched | 490.4 ± 16.8 | 56.4 ± 4.1 | 71.8 | 71.7 ± 2.7 |

---

## Water Treatment Plant

| Search Method | Avg. Params (K) ↓ | Avg. Search Time (h) ↓ | Selected Params (K) ↓ | Selected Inference Time (s) ↓ |
|---|---:|---:|---:|---:|
| PHMOEA-searched | **115.2 ± 0.95** | **11.5 ± 0.3** | **35.4** | **34.2 ± 0.3** |
| SMAC3-searched | 360.5 ± 10.5 | 35.2 ± 1.8 | 255.0 | 78.5 ± 6.5 |
| AutoDL-searched | 410.2 ± 15.4 | 37.5 ± 2.5 | 58.5 | 46.5 ± 1.8 |

---

*Note:* “Selected” refers to the single final model used for testing in each run, i.e., the best model for single-objective search methods and the most suitable representative solution chosen from the Pareto set for PHMOEA.
