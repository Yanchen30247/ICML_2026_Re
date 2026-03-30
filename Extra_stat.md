**Table 1. TUSZ dataset: statistical comparison using NeuroCanvas (19Ch CNS, F1 = 0.5022 ± 0.0119) as the reference model.**

| Comparator          | F1 (mean ± sd) | ΔF1    | t     | df   | one-sided p | Conclusion              |
|---------------------|---------------:|-------:|------:|-----:|------------:|-------------------------|
| GRU                 | 0.2845 ± 0.0273 | +0.2177 | 12.66 | 2.73 | 0.0008      | Significantly better    |
| CNN-LSTM            | 0.2128 ± 0.0295 | +0.2894 | 15.76 | 2.63 | 0.0006      | Significantly better    |
| Transformer         | 0.3702 ± 0.0141 | +0.1320 | 12.39 | 3.89 | 0.0001      | Significantly better    |
| ResNet-LSTM         | 0.3910 ± 0.0359 | +0.1112 | 5.09  | 2.43 | 0.0119      | Significantly better    |
| DCRNN               | 0.4074 ± 0.0546 | +0.0948 | 2.94  | 2.19 | 0.0444      | Significantly better    |
| REST                | 0.3643 ± 0.0150 | +0.1379 | 12.47 | 3.80 | 0.0002      | Significantly better    |
| Time-LLM            | 0.2686 ± 0.0517 | +0.2336 | 7.63  | 2.21 | 0.0063      | Significantly better    |
| Our Model (19Ch DV) | 0.4438 ± 0.0137 | +0.0584 | 5.57  | 3.92 | 0.0027      | Significantly better    |
| Our Model (8Ch CNS) | 0.4505 ± 0.0142 | +0.0517 | 4.83  | 3.88 | 0.0046      | Significantly better    |
| Our Model (4Ch CNS) | 0.4059 ± 0.0125 | +0.0963 | 9.66  | 3.99 | 0.0003      | Significantly better    |
| Our Model (2Ch CNS) | 0.3686 ± 0.0104 | +0.1336 | 14.64 | 3.93 | 0.0001      | Significantly better    |

**Table 2. CHB-MIT dataset: statistical comparison using NeuroCanvas (16Ch CNS, F1 = 0.5146 ± 0.0059) as the reference model.**

| Comparator          | F1 (mean ± sd) | ΔF1    | t     | df   | one-sided p | Conclusion                |
|---------------------|---------------:|-------:|------:|-----:|------------:|---------------------------|
| GRU                 | 0.2951 ± 0.0501 | +0.2195 | 7.54  | 2.06 | 0.0079      | Significantly better      |
| CNN-LSTM            | 0.3742 ± 0.0450 | +0.1404 | 5.36  | 2.07 | 0.0154      | Significantly better      |
| Transformer         | 0.3318 ± 0.0151 | +0.1828 | 19.53 | 2.60 | 0.0003      | Significantly better      |
| ResNet-LSTM         | 0.3342 ± 0.0051 | +0.1804 | 40.07 | 3.92 | <0.0001     | Significantly better      |
| DCRNN               | 0.4564 ± 0.0080 | +0.0582 | 10.14 | 3.68 | 0.0004      | Significantly better      |
| REST                | 0.2608 ± 0.0471 | +0.2538 | 9.26  | 2.06 | 0.0052      | Significantly better      |
| Time-LLM            | 0.1555 ± 0.0040 | +0.3591 | 87.26 | 3.52 | <0.0001     | Significantly better      |
| Our Model (16Ch DV) | 0.4692 ± 0.0059 | +0.0454 | 9.42  | 4.00 | 0.0004      | Significantly better      |
| Our Model (8Ch CNS) | 0.5089 ± 0.0092 | +0.0057 | 0.90  | 3.41 | 0.2128      | Not significant           |
| Our Model (4Ch CNS) | 0.5351 ± 0.0092 | -0.0205 | -3.25 | 3.41 | 0.9802      | Not better than comparator |
| Our Model (2Ch CNS) | 0.3905 ± 0.0123 | +0.1241 | 15.76 | 2.87 | 0.0004      | Significantly better      |
