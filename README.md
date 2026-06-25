# Assignment-17.1
Berkeley Assignment

This assignment focused on how four different algorithms performed. These four include K-nearest Neighbors, Logistic Regression, Decision Tree, and Support Vector Machine. We worked with a real bank marketing dataset that followed the CRISP-DM methodology. The goal of this assignment was to help a bank improve the efficiency of its telemarketing campaigns for its long-term deposit subscriptions. Using the client's data, we built classifiers that predicted whether a client would subscribe to a term deposit, so the bank could focus on clients most likely to subscribe and reduce wasted calls. 

KEY FINDINGS:
- 11.3 percent of the clients actually subscribed.
- The models were trained on the bank client features
- The data was 70 percent training, 30 percent testing
- The baseline found was about 88.7 percent accuracy, which any model needed to beat.
- The four classifiers were fit with their default settings and were then compared on training time and accuracy.
- Models were improved by switching the metric from accuracy to F1 and adding balanced class weights.
- After reweighing and focusing on F1 score for the subscriber class, the Decision Tree was found to perform the best with an F1 of .266
- Accuracy was the wrong metric
- Raising F1 score from zero to .26 by by forcing the models to pay attention to the minority.
- Bank client features on their own are weak predictors with a best F1 of about .27
