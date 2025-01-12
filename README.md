# Admission Prediction Using Machine Learning

## Overview
This project involves predicting the chances of a student being admitted to a university based on various parameters such as GRE score, TOEFL score, CGPA, and more. The dataset used for this project is sourced from Kaggle and provides valuable insights into the factors influencing admissions.

## Features of the Dataset
The dataset contains the following features:
- **GRE Score**: Graduate Record Examination score (out of 340).
- **TOEFL Score**: Test of English as a Foreign Language score (out of 120).
- **University Rating**: Rating of the university (1 to 5).
- **Statement of Purpose (SOP)**: Strength of the Statement of Purpose (1 to 5).
- **Letter of Recommendation (LOR)**: Strength of the Letter of Recommendation (1 to 5).
- **CGPA**: Undergraduate CGPA (on a scale of 10).
- **Research**: Whether the candidate has research experience (0 = No, 1 = Yes).
- **Chance of Admit**: The target variable, representing the probability of admission (0 to 1).

## Project Structure
The repository contains the following files:
- **`Admission_Predict_A3.csv`**: The dataset used for the analysis and prediction.
- **`(2022aaps0266h,2022a3ps1473h)Assn3.ipynb`**: Jupyter Notebook containing the data preprocessing, exploratory data analysis, and model training steps.
- **`requirements.txt`**: List of Python packages required to run the project.
- **`README.md`**: Documentation for the project.

## Steps to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/maheshwaridevang/Admission-Prediction-Using-Machine-Learning.git
   cd Admission-Prediction-Using-Machine-Learning
   ```
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook (2022aaps0266h,2022a3ps1473h)Assn3.ipynb
   ```
4. Follow the steps in the notebook to preprocess the data, train models, and make predictions.

## Machine Learning Workflow
1. **Data Preprocessing**: Cleaning and normalizing the dataset for better model performance.
2. **Exploratory Data Analysis (EDA)**: Visualizing and understanding the relationships between variables.
3. **Model Selection**: Training and evaluating various regression models to predict the chance of admission.
4. **Model Evaluation**: Using metrics like Mean Squared Error (MSE) and R-squared to assess model performance.

## Results
The model achieves a high degree of accuracy in predicting the probability of admission. Detailed results, including visualizations, are provided in the notebook.

## Future Enhancements
- Incorporating additional features to improve prediction accuracy.
- Deploying the model as a web application using Flask or FastAPI.
- Experimenting with advanced machine learning techniques like ensemble methods.

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute the code.

---

