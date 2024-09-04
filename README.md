# PL-Match-Predictor
This is a simple classifier which is trained on four years worth of data from each Premier League match. 
It takes match data as input & predicts whether or not the home team will win the macth, lose it or draw.

The data was pulled from [this Kaggle page](https://www.kaggle.com/datasets/mhmdkardosha/premier-league-matches/data).

The project contains the following models trained on the said data:
  - Random forest
  - Decision tree

Additionally, different metric scores of both the models are compared with each other.
The metrics chosen are:
  - Training accuracy
  - Testing accuracy
  - Macro averages of
      - precision score
      - recall score
      - f1 score
  - Weighted averages of
      - precision score
      - recall score
      - f1 score
