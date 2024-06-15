# Medical Computer Vision Experiments

- [**CheXpert: Chest X-Rays Dataset**](https://stanfordmlgroup.github.io/competitions/chexpert/)
  - exploring dataset as per the labels: [Data Visuals](./CheXpert/1_chexpert-x-rays-dataset-data-visuals.ipynb), [kaggle](https://www.kaggle.com/code/shreydan/chexpert-x-rays-dataset-data-visuals)
  - training a multilabel classifier with Asymmetric loss + masking: [classifier](./CheXpert/2_chexpert-multi-label-classifier.ipynb), [kaggle](https://www.kaggle.com/code/shreydan/chexpert-multi-label-classifier)
  - generating labels for the uncertain samples with test-time augmentation: [TTA labeling](./CheXpert/3_chexpert-tta-labeling.ipynb), [kaggle](https://www.kaggle.com/code/shreydan/chexpert-tta-labeling)
  - retraining a multilabel classifier with Asymmetric loss using original + generated pseudo-labels: [classifier + pseudo-labels](./CheXpert/4_chexpert-classifier-pseudo-labels.ipynb), [kaggle](https://www.kaggle.com/code/shreydan/chexpert-classifier-pseudo-labels)


- [**MRNet: A Knee MRI Dataset**](https://stanfordmlgroup.github.io/competitions/mrnet/)
  - the dataset has all 3 views: sagittal, axial, coronal.
  - TripleMRNet: This implementation is loosely based on their [original implementation](https://journals.plos.org/plosmedicine/article?id=10.1371%2Fjournal.pmed.1002699#sec008) and this [combined triple-model implementation](https://github.com/yashbhalgat/MRNet-Competition/)
  - viewing sagittal samples: [Data Visuals](./MRNet/1_mrnet-sagittal-data_viz.ipynb)
  - training classifier for `abnormal` class: [abnormal classifier](./MRNet/2_triplemrnet-abnormal.ipynb), [kaggle](https://www.kaggle.com/code/shreydan/triplemrnet-abnormal)
  - training classifier for `acl` and `meniscus` class: [acl+meniscus classifier](./MRNet/3_triplemrnet-acl-meniscus.ipynb), [kaggle](https://www.kaggle.com/code/shreydan/triplemrnet-acl-meniscus/)