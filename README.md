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
  - ```
    {'loss': 0.504382848739624, 'binary_accuracy': 0.7546666860580444, 'precision': 0.7523117661476135, 'recall': 0.7593333125114441}
    ```
- Pearson
  - ```
    {'loss': 0.5367627143859863, 'binary_accuracy': 0.7353333234786987, 'precision_1': 0.7447988986968994, 'recall_1': 0.7160000205039978}
    ```
- Chi-square
  - ```
    {'loss': 0.5034903883934021, 'binary_accuracy': 0.7526666522026062, 'precision_2': 0.7516600489616394, 'recall_2': 0.7546666860580444}
    ```
- ANOVA
  - ```
    {'loss': 0.5044726133346558, 'binary_accuracy': 0.75, 'precision_3': 0.7600554823875427, 'recall_3': 0.7306666374206543}
    ```
> 6/4 16:00

Daisy.

Maximum binary accuracy during validation & test evaluation:

- No selection
  - ```
    {'loss': 0.5344247817993164, 'binary_accuracy': 0.7273333072662354, 'precision': 0.7246376872062683, 'recall': 0.7333333492279053}
    ```
- Pearson
  - ```
    {'loss': 0.5363144874572754, 'binary_accuracy': 0.734333336353302, 'precision_1': 0.7226092219352722, 'recall_1': 0.7606666684150696}
    ```
- Chi-square
  - ```
    {'loss': 0.5361865758895874, 'binary_accuracy': 0.7293333411216736, 'precision_2': 0.7362637519836426, 'recall_2': 0.7146666646003723}
    ```
- ANOVA
  - ```
    {'loss': 0.5361486077308655, 'binary_accuracy': 0.7336666584014893, 'precision_3': 0.7228226065635681, 'recall_3': 0.7580000162124634}
    ```