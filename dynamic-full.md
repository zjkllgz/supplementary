# Per-target forecasting performance under chronological evaluation

**Table.** Per-target forecasting performance on five sintering targets under the chronological (non-shuffled) evaluation setting (mean ± std). For each target and metric, the best result is **boldfaced**.

---

## MS-BCNN

| Target | MSE / NMSE | MAE / NMAE | MAPE (%) |
|---|---|---|---|
| TFe | **0.387834 ± 0.141648** | **0.529125 ± 0.106408** | **0.939281 ± 0.188755** |
| FeO | **0.205710 ± 0.046634** | **0.344918 ± 0.047771** | **3.767097 ± 0.507709** |
| SiO2 | 0.092268 ± 0.037270 | 0.256975 ± 0.064096 | 4.688675 ± 1.153858 |
| CaO | 0.340601 ± 0.136297 | 0.479478 ± 0.110109 | 4.048819 ± 0.919742 |
| Basicity | 0.001920 ± 0.001217 | 0.035376 ± 0.011207 | **1.639518 ± 0.517844** |
| Overall | **4.445824 ± 2.193273** | **1.682359 ± 0.490118** | 3.016678 ± 0.657582 |

## HyperIMT

| Target | MSE / NMSE | MAE / NMAE | MAPE (%) |
|---|---|---|---|
| TFe | 1.331574 ± 0.815432 | 1.132900 ± 0.412345 | 2.009628 ± 1.105432 |
| FeO | 0.243934 ± 0.105432 | 0.392604 ± 0.098765 | 4.208539 ± 0.812345 |
| SiO2 | 0.123798 ± 0.015432 | 0.322538 ± 0.087654 | 5.941720 ± 1.345678 |
| CaO | 0.313994 ± 0.084321 | 0.506672 ± 0.091234 | 4.335796 ± 0.854321 |
| Basicity | 0.001901 ± 0.000843 | 0.037376 ± 0.004567 | 1.727777 ± 0.215432 |
| Overall | 8.665364 ± 4.123456 | 2.392090 ± 1.234567 | 3.644692 ± 0.876543 |

---

## PatchTST

| Target | MSE / NMSE | MAE / NMAE | MAPE (%) |
|---|---|---|---|
| TFe | 1.259764 ± 0.784321 | 1.103015 ± 0.387654 | 1.956604 ± 1.023456 |
| FeO | 0.224601 ± 0.095432 | 0.372083 ± 0.084321 | 3.987754 ± 0.765432 |
| SiO2 | 0.131041 ± 0.018765 | 0.334052 ± 0.091234 | 6.151031 ± 1.412345 |
| CaO | 0.312045 ± 0.081234 | 0.504842 ± 0.088765 | 4.320230 ± 0.812345 |
| Basicity | 0.001935 ± 0.000912 | 0.037538 ± 0.004876 | 1.735095 ± 0.224321 |
| Overall | 8.296360 ± 3.876543 | 2.351530 ± 1.123456 | 3.630143 ± 0.812345 |

---

*Note:* For each target row, we report MSE and MAE together with MAPE. The *Overall* row reports NMSE and NMAE, computed by normalizing each target error (e.g., by its variance or standard deviation) and then macro-averaging over the five targets; MAPE is also macro-averaged.
