# Predicting Student's Dropout and Academic Success

This project aims to predict student dropout rates and academic success using various machine learning techniques. The dataset used for this analysis is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success).

The success of students in completing their college education is of utmost importance to the development of the nation. Graduates become valuable contributors to the economy as part of the labor force. Moreover, timely completion of college helps schools and universities manage their budget efficiently since student retention plays a significant role in the allocation of expenses, particularly if the students are supported by scholarships. Nevertheless, certain factors affect students' ability to succeed in college. In this analysis, we will examine various factors such as demographics, socioeconomic and macroeconomic status, and academic performance that contribute to students' academic success. We will also utilize these factors to construct a model to predict whether students are likely to drop out or successfully complete their college education.

## Data Description

- **Marital Status**: The marital status of the student. (Categorical)
- **Application Mode**: The method of application used by the student. (Categorical)
- **Application Order**: The order in which the student applied. (Numerical)
- **Course**: The course taken by the student, such as agronomy, design, education, nursing, journalism, management, social service, and technologies. (Categorical)
- **Daytime/Evening Attendance**: Whether the student attends classes during the day or in the evening. (Categorical)
- **Previous Qualification**: The qualification obtained by the student before enrolling in higher education. (Categorical)
- **Nationality**: The nationality of the student. (Categorical)
- **Mother's Qualification**: The qualification of the student's mother. (Categorical)
- **Father's Qualification**: The qualification of the student's father. (Categorical)
- **Mother's Occupation**: The occupation of the student's mother. (Categorical)
- **Father's Occupation**: The occupation of the student's father. (Categorical)
- **Displaced**: Whether the student is a displaced person. (Categorical)
- **Educational Special Needs**: Whether the student has any special educational needs. (Categorical)
- **Debtor**: Whether the student is a debtor. (Categorical)
- **Tuition Fees Up to Date**: Whether the student's tuition fees are up to date. (Categorical)
- **Gender**: The gender of the student. (Categorical)
- **Scholarship Holder**: Whether the student is a scholarship holder. (Categorical)
- **Age at Enrollment**: The age of the student at the time of enrollment. (Numerical)
- **International**: Whether the student is an international student. (Categorical)
- **Curricular Units 1st Sem (Credited)**: The number of curricular units credited by the student in the first semester. (Numerical)
- **Curricular Units 1st Sem (Enrolled)**: The number of curricular units enrolled by the student in the first semester. (Numerical)
- **Curricular Units 1st Sem (Evaluations)**: The number of curricular units evaluated by the student in the first semester. (Numerical)
- **Curricular Units 1st Sem (Approved)**: The number of curricular units approved by the student in the first semester. (Numerical)
- **Curricular Units 1st Sem (Grade)**: The grade of the student in the first semester. (Numerical)
- **Curricular Units 1st Sem (Without Evaluations)**: The number of curricular units without evaluations in the first semester. (Numerical)
- **Curricular Units 2nd Sem (Credited)**: The number of curricular units credited by the student in the second semester. (Numerical)
- **Curricular Units 2nd Sem (Enrolled)**: The number of curricular units enrolled by the student in the second semester. (Numerical)
- **Curricular Units 2nd Sem (Evaluations)**: The number of curricular units evaluated by the student in the second semester. (Numerical)
- **Curricular Units 2nd Sem (Approved)**: The number of curricular units approved by the student in the second semester. (Numerical)
- **Curricular Units 2nd Sem (Grade)**: The grade of the student in the second semester. (Numerical)
- **Curricular Units 2nd Sem (Without Evaluations)**: The number of curricular units without evaluations in the second semester. (Numerical)
- **Unemployment Rate**: The unemployment rate at the time. (Numerical)
- **Inflation Rate**: The inflation rate at the time. (Numerical)
- **GDP**: The Gross Domestic Product at the time. (Numerical)
- **Target**: The target variable indicating dropout (0), enrolled (1), or graduate (2) status. (Categorical)

## Project Structure

This project is structured into several notebooks to ensure a modular approach:

1. **Data Acquisition**: Fetch the raw data and save it.
    - Notebook: `01_Predict_Students_Dropout_Get_Raw_Data.ipynb`
2. **Exploratory Data Analysis (EDA)**: Explore the data to understand its structure, distributions, and relationships.
    - Notebook: `02_Predict_Students_Dropout_EDA.ipynb`
3. **Data Cleaning**: Clean and preprocess the data to make it ready for analysis and modeling.
    - Notebook: `03_Predict_Students_Dropout_Data_Cleaning.ipynb`
4. **Modeling**: Build and evaluate machine learning models to predict student dropout and academic success.
    - Notebook: `04_Predict_Students_Dropout_Modeling.ipynb`

## Usage

1. Clone the repository and navigate to the project directory.
2. Ensure all required libraries are installed (e.g., pandas, numpy, matplotlib, seaborn, scikit-learn, etc.).
3. Run the notebooks in the order specified above to reproduce the analysis and models.

```bash
git clone <repository-url>
cd <project-directory>
