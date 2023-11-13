# Yandex ML Cup 2023: Genre Predictions, 26th place

Music genre predictions contest solution based on audio-embedding data.

## Prerequisites
- Install `track-embeddings/` folder from Kaggle - [link](https://www.kaggle.com/datasets/sharthz23/yandex-cup-2023-recsys/data?select=track_embeddings)
- Install requirements - `pip install -r requirements.txt`

Same Solution on Kaggle: 🔗 https://www.kaggle.com/code/djacon/yandex-ml-cup-2023-26th-place-solution

### Parameters
```
Metric: Average Precision (AP)
Optimizer: AdamW
Learning Rate: 3e-4
Batch Size: 64
Number of Folds: 10
Number of Epochs: 14
Model Params: 4.7M
```

### Results
```
Public Score: 0.2762
Private Score: 0.2759
```