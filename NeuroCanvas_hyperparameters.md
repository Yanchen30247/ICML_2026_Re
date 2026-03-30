| Hyperparameter | Value |
| --- | --- |
| Frozen components | LLM backbone |
| Trainable components | Vision tower, cross-modal merger, classification head |
| Vision tower learning rate | 6×10⁻⁶ |
| Merger learning rate | 2×10⁻⁵ |
| Base model learning rate | 3×10⁻⁵ |
| Classification head learning rate | 4×10⁻⁵ |
| Weight decay | 0.02 |
| Max gradient norm | 1.0 |
| Effective batch size | 16 (4 per device × 4 gradient accumulation steps) |
| LR scheduler | Cosine with warmup ratio 0.05 |
| Training epochs | 1 |
| Precision | bf16 |
| Random seed | 42/430/229 |
