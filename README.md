# Cloudxlab_ML_CapstoneProject

This is my solution to the kaggle project "Problematic Internet Use" by Child Mind Institute (located here: https://www.kaggle.com/competitions/child-mind-institute-problematic-internet-use).

I have split my work into ten notebooks (plus more in my earlier, more exploratory attempts which I have not uploaded to this repository).

They are as follows:
1. Data Exploration - exploring the train data to determine the best features to keep and what cleaning is necessary
2. Feature Imputation - testing different approaches to imputing missing features. Compared the result of an XGBoost model on the test set
3. XGBoost - optimising XGBoost model trained on the labelled data
4. LightGBM - optimising LightGBM model trained on the labelled data
5. DNN and DNN 2 - optimising DNN model trained on the labelled data. Split into two notebooks as there were many different things to try, e.g., implementing a custom QWK loss function which in the end did not yield results
6. SVR - optimising SVR model trained on the labelled data
7. Random Forest - optimising RandomForestRegressor model trained on the labelled data. Did not pursue this in the ensemble as results were not strong and were unlikely to help ensemble due to similarity with gradient-boosted model approaches
8. Model aggregation - finding the best combination of the above four models trained on the labelled data
9. Feature imputation - an extra attempt, imputing pseudolabels for the unlabelled data and retraining. However, it seems that the model was not good enough for the imputed pseudolabels to be helpful

I have also included my spreadsheet where I kept track of how some of my different approaches improved (or didn't) over time. Currently a few details are missing and they may be updated.
