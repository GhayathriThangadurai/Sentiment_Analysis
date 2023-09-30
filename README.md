# Sentiment_Analysis
  To build a prediction model to predict whether a reviews on the restaurant is positive or negative.

# End users of this Project
  * Restaurant Owners & Managers - They can use the sentiment analysis to understand how customers perceive their restaurant.
  * Customers - Potential diners can use this analysis to make informed decisions about whether to visit a particular restaurant based on the overall sentiment of reviews.
  * Investors - Sentiment analysis can help marketing teams tailor their campaigns based on the Sentiment trends & creating  targeted advertisements.
  * Marketers & Advertisers - Investors in the Restaurant industry can use  sentiment analysis to gauge the public perception of a Restaurant chain or brand before making investment decisions.
  * Government Agencies - Health and safety departments can potentially use sentiment analysis to monitor public perception of hygiene and food safety in different restaurants.

# Steps to build a Prediction Model
   1. Import all the neccesary libraries - Numpy, Pandas, NLTK
   2. Import the Dataset - Dataset consists of 1000 reviews of the Particular Restaurant.
   3. Explore the Dataset - Find whether any Missing values or Outliers presents. If any of them occurs try to remove them before feeding it to the model.
   4. Visualize the Dataset - Since our Dataset is Qualitative we can Visualize it with Word cloud which gives the words with different font sizes representing the frequency of it occurs.
   6. Data Pre-Processing - In this Step we will try to remove all the stop words which is not needed for prediction. This can be done using nltk package which comes with inbuilt stop words.
   7. Feature Extraction - Use CountVectorizer or Tfidfvectorizer
   8. Model Building - Since it is a prediction model we want to use Classification Algorithms.
   9. Model Evaluation - Evaluate the metrics of the model using accuracy score, Confusion matrix, etc...
   10. Model prediction - Use the model to predict new set of Reviews.
       
I tried Different classification algorithms like Random Forest Classifier, Support vector Classifier , MultinomialNB , Linear and Logistic Regression But I got Higgest accuracy for Random Forest Classifier with 77%.

# Conclusion 
![image](https://github.com/GhayathriThangadurai/Sentiment_Analysis/assets/141329267/a6e4f13e-16d8-4ee7-a677-cba7f12c981d)

