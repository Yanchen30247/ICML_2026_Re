| Hyperparameter | GRU | CNN-LSTM | ResNet-LSTM | Transformer | DCRNN | REST | Time-LLM |
|---|---|---|---|---|---|---|---|
| Epochs | 3 | 10 | 5 | 10 | 100 (early stop) | 100 | 3 |
| Batch size | 256 | 256 | 256 | 256 | 32 | 256 | 8 |
| Learning rate | 1e-4 | 1e-4 | 1e-4 | 1e-3 | 1e-4 | 5e-4 | 1e-4 |
| Weight decay | — | — | — | — | 5e-4 | — | — |
| Dropout | 0.3 | 0.1 | — | 0.1 | — | — | — |
| Optimizer | Adam | Adam | Adam | Adam | Adam | Adam | Adam |
| LR scheduler | — | — | — | — | CosineAnnealingLR | MultiStepLR | One Cycle LR |
| Hidden size | 128 | 128 | 128 | d_model=128 | rnn_units=64 | 32 | 128 |
| Num layers | 2 | 3 (LSTM) | 1 (LSTM) | 2 | 2 | 2 (GraphConv) | 22 |
| Loss function | BCE | BCE | BCE | BCE (pos_weight) | BCE | MSE | BCE |
