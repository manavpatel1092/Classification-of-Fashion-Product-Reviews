# Classification-of-Fashion-Product-Reviews

### Overview of the dataset:

The dataset contains the online shopping reviews of women fashion. It consists of Title, Review, Recommendation. The Recommendation value are 0 & 1 which corresponds to Not recommended and recommended respectively. 

### Task:

We performed text analytics to eventually build a machine learning classification model using Logistic Regression to know if a person would recommended the product or not based on his/her review. 
- Firstly we assessed the model accuracy and feature selection using the headline and/or the review. We then regularized each model to see any difference. 
- For feature tuning we used different combinations of TfidVectorizer/CountVectorizer, Stop words, Normalization, n-gram, min_df, and max_df techniques to select the best features.
- For Model Tuning, we imposed L1 and L2 penalties to see any difference. 
- The final model precision of 91% was achieved.

### Following questions were answered through the course of this task:

2.1 Using TfidfVectorizer instead of CountVectorizer. Does it change the score? Does it change the important coefficients?

2.2 Does using a Normalizer with CountVectorizer change the outcome?

2.3 Do the standard English stop-words help? Why / why not?

2.4 Limit the vocabulary using min_df or max_df. How to these impact the number of features, and how do they impact the scores?

3.1 Using your current best model, try changing from unigrams to n-grams of varying length. What provides the best performance?

3.2 Using character n-grams. Visualize the coefficients. Can we learn something from this?

3.3 Investigate how min_df and the use of stop-words changes the number of features when using word n-grams, and how they change the score.

4.1 Are there any other obvious features to try, or combinations to try out?
