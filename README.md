# Project Summary
In this project, we followed these key steps:

**Data Cleaning and Preprocessing**: We began by cleaning and preprocessing the dataset, ensuring that it was free of missing data, duplicates, and other quality issues. This step is essential to prepare the data for analysis and modeling.

**Feature Engineering for Classification**: To prepare the dataset for machine learning models, we performed feature engineering. This involved creating new features and transforming existing ones to better capture underlying data patterns.

**Feature Engineering on Price/Sqft**: Specifically, we focused on the "Price/Sqft" feature, where we conducted operations such as:

<br>

- Normalizing the Latitude and Longitude features using Min-Max normalization.
- Creating a new feature called "Price/Sqft."
- Custom binning of the "Price per Sqft" to classify data into distinct categories.
Classifier Training: We trained several classifiers, including k-Nearest Neighbors (kNN), Gaussian Naive Bayes (NB), and Gaussian Bayes, to classify data into Price/Sqft categories. For each classifier, we reported both training and test accuracies.

**Additional Feature Engineering**: Beyond Price/Sqft, we performed additional feature engineering. This included combining features, such as Bedrooms and Bathrooms, and converting the Homeowners Association (HOA) feature into a categorical variable (0 or 1). We also applied Min-Max normalization to various other property-related features to enhance the quality of our features for modeling.

**Property Price Prediction**: We leveraged the prepared dataset to predict property prices. To accomplish this, we opted for a Multivariate Linear Regression model. The dataset was divided into a training set (90%) and a test set (10%), with 4462 samples in the training set and 495 samples in the test set.

This comprehensive approach aimed to enhance the dataset's suitability for modeling and, ultimately, improve our property price predictions.