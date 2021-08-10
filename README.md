# Logistic-Regression-on-Donors-Choose-dataset

### Assignment 5: Logistic Regression
#### 1. [Task-1] Logistic Regression(either SGDClassifier with log loss, or LogisticRegression) on these feature sets
- Set 1: categorical, numerical features + project_title(BOW) + preprocessed_eassay (`BOW with bi-grams` with `min_df=10` and `max_features=5000`)
- Set 2: categorical, numerical features + project_title(TFIDF)+ preprocessed_eassay (`TFIDF with bi-grams` with `min_df=10` and `max_features=5000`)
- Set 3: categorical, numerical features + project_title(AVG W2V)+ preprocessed_eassay (AVG W2V)
- Set 4: categorical, numerical features + project_title(TFIDF W2V)+ preprocessed_essay (TFIDF W2V)

#### 2. Hyper paramter tuning (find best hyper parameters corresponding the algorithm that you choose)
- Find the best hyper parameter which will give the maximum AUC value
- Find the best hyper paramter using k-fold cross validation or simple cross validation data
- Use gridsearch cv or randomsearch cv or you can also write your own for loops to do this task of hyperparameter tuning

#### 3. Representation of results
- You need to plot the performance of model both on train data and cross validation data for each hyper parameter.
- Once after you found the best hyper parameter, you need to train your model with it, and find the AUC on test data and plot the ROC curve on both train and test.
- Along with plotting ROC curve, you need to print the confusion matrix with predicted and original labels of test data points. Please visualize your confusion matrices using seaborn heatmaps.

#### 4. [Task-2] Apply Logistic Regression on the below feature set Set 5 by finding the best hyper parameter as suggested in step 2 and step 3.<br/>
Consider these set of features for Set 5 :
- school_state : categorical data
- clean_categories : categorical data
- clean_subcategories : categorical data
- project_grade_category :categorical data
- teacher_prefix : categorical data
- quantity : numerical data
- teacher_number_of_previously_posted_projects : numerical data
- price : numerical data
- sentiment score's of each of the essay : numerical data
- number of words in the title : numerical data
- number of words in the combine essays : numerical data
<br/>And apply the Logistic regression on these features by finding the best hyper paramter as suggested in step 2 and step 3

#### 5. Conclusion
You need to summarize the results at the end of the notebook, summarize it in the table format.
