# MLBas_Romanenko_exam

This is a student project for the PhD course on Applied Machine Learning (Basic) in the University of Bologna.

For this work the "Credit Card Fraud Detection" dataset was chosen:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data

The project is divided in two parts:

1) "Frauds_DataPreparation.ipynb"
   where the dataset was examined and prepared for the future training. The preparation includes checking the distribution of the features and rescailing some of them, clearing from the fake entries and outliers. After all the transformation and cleaning, the resulting sub-set was written into a separete file for the futurre training.
2) "Frauds_ModelsTrain.ipynb"
   where different classification algorithms were tested -- resulting in the choice of the Linear one. Then, the importance of the features was estimated leading to dropping 8 of the less important for the sake of computational resourses economy. The resulting setup (linear model and set of selected features) was then used for the further tests and adjustments of the model configuration. The choice of the main metric for this particular case is discussed.

The project is prepared by a PhD student Gleb Romanenko for the final exam.
