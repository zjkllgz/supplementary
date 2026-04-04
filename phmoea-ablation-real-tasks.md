# PHMOEA ablation on the real-world sintering task and water treatment plant task

**Table.** PHMOEA ablation on the real-world sintering task and water treatment plant task (mean ± std across random seeds).

---

## Sintering-task

| Variant | IGD ↓ | HV ↑ | FEs (k) ↓ | Time (h) ↓ |
|---|---:|---:|---:|---:|
| Full (PHMOEA) | 0.0163 ± 0.0026 | 0.986 ± 0.005 | 1.11 ± 1.9 | 52.5 ± 0.4 |
| w/o De-duplication | 0.0175 ± 0.0028 | 0.982 ± 0.006 | 1.12 ± 1.9 | 53.0 ± 0.5 |
| w/o Elitism | 0.0421 ± 0.0055 | 0.854 ± 0.015 | 1.50 ± 0.0 | 70.9 ± 0.0 |
| w/o stage-aware scoring | 0.0171 ± 0.0027 | 0.983 ± 0.005 | 1.14 ± 1.8 | 53.9 ± 0.6 |
| w/o hot/cold partition | 0.0178 ± 0.0031 | 0.981 ± 0.006 | 1.13 ± 2.1 | 53.4 ± 0.5 |
| w/o adaptive refinement | 0.0161 ± 0.0021 | 0.987 ± 0.003 | 1.15 ± 1.7 | 54.4 ± 0.5 |
| w/o early stopping | 0.0160 ± 0.0024 | 0.987 ± 0.004 | 1.50 ± 0.0 | 70.9 ± 0.0 |

---

## Water Treatment Plant-task

| Variant | IGD ↓ | HV ↑ | FEs (k) ↓ | Time (h) ↓ |
|---|---:|---:|---:|---:|
| Full (PHMOEA) | 0.0214 ± 0.0018 | 0.953 ± 0.004 | 1.35 ± 2.4 | 33.8 ± 2.4 |
| w/o De-duplication | 0.0225 ± 0.0022 | 0.948 ± 0.005 | 1.38 ± 2.4 | 34.5 ± 2.7 |
| w/o Elitism | 0.0652 ± 0.0084 | 0.812 ± 0.012 | 2.00 ± 0.0 | 50.0 ± 0.0 |
| w/o stage-aware scoring | 0.0221 ± 0.0020 | 0.950 ± 0.005 | 1.42 ± 2.5 | 35.5 ± 3.1 |
| w/o hot/cold partition | 0.0228 ± 0.0024 | 0.946 ± 0.006 | 1.45 ± 2.6 | 36.3 ± 2.8 |
| w/o adaptive refinement | 0.0210 ± 0.0015 | 0.955 ± 0.003 | 1.48 ± 2.2 | 37.0 ± 1.8 |
| w/o early stopping | 0.0213 ± 0.0017 | 0.954 ± 0.004 | 1.50 ± 0.0 | 38.0 ± 0.0 |
