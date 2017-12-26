# Web Analytics
# Business Information Prediction for Yelp Restaurants

This is a python implementation that can mine the reviews of a restaurant and predict the correct values for each entry in the "Business info" section", listed on the right side of the screen. For example: "Good For kids", "Good for large groups" etc.

1.	Run YelpReviewScraper.py file to create folder for each city containing folder for each restaurant HTML file. This will also create text file of reviews for each city.

  HTML Data Link: https://drive.google.com/open?id=1oK57zlwLWlh0ydmh8bwNYpWBvdfnL5AN


2.	Run reviewTransform.py file to merge each city text file to train and test tab separated text file for prediction of business information.

3.	Run MultinomialNB.py file to predict all Business Information using MultinomialNB Classifier and It will generate output file containing all accuracy.

4.	Run RandomForestClassifier.py file to predict all Business Information using RandomForest Classifier and It will generate output file containing all accuracy.

5.	Run linearSVC.py file to predict all Business Information using linearSVC Classifier and It will generate output file containing all accuracy.

6.	Run gridSearch.py file to predict all Business Information using Grid Search Classifier and It will generate output file containing all accuracy.
