# Credit Card Fraud Detection

This project focuses on detecting credit card fraud using machine learning techniques. The dataset used contains transactions made by credit cards in September 2013 by European cardholders. The dataset is highly imbalanced, as it contains a vast majority of genuine transactions and a small proportion of fraudulent transactions.

## Dataset

The dataset used in this project is the Credit Card Fraud Detection dataset, obtained from Kaggle. It contains 31 features, including time, amount, and anonymized features (V1 to V28), along with a target variable 'Class' indicating whether the transaction is genuine (0) or fraudulent (1).

## Data Preprocessing

- Checked for missing values.
- Normalized the numerical features using StandardScaler.
- Handled class imbalance by oversampling the minority class using SVMSMOTE (Support Vector Machine Synthetic Minority Over-sampling Technique).

## Model Building

- Split the dataset into training and testing sets.
- Trained a Logistic Regression model on the resampled dataset.

## Evaluation

- Evaluated the model's performance using classification metrics such as precision, recall, and F1-score.
- Plotted a confusion matrix to visualize the model's performance.

## Additional Visualizations

- Visualized the distribution of genuine and fraudulent transactions before and after SVMSMOTE oversampling.
- Plotted the counts of genuine and fraudulent transactions after SVMSMOTE to show the balance achieved.

## Results

- The model achieved high accuracy, precision, recall, and F1-score for both genuine and fraudulent transactions.
- The confusion matrix shows that the model effectively detected both genuine and fraudulent transactions.

## Conclusion

- This project demonstrates the effectiveness of machine learning techniques in detecting credit card fraud, even with highly imbalanced datasets.
- SVMSMOTE oversampling helped balance the classes, leading to improved model performance in detecting fraudulent transactions.
- Further optimization and fine-tuning of models could potentially enhance detection accuracy.
