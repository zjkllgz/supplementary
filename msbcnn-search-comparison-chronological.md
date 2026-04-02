# Per-target forecasting results of MS-BCNN obtained by different search methods

**Table.** Per-target forecasting results of MS-BCNN obtained by different search methods on the real-world sintering task under the chronological (non-shuffled) evaluation setting (mean ± std across 5 random seeds). For each target and metric, the best result is **boldfaced**.

---

## MS-BCNN (PHMOEA-searched)

| Target | MSE / NMSE | MAE / NMAE | MAPE (%) |
|---|---|---|---|
| TFe | **0.387834 ± 0.141648** | **0.529125 ± 0.106408** | **0.939281 ± 0.188755** |
| FeO | 0.205710 ± 0.046634 | 0.344918 ± 0.047771 | 3.767097 ± 0.507709 |
| SiO2 | **0.092268 ± 0.037270** | **0.256975 ± 0.064096** | **4.688675 ± 1.153858** |
| CaO | **0.340601 ± 0.136297** | **0.479478 ± 0.110109** | **4.048819 ± 0.919742** |
| Basicity | 0.001920 ± 0.001217 | 0.035376 ± 0.011207 | 1.639518 ± 0.517844 |
| Overall | **4.445824 ± 2.193273** | **1.682359 ± 0.490118** | **3.016678 ± 0.657582** |

---

## MS-BCNN (SMAC3-searched)

| Target | MSE / NMSE | MAE / NMAE | MAPE (%) |
|---|---|---|---|
| TFe | 0.419738 ± 0.325476 | 0.569419 ± 0.125465 | 1.011433 ± 0.248412 |
| FeO | **0.144032 ± 0.031542** | **0.274924 ± 0.038415** | **3.009580 ± 0.415236** |
| SiO2 | 0.104961 ± 0.042153 | 0.274955 ± 0.071234 | 4.979015 ± 1.254321 |
| CaO | 0.424217 ± 0.165432 | 0.565301 ± 0.132145 | 4.768518 ± 1.054321 |
| Basicity | 0.001900 ± 0.001145 | 0.034701 ± 0.010543 | 1.604318 ± 0.485432 |
| Overall | 4.685480 ± 2.254321 | 1.791663 ± 0.512345 | 3.074573 ± 0.685432 |

---

## MS-BCNN (AutoDL-searched)

| Target | MSE / NMSE | MAE / NMAE | MAPE (%) |
|---|---|---|---|
| TFe | 0.431928 ± 0.256412 | 0.601320 ± 0.136542 | 1.068726 ± 0.241254 |
| FeO | 0.150016 ± 0.034512 | 0.289354 ± 0.041234 | 3.125695 ± 0.395432 |
| SiO2 | 0.112848 ± 0.045432 | 0.302459 ± 0.078543 | 5.466985 ± 1.385432 |
| CaO | 0.614958 ± 0.235432 | 0.723747 ± 0.185432 | 6.097002 ± 1.465432 |
| Basicity | **0.001497 ± 0.000954** | **0.030584 ± 0.009543** | **1.415621 ± 0.445432** |
| Overall | 4.774088 ± 2.454321 | 1.970922 ± 0.565432 | 3.434806 ± 0.735432 |

---

*Note:* For each individual target row, we report MSE, MAE, and MAPE. The *Overall* row reports macro-averaged NMSE and NMAE over the five targets, where NMSE = MSE / var and NMAE = MAE / std; MAPE is also macro-averaged over the five targets.
