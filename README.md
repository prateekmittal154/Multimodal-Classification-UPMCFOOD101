# Multimodal-Classification-UPMCFOOD101
This Repository consists of the various codes written to support the research work on Multimodal Classification using UPMC-FOOD101 as the benchmark

The results obtained so far are as follows ( The metric used is - Accuracy)

| **Model Name & Details**                                    | **Fusion Technique used**                | **Number of Epochs** | **Training Data** | **Testing Data** |
|-------------------------------------------------------------|------------------------------------------|----------------------|-------------------|------------------|
| BERT - LSTM                                                 | -                                        | 10                   | 92.8%             | 78.6%            |
| VGG16                                                       | -                                        | 10                   | 80.2%             | 71.24%           |
| BERT-LSTM + VGG16                                           | Stacking Late Fusion                    | 10                   | 91%               | 90.2%            |
| Inception v3                                                | -                                        | 10                   |                   |                  |
| BERT-LSTM + Inception v3  (original)                        | Stacking Early Fusion                    | 10                   | 81.2%             | 79.6%            |
| VGG16 with two dense layers                                 | -                                        | 10                   |                   |                  |
| BERT-LSTM + VGG16 with two dense layers                     | Stacking Late Fusion                    | 10                   | 92.26%            | 91.44%            |
| Inception v4                                                |                                          | 10                   | 51.7%             | 52.07%           |
| BERT-LSTM + Inception v4                                    | Stacking Lateion                    | 10                   | 92.26%            | 91.6%            |
| BERT+LSTM with extra dense layers                           |                                          | 10                   |                   |                  |
| BERT-LSTM with extra dense layers + VGG16                   | stacking Late fusion                    | 10                   |                   |                  |
| BERT-LSTM with extra dense layers + VGG16 with dense layers | Stacking Late fusion                    | 10                   | 67.69%            | 72.25%           |
| Inception v3 with extra dense layers                        |                                          | 10                   |                   |                  |
| BERT-LSTM + Inception v3 with extra dense layers            | stacking Late fusion                    | 10                   |                   |                  |
| Inception v4 with extra dense layers                        |                                          | 10                   |                   |                  |
| BERT-LSTM + Inception v4 with extra dense layers            | stacking Late fusion                    | 10                   |                   |                  |
| BERT+LSTM + Inception v4 with extra dense layers            | stacking with Late fusion + 1 Desne Layer | 10                   |                   |   91.89%               |
