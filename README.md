# Medical Computer Vision Experiments

- [**CheXpert: Chest X-Rays Dataset**](https://stanfordmlgroup.github.io/competitions/chexpert/)
  - exploring dataset as per the labels: [Data Visuals](./CheXpert/1_chexpert-x-rays-dataset-data-visuals.ipynb), [kaggle](https://www.kaggle.com/code/shreydan/chexpert-x-rays-dataset-data-visuals)
  - training a multilabel classifier with Asymmetric loss + masking: [classifier](./CheXpert/2_chexpert-multi-label-classifier.ipynb), [kaggle](https://www.kaggle.com/code/shreydan/chexpert-multi-label-classifier)
  - generating labels for the uncertain samples with test-time augmentation: [TTA labeling](./CheXpert/3_chexpert-tta-labeling.ipynb), [kaggle](https://www.kaggle.com/code/shreydan/chexpert-tta-labeling)
  - retraining a multilabel classifier with Asymmetric loss using original + generated pseudo-labels: [classifier + pseudo-labels](./CheXpert/4_chexpert-classifier-pseudo-labels.ipynb), [kaggle](https://www.kaggle.com/code/shreydan/chexpert-classifier-pseudo-labels)