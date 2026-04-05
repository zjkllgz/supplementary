# PHMOEA ablation on the real-world sintering task and water treatment plant task

**Table.** PHMOEA ablation on the real-world sintering task and water treatment plant task (mean ± std across random seeds). 

---

## Sintering-task

| Variant | IGD ↓ | HV ↑ | FEs ↓ | Time (h) ↓ |
|---|---:|---:|---:|---:|
| Full (PHMOEA) | 0.0163 ± 0.0026 | 0.986 ± 0.005 | **1113.6 ± 1.9** | **17.6 ± 0.5** |
| w/o De-duplication | 0.0175 ± 0.0028 | 0.982 ± 0.006 | 1128.3 ± 1.9 | 17.7 ± 0.7 |
| w/o Elitism | 0.0421 ± 0.0055 | 0.854 ± 0.015 | 1500.0 ± 0.0 | 23.7 ± 1.8 |
| w/o stage-aware scoring | 0.0171 ± 0.0027 | 0.983 ± 0.005 | 1147.4 ± 1.8 | 18.0 ± 1.2 |
| w/o hot/cold partition | 0.0178 ± 0.0031 | 0.981 ± 0.006 | 1232.5 ± 2.1 | 19.9 ± 0.8 |
| w/o adaptive refinement | 0.0182 ± 0.0035 | 0.977 ± 0.003 | 1356.4 ± 2.3 | 21.3 ± 1.2 |
| w/o early stopping | **0.0160 ± 0.0024** | **0.987 ± 0.004** | 1500.0 ± 0.0 | 23.7 ± 1.7 |

---

## Water Treatment Plant-task

| Variant | IGD ↓ | HV ↑ | FEs ↓ | Time (h) ↓ |
|---|---:|---:|---:|---:|
| Full (PHMOEA) | **0.0214 ± 0.0018** | 0.953 ± 0.004 | **1252.1 ± 2.4** | **11.5 ± 0.3** |
| w/o De-duplication | 0.0225 ± 0.0022 | 0.948 ± 0.005 | 1284.6 ± 2.4 | 11.8 ± 0.3 |
| w/o Elitism | 0.0652 ± 0.0084 | 0.812 ± 0.012 | 1500.0 ± 0.0 | 14.8 ± 0.8 |
| w/o stage-aware scoring | 0.0221 ± 0.0020 | 0.950 ± 0.005 | 1320.4 ± 2.5 | 12.1 ± 0.3 |
| w/o hot/cold partition | 0.0228 ± 0.0024 | 0.946 ± 0.004 | 1351.8 ± 2.6 | 12.4 ± 0.3 |
| w/o adaptive refinement | 0.0232 ± 0.0021 | 0.945 ± 0.003 | 1382.3 ± 2.2 | 12.6 ± 0.3 |
| w/o early stopping | **0.0214 ± 0.0017** | **0.954 ± 0.004** | 1500.0 ± 0.0 | 14.9 ± 0.9 |
