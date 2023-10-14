**Email_spam detection using Machine Learning**

This project focuses on email spam detection using machine learning techniques. It begins by encoding the target variable, where 'ham' and 'spam' labels are transformed into numerical values for analysis. A pie chart is created to visualize the distribution of spam and non-spam emails in the dataset.

The project then prepares the data for modeling by splitting it into training and testing sets, with 80% for training and 20% for testing. Text data (email messages) is transformed into numerical features using Count Vectorization, a technique to convert text data into a format suitable for machine learning algorithms.

A logistic regression model is employed for classification. The model is trained on the training data and evaluated on both the training and testing sets using accuracy as a performance metric. The project calculates and prints the accuracy scores to assess the model's ability to correctly classify emails as spam or not. Higher accuracy scores indicate the model's effectiveness in email spam detection.
