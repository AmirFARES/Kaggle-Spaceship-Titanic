# Spaceship Titanic: Predicting Alternate Dimension Transportation 🚀

![Project Image](https://github.com/AmirFARES/Kaggle-Spaceship-Titanic/blob/main/imgs/spaceship.jpg)

## Introduction 🌟

Welcome to my Data Science and Machine Learning portfolio! This repository houses my work on the Kaggle Spaceship Titanic competition. Here, I tackle a cosmic mystery by predicting which passengers were transported to an alternate dimension during the Spaceship Titanic's collision with a spacetime anomaly.

[**Link to my Submission Notebook**](https://www.kaggle.com/code/amirfares/spaceship-titanic-weighted-ensemble)

**Key Insights & Results**:

- One of the most critical factors in predicting passenger transportation was the "CryoSleep" feature, showing a strong correlation of over 0.4. Passengers who opted for cryosleep were more likely to be transported to an alternate dimension.

- Through rigorous analysis and modeling, I achieved a commendable score of 0.80, securing a top 28% ranking among 2062 teams. My model's predictions played a vital role in the rescue mission's success.

## About the Challenge 🌐

The Spaceship Titanic competition tasks us with solving a cosmic mystery. By leveraging data science skills, we aim to predict the fate of passengers who encountered a spacetime anomaly during their voyage.

[**Challenge Link**](https://www.kaggle.com/competitions/spaceship-titanic)

### Challenge Details 📝

- **Goal**: Classify passengers as transported or not transported to an alternate dimension.
- **Datasets**: The competition provides a training dataset with personal records and a test dataset for predictions.
- **Evaluation**: Submissions are evaluated based on classification accuracy.

## Project Files 📂

Key files related to this project:

- [**train.csv**](./data/train.csv) - Training dataset with personal records and ground truth labels.
- [**test.csv**](./data/test.csv) - Test dataset for predictions.
- [**sample_submission.csv**](./data/sample_submission.csv) - Sample submission file with the required format.
- [**My Notebook**](./spaceship-titanic-weighted-ensemble.ipynb) or [**My Kaggle Notebook**](https://www.kaggle.com/code/amirfares/spaceship-titanic-weighted-ensemble) - My notebook with code and analysis.

## My Approach 🚀

1. **Reading Datasets**: I began by loading the provided datasets, both the training and test data.

2. **Checking Class Distribution**: To understand the balance between transported and non-transported passengers, I examined the distribution of classes in the training dataset.

3. **Handling Missing Values**: I addressed missing data in the dataset, ensuring that no valuable information was lost.

4. **Making the Correlation Heatmap**: I created a correlation heatmap to visualize relationships between different features, highlighting the strong correlation between "CryoSleep" and passenger transportation.

<img src="https://github.com/AmirFARES/Kaggle-Spaceship-Titanic/blob/main/imgs/correlationHeatmap.png" alt="Line Chart" width="700" height="437">

5. **Feature Engineering**: To improve model performance, I engineered new features. For example, I extracted additional information from the "Cabin" column, breaking it down into "Deck," "Num," and "Side" components.

6. **One-Hot Encoding**: I prepared the data for modeling by performing one-hot encoding, a necessary step for many machine learning models.

7. **Handling Missing Data for Test**: Given the constraints of the test data, where rows could not be removed, I implemented a specific strategy to handle missing values.

8. **Extracting (X, y)**: I separated the feature matrix (X) and the target variable (y) from the training dataset, ensuring that the data was ready for model training.

9. **Playing with the Models**: In this phase, I experimented with multiple machine learning models, including but not limited to:
   - RandomForestClassifier
   - DNN (Deep Neural Network)
   - LogisticRegression
   - XGBoost
   - LightGBM
   - CatBoostClassifier
   - AdaBoost
   - KNN (K-Nearest Neighbors)
   - DecisionTreeClassifier

   I performed tuning and tweaks on these models to optimize their performance.

10. **Ensemble Modeling**: To further enhance accuracy, I selected the top-performing models (the best six performers) and created a simple weighted ensemble. This ensemble played a significant role in achieving the impressive accuracy score.

11. **Making Predictions**: Finally, I used the ensemble model to make predictions on the test data and formatted the results according to the competition's requirements. The predictions can be found in the [**result.csv**](./result.csv).


For detailed implementation and analysis, please refer to [**My Notebook**](./spaceship-titanic-weighted-ensemble.ipynb) or [**My Kaggle Notebook**](https://www.kaggle.com/code/amirfares/spaceship-titanic-weighted-ensemble).

## Connect with Me 📫

I'm open to collaboration and eager to learn from the data science community. You can connect with me on [LinkedIn](https://www.linkedin.com/in/amir-f) or find more of my projects on [GitHub](https://github.com/AmirFARES).

## Acknowledgments 🙏

I want to express my gratitude to Kaggle for hosting this challenging competition. Saving passengers from alternate dimensions is no small feat!

Thank you for visiting my portfolio, and I look forward to sharing more data science projects in the future! 🚀✨

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/amir-f)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-green)](https://github.com/AmirFARES)
