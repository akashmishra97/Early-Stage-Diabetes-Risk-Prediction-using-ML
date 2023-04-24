

# Early Stage Diabetes Risk Prediction

This project aims to predict the risk of early stage diabetes using machine learning techniques. The dataset used in this project was collected from patients of Sylhet Diabetes Hospital in Sylhet, Bangladesh and approved by a doctor.

## Dataset Information
The dataset contains the following attributes:

1. Age: Age of the patient (ranging from 20 to 65)
2. Sex: Gender of the patient (1 for Male, 2 for Female)
3. Polyuria: Presence of polyuria symptom (1 for Yes, 2 for No)
4. Polydipsia: Presence of polydipsia symptom (1 for Yes, 2 for No)
5. Sudden weight loss: Presence of sudden weight loss symptom (1 for Yes, 2 for No)
6. Weakness: Presence of weakness symptom (1 for Yes, 2 for No)
7. Polyphagia: Presence of polyphagia symptom (1 for Yes, 2 for No)
8. Genital thrush: Presence of genital thrush symptom (1 for Yes, 2 for No)
9. Visual blurring: Presence of visual blurring symptom (1 for Yes, 2 for No)
10.Itching: Presence of itching symptom (1 for Yes, 2 for No)
11. Irritability: Presence of irritability symptom (1 for Yes, 2 for No)
12. Delayed healing: Presence of delayed healing symptom (1 for Yes, 2 for No)
13. Partial paresis: Presence of partial paresis symptom (1 for Yes, 2 for No)
14. Muscle stiffness: Presence of muscle stiffness symptom (1 for Yes, 2 for No)
15. Alopecia: Presence of alopecia symptom (1 for Yes, 2 for No)
16. Obesity: Presence of obesity symptom (1 for Yes, 2 for No)
17. Class: Diagnosis of diabetes (1 for Positive, 2 for Negative)
## Project Structure

This project is organized into two Jupyter notebooks:

**DiabetesRiskPrediction_DataPreprocessing.ipynb**: This notebook focuses on data preprocessing tasks such as handling missing values, encoding categorical variables, and splitting the dataset into training and testing sets. The preprocessed datasets are saved and exported as X_train, X_test, y_train, and y_test for further modeling.

**DiabetesRiskPrediction_models.ipynb**: This notebook implements various machine learning models, including logistic regression, support vector machine (SVM), decision trees, and deep neural networks, using the preprocessed datasets. Hyperparameter tuning is performed to optimize the models. Recall, which measures the true positive rate, is chosen as the performance metric to evaluate the models. The deep neural network model achieved the best performance with a recall score of 98.9%.

## Instructions for Running the Project

To run this project on your local machine, follow these steps:

1. Clone the repository from GitHub: GitHub Repository URL

2. Install the required libraries and dependencies listed in the requirements.txt file.

3. Open the Jupyter notebooks in the following order:
    3.1 DiabetesRiskPrediction_DataPreprocessing.ipynb
    3.2 DiabetesRiskPrediction_models.ipynb
   
4. Run each cell in the notebooks sequentially to preprocess the data, train the machine learning models, and evaluate their performance.

5. You can modify the hyperparameters or try different models to further improve the model's performance.

## Conclusion
This project demonstrates the use of machine learning techniques for early stage diabetes risk prediction. The deep neural network model achieved the best performance with a recall score of 98.9%. The code and datasets are provided in this repository for reference and further development. If you have any questions
