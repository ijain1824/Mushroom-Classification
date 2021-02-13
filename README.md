# Mushroom-Classification
This dataset includes descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family Mushroom drawn from The Audubon Society Field Guide to North American Mushrooms (1981). Each species is identified as definitely edible, definitely poisonous, or of unknown edibility and not recommended.

The main task included Classification of mushrooms into edible and non edible.

# Using sklearn library:
Performed preprocessing and found the correlation between various features using sns plots and correlation matrix in pandas.
Applied various classification models including Random Forests, XG Boost, SVM etc to recieve an accuracy of 99.8% through Random Forest classifier.

# Using H2o.ai library:
H2O is a Java-based software for data modeling and general computing. There are many different perceptions of the H2O software, but the primary purpose of H2O is as a distributed (many machines), parallel (many CPUs), in memory (several hundred GBs Xmx) processing engine.
Built model using GBM classifier of h2o library.

AutoML:
H2O’s AutoML can be used for automating the machine learning workflow, which includes automatic training and tuning of many models within a user-specified time-limit. Stacked Ensembles will be automatically trained on collections of individual models to produce highly predictive ensemble models which, in most cases, will be the top performing models in the AutoML Leaderboard.

Used AutoML to built variety of models inlcuding GBM, GLM, Deep Learning and XRT (Extremely Randomized Trees) and the best model obtained was a DRF(Distributed Random Forest- Gave 100% accuracy)

