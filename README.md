# Credit Modeling Assignment

This project focuses on the development and evaluation of a credit risk scorecard model. The process is broken down into six sections, each addressing critical steps in the development of credit models. This work combines exploratory data analysis, feature engineering, model development, and final scorecard creation to predict the likelihood of default for a set of applicants.

---

## **Project Sections**

### **1. Exploratory Data Analysis (EDA)**

The `EDA.ipynb` notebook serves as the starting point for the project. In this section, we conduct a thorough audit of the data and examine the initial trends and distributions.

- **Data Audit**: An overview of the dataset, including summary statistics and missing data patterns.
- **Distribution of Through-the-Door Applications**: Insights into the volume and frequency of loan applications.
- **Trend of Loan Ticket Size Distribution**: Analysis of loan amounts across different segments.
- **Distribution of Applications per Segment**: Breakdown of applications based on demographic or financial criteria.

---

### **2. Data Preparation**

The data preparation phase includes handling missing values, engineering new features, and splitting the data for training and testing purposes.

- **Null Tracking**: Identification and treatment of missing data.
- **Feature Engineering**: Creation of new features that could enhance model performance.
- **Data Splitting**: Dividing the dataset into training and test sets to validate model performance.

---

### **3. Fine Classing, Coarse Classing, and Feature Selection**

In this section, we transform variables using Weight of Evidence (WoE) and Information Value (IV) techniques and perform feature selection to retain the most predictive features.

- **WoE and IV Calculations**: Measuring the predictive power of variables.
- **Feature Selection**: Choosing the most relevant features based on IV thresholds.
- **WoE Transformation**: Transforming categorical variables using WoE to ensure monotonicity.

---

### **4. Model Development**

This stage involves building and tuning the scorecard model.

- **Setting up Scorecard Object**: Initializing and training the scorecard model.
- **Characteristics Analysis Report**: Generating reports that explain the model's characteristics.
- **Save Model**: Storing the trained model for future use and evaluation.

---

### **5. Model Evaluation**

Here, we evaluate the model's performance using various metrics and visualizations to assess credit score distribution and model interpretability.

- **Scorecard and Credit Score Distribution**: Analysis of how the model assigns credit scores across the population.
- **Model Profile**: A detailed review of the model's performance.
- **Model Interpretability**: Understanding the decision-making process of the model, ensuring transparency and fairness.

---

### **6. Scorecard Profile Creation**

The final step involves loading the saved model and generating the final scorecard profile, which includes a detailed credit report for potential applicants.

- **Model Loader**: Loading the trained model for predictions.
- **Scorecard Profile**: Creating a detailed profile based on the scorecard outputs.
- **Final Credit Report**: Producing a comprehensive credit report based on the model's predictions.

---

## **How to Run the Project**

1. Clone this repository:  
   `git clone https://github.com/your-username/credit-modeling-assignment.git`

2. Install the required packages:  
   `pip install -r requirements.txt`

3. locate Notebooks folder for .ipynb files and .html view of the notebooks.  each notebook in the given sequence to explore the data, build the model, and generate the final scorecard profile.

4. Use the provided datasets to train the model and evaluate its performance.

---

## **Contributors**

- [Talha Qayyum](https://github.com/talhaqayyum89)

---
