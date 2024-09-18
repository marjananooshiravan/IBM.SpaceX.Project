# IBM.SpaceX.Project
## SpaceX Falcon 9 Landing Prediction
Overview
This project focuses on predicting whether the first stage of SpaceX's Falcon 9 rocket will successfully land. SpaceX reduces launch costs by reusing the first stage of their rockets. The ability to accurately predict successful landings is critical for minimizing costs and making informed decisions in the space launch industry. The dataset used for this project was sourced from Kaggle.
Project Structure
## The project involves several key steps:
1.	Data Preprocessing: The dataset was cleaned and prepared for analysis.
2.	Feature Engineering: Additional features were created to improve model performance.
3.	Model Selection: Four supervised learning models were tested to determine the best one:
o	K-Nearest Neighbors (KNN)
o	Decision Tree
o	Logistic Regression
o	Support Vector Machine (SVM)
## 4.	Model Evaluation:
o	The main goal was to minimize false negatives (Type II errors), as predicting a successful landing when one fails can have significant financial consequences.
o	Both Decision Tree and Support Vector Machine models achieved zero false negatives.
o	The SVM model had the highest accuracy at 96%, making it the best model for predicting successful Falcon 9 landings.
5.	Hyperparameter Tuning: GridSearchCV was used to optimize the models for the best performance.
##Results
The Support Vector Machine (SVM) model was chosen as the final model for predicting Falcon 9 landings. It achieved an accuracy of approximately 96% and had zero false negatives, making it highly reliable for this task.
##Requirements

##The following libraries are required to run this project:

•	Pandas
•	NumPy
•	Matplotlib
•	Seaborn
•	Scikit-learn

•	The Support Vector Machine (SVM) model is the most accurate model for predicting successful Falcon 9 landings, achieving 96% accuracy.
•	The model effectively minimizes false negatives, providing a high degree of confidence in predicting successful landings.
  This approach can help companies make better-informed decisions regarding launch costs and risks, particularly in bidding against competitors like SpaceX.

