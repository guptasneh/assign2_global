Global Pollution Classification Project


This project applies machine learning techniques to classify global regions into either High or Low Pollution Zones. It utilizes pollution-related data, including levels of CO₂, SO₂, NO₂, energy consumption, and other indicators to predict pollution severity. The objective is to support environmental monitoring efforts by identifying high-risk regions through data-driven models.

Three classification algorithms were implemented: Naive Bayes (GaussianNB), K-Nearest Neighbors (KNeighborsClassifier with k=5), and Decision Tree Classifier. The dataset underwent preprocessing steps including handling of missing values, removal of irrelevant columns (such as names and locations), label encoding of categorical features, and feature scaling (particularly important for KNN). The dataset was split into training and testing sets in an 80:20 ratio.

To evaluate model performance, the project employed metrics such as Accuracy, Precision, Recall, F1 Score, and Confusion Matrix. Among the three models, Decision Tree Classifier achieved the highest accuracy of 1.0 (100%), outperforming both Naive Bayes and KNN, which each achieved approximately 56% accuracy. The Decision Tree also recorded perfect scores in precision, recall, and F1, demonstrating strong generalization for this task.

To run this project locally, clone the repository using Git and navigate into the project directory. Install the required Python packages using pip install -r requirements.txt, then open and run the Jupyter Notebook titled Assigment2_global.ipynb.

Future enhancements could include incorporating cross-validation to reduce overfitting, introducing ensemble methods like Random Forest or XGBoost, integrating real-time pollution data from external APIs, and expanding the feature set to include seasonal or geographic trends for improved prediction accuracy.

