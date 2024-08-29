## Kaggle competition solution
https://www.kaggle.com/competitions/playground-series-s4e8

### Project Goal
Uhe goal of this competition is to predict whether a mushroom is edible or poisonous based on its physical characteristics.

### About the Tabular Playground Series
The goal of the Tabular Playground Series is to provide the Kaggle community with a variety of fairly light-weight challenges that can be used to learn and sharpen skills in different aspects of machine learning and data science. The duration of each competition will generally only last a few weeks, and may have longer or shorter durations depending on the challenge. The challenges will generally use fairly light-weight datasets that are synthetically generated from real-world data, and will provide an opportunity to quickly iterate through various model and feature engineering ideas, create visualizations, etc.

### Evaluation
Submissions are evaluated using the Matthews correlation coefficient (MCC).

### keywords
torch, pytorch, autoencoder, embeddings, tabnet, transformer

### Project methodology
The main goal of this project was to compare the practical effectiveness of "autoencoder net" + "fully connected head" vs "tabnet (with self-supervised training)". TabNet was chosen as the final model.
