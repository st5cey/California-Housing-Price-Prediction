# California-Housing-Price-Prediction
This is my second project in my learning process. I used the California Housing dataset to predict house prices based on various factors like neighborhood income, house age, and location.

What I Did in This Project

I followed a professional data science workflow to see how different models perform:

Data Setup: Loaded the dataset using pandas and prepared it for training.
Simple Baseline: I started by predicting price using only one feature (Median Income) to see the simplest possible relationship.
Model Comparison: I trained and compared two different types of models:
1. Linear Regression: A model that looks for a "straight line" relationship.
2. Random Forest: A more complex model that uses many "decision trees" to find patterns.
Evaluation: I used Mean Absolute Error (MAE) to measure how far off my predictions were on average.
Basic testing: I created "fake" houses (one rich, one poor) to make sure the model's logic made sense in the real world.
Feature Importance: I visualized which data points (like income vs house age) the model found most important.

What I Learned

The Power of More Data: Adding more features (like location and house age) dropped my error from 0.63 down to 0.33.
Model Selection Matters: I learned that for this specific data, the Random Forest (81% accuracy) was much better than the Linear Regression.
Visualizing helps: Plotting the "Actual vs. Predicted" values made it much easier to see where the model was struggling (specifically at the higher price points).
Feature Drivers: I discovered that Median Income is by far the most important factor in predicting house prices in this dataset.

Technologies Used

Python
Pandas (Data manipulation)
Matplotlib (Visualization)
Scikit-Learn (Machine Learning models)

Results

Linear Regression MAE: 0.53
Random Forest MAE: 0.33
Final Model Accuracy: ~81%
