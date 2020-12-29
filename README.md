# Natural-Language-Processing-Positive-Negative-Reviews
Create a NLP model for classifying the amazon reviews as positive or negative

In this project I created a NLP model to classify the amazon reviews as positive or negative

Procedure followed:

1. Get the data 
2. Store the text and rating
3. Classify the reviews as 'POSITIVE' and 'NEGATIVE' based on the rating
4. Use vectorizer to transform the text to vector
5. Create a training and test set
6. Fit the training set to the classifier

Initial Observation:
1. After fitting the classifier it was observed that the model was biased towards POSITIVE reviews,after some digging through the data it was seen that there were more
POSITIVE reviews than NEGATIVE ,so the data set was imbalanced.
2. Now the dataset needs to balanced
3. In order to do this I took as many as positive reviews as the negative reviews.

Then I used GridSearchCV method to find out best parameters of the model.

Final Step:
1. Saved the model
2. Load the model
