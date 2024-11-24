Credit Card Fraud Detection
This project detects fraudulent credit card transactions using a dataset of real transaction records. It employs logistic regression after addressing class imbalance with under-sampling.

Steps
Data Preprocessing:

Removed duplicates and verified no missing values.
Balanced the dataset using NearMiss under-sampling.
Model Training:

Split data (80% train, 20% test).
Trained a logistic regression model on the balanced dataset.
Evaluation:

Used accuracy score, confusion matrix, and classification report to assess performance.
Dependencies
numpy, pandas, matplotlib, seaborn, scikit-learn, imbalanced-learn
How to Run
Install libraries:
Copy code
pip install numpy pandas matplotlib seaborn scikit-learn imbalanced-learn
Place creditcard.csv in the working directory.
Run the script in a Jupyter Notebook or IDE.
Outputs
Balanced dataset visualization.
Logistic regression results:
Accuracy score.
Confusion matrix.
Classification report.
Future Work
Explore advanced models like Random Forests or Neural Networks.
Use SMOTE for synthetic over-sampling.
Perform hyperparameter tuning.
