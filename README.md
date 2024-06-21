# Predictive-Model-for-Student-Retention-using-PySpark

## Introduction

**Why this dataset?**

Educational institutions increasingly rely on data to predict student outcomes and enhance retention strategies. This project utilizes PySpark to process large educational datasets effectively, aiming to predict student dropout and academic success.

**Objective:**

- Predict student dropout and academic success using large-scale educational datasets.
- Implement a predictive model to optimize interventions, increase retention rates, and personalize student support.

## Business Problem

High student dropout rates challenge educational effectiveness and economic stability, affecting institutional reputation, financial health, and personal growth of students. The key question is: **Can we accurately predict which students are at risk of dropping out using available data?**

## Existing Solution & Necessity for a New Model

**Existing Model Limitations:**

- Basic ML techniques with limited support for large-scale data.
- Issues with scalability and performance.

**Advancements with New Model:**

- Integration of PySpark for efficient handling of large datasets.
- Adoption of advanced ML algorithms and techniques for better model development.

## Methodology

- Integration of data from academic records, socio-economic backgrounds, and behavioral data.
- Utilization of PySpark for efficient data handling and processing, ensuring robust data integrity and speed.
- Deployment of various machine learning techniques to identify potential dropouts early in their academic journey.

## Understanding Source Data

**Source:**

- UCI ML repository: An open-source repository providing diverse datasets for educational research and analysis.
- Student Retention and Academic Success Dataset: Developed under the SATDAP program, aimed at reducing dropout and failure rates in higher education.

**Data Type:**

- Classification Data: Structured for a three-category classification task with the target column of cardinality 3 (Dropout, Enrolled, Graduate).

## Attribute Information

| Feature Name | Feature Description |
|--------------|---------------------|
| Marital Status | Indicates the marital status of the student |
| Nationality | The student's nationality reflecting diverse backgrounds |
| Gender | The gender identity of the student |
| Age at Enrollment | Age of the student at the time of enrollment |
| Course | The specific course or program the student is enrolled in |
| Application Mode | How the student applied to the institution |
| Application Order | The priority or order of application among multiple choices |
| Previous Qualification | The highest qualification obtained before current enrollment |
| Previous Qualification (Grade) | Grades associated with the previous qualification |
| Mother's Qualification | Educational qualification of the student's mother |
| Father's Qualification | Educational qualification of the student's father |
| Mother's Occupation | The occupation of the student's mother |
| Father's Occupation | The occupation of the student's father |
| Tuition Fees Up to Date | Whether tuition fees are paid up to date |
| Scholarship Holder | Indicates if the student is receiving a scholarship |
| Debtor | Indicates if the student owes any debts to the institution |
| Daytime/Evening Attendance | Whether the student attends daytime or evening classes |
| Curricular Units 1st/2nd Sem | Detailed metrics of academic involvement and performance over the first and second semesters |
| Unemployment Rate | Regional unemployment rate indicating economic conditions that might affect student success |
| Inflation Rate | Inflation rate at the time of study providing context on economic stability |
| GDP | Gross Domestic Product reflecting the economic environment surrounding the educational sector |
| Displaced | Indicates whether the student is displaced due to any reason |
| Educational Special Needs | Whether the student has any special educational needs |
| International | Whether the student is an international student |
| Target | The classification outcome for each student – dropout, enrolled, or graduate |

## Modelling Techniques & Performance Tuning

**Classifier Models:**

- Logistic Regression
- Decision Tree

**Ensemble Techniques:**

- Random Forest

## Choosing the Best Metrics for Our Models

**False Positive Error:**
- Predicts dropout incorrectly, leading to misdirected resources and potential stress for the student.

**False Negative Error:**
- Fails to predict dropout, missing opportunities for timely intervention, leading to actual dropout.

**Best Model:**

- Random Forest: Best precision with a precision score of 76.88%.

| Model               | Accuracy | Recall  | Precision | F1 Score |
|---------------------|----------|---------|-----------|----------|
| Logistic Regression | 71.61%   | 71.61%  | 68.43%    | 67.18%   |
| Decision Tree       | 71.49%   | 71.49%  | 70.67%    | 68.69%   |
| Random Forest       | 71.85%   | 71.85%  | 76.88%    | 65.37%   |
| Random Forest Ht    | 73.99%   | 73.99%  | 72.53%    | 71.34%   |

## Conclusion

PySpark's robust data processing capabilities enable the development of accurate predictive models that significantly reduce dropout rates and personalize student support. Institutions are encouraged to adopt advanced data analytics to transform educational outcomes through targeted interventions.

## Future Scope

- **Improvements:** Exploration of neural networks and deep learning models to enhance prediction accuracy.
- **Integration:** Potential to integrate the predictive model with student management systems for real-time analytics and interventions.
- **Expansion:** Explore other areas of application, such as predictive maintenance of institutional resources and facilities.
