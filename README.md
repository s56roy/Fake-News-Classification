# Fake-News-Classification

## Usage

1. Preprocessing is done in both the python notebook.
2. Notebook - "Classical ML.ipynb" explored Multinomial Naive Bayes, Passive Aggressive Classifier, Xtreme Gradient Boost and Ensemble.
3. Notebook - "SVM and NN using BERTTokenizer classification.ipynb" explored Neural network and SVM. It also explored the class_imbalance issue to check how it affects the model performance.
4. Detailed exploratory analysis is done on "Classical ML.ipynb".
5. A cleaned_balanced_dataset.csv is generated


The extracted features are fed into different classifiers. The following classififers have been used Naive-bayes, SVM with rbf kernel, Stochastic gradient descent, Passive Aggressive Classifier, Ensemble classifiers and 2 layer Neural Network. Each of the extracted features were used in all of the classifiers. Once fitting the model, we compared the f1 score and checked the confusion matrix. We have performed parameter tuning by implementing GridSearchCV methods on these candidate models and chosen best performing parameters for these classifier. Finally selected model was used for fake news detection with the probability of truth. 
