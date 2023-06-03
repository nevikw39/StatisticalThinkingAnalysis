# Statistical Thinking & Analysis
## GEC 111503

> 6/3 23:00

Maximum binary accuracy on validation data set (random sample \(20%\) from train data set):

- `model`
  - 0.7380
- `model_pearson`
  - 0.7166
- `model_chi_square`
  - 0.7368
- `model_anova`
  - 0.7726

> 6/4 02:00

Split data into train, validation, test set.

Maximum binary accuracy during validation & test evaluation:

- No selection
  - \(0.7615\)
  - ```
    {'loss': 0.504382848739624, 'binary_accuracy': 0.7546666860580444, 'precision': 0.7523117661476135, 'recall': 0.7593333125114441}
    ```
- Pearson
  - \(0.7490\)
  - ```
    {'loss': 0.5367627143859863, 'binary_accuracy': 0.7353333234786987, 'precision_1': 0.7447988986968994, 'recall_1': 0.7160000205039978}
    ```
- Chi-square
  - \(0.7645\)
  - ```
    {'loss': 0.5034903883934021, 'binary_accuracy': 0.7526666522026062, 'precision_2': 0.7516600489616394, 'recall_2': 0.7546666860580444}
    ```
- ANOVA
  - \(0.7680\)
  - ```
    {'loss': 0.5044726133346558, 'binary_accuracy': 0.75, 'precision_3': 0.7600554823875427, 'recall_3': 0.7306666374206543}
    ```