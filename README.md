# Lead Scoring Model for X Education

## Project Overview
This project aims to build a **Lead Scoring Model** for **X Education**, an online course provider. The objective is to predict the likelihood of a lead converting into a paying customer using **Logistic Regression** and assign a lead score between **0 and 100**. The model helps optimize sales efforts by focusing on high-potential leads, improving the conversion rate from **30% to a targeted 80%**.

## Dataset
The dataset consists of **9000+ lead records** with various attributes such as:
- **Lead Source** (Google, LinkedIn, Referral, etc.)
- **Total Time Spent on Website**
- **Last Activity** (Email Opened, SMS Received, etc.)
- **Lead Origin**
- **Total Visits**
- **Converted** (Target variable: 1 = Converted, 0 = Not Converted)

## Process Followed
### 1. **Data Understanding & Cleaning**
- Handled missing values by imputing or removing irrelevant data.
- Removed duplicate records and inconsistencies.
- Created dummy variables for categorical data.
- Derived new metrics where applicable.

### 2. **Exploratory Data Analysis (EDA)**
- **Univariate Analysis**: Identified key patterns in lead behavior.
- **Bivariate Analysis**: Correlation analysis between features and conversion rate.
- Identified most influential variables using statistical analysis.

### 3. **Model Building**
- Implemented **Logistic Regression** for binary classification.
- Performed **Feature Selection** using statistical tests.
- Split data into **train (70%) and test (30%)** sets.
- Applied **Standard Scaling** to numerical features.

### 4. **Model Evaluation & Optimization**
- Optimized probability cutoff based on **Precision-Recall tradeoff**.
- Evaluated using **Accuracy, Sensitivity, Specificity, Precision, and Recall**.

#### **Final Model Performance:**
| Metric      | Test Set |
|------------|---------|
| Accuracy   | **91%** |
| Sensitivity | **88%** |
| Specificity | **94%** |

### 5. **Business Recommendations**
- **During Intern Hiring Period:** Lower lead score threshold (0.5) and increase outreach.
- **After Hitting Quarterly Targets:** Increase lead score threshold (0.8) to minimize unnecessary calls.
- Focus more on leads from **high-converting sources** (Google, LinkedIn, Referrals).
- Automate follow-ups to optimize sales efficiency.

## Files Included
- **`Lead_scoring_assignment.ipynb`** - Jupyter Notebook with code and analysis.
- **`LEAD_SCORE_CASE_STUDY.pptx`** - Presentation summarizing the findings.
- **`Assignment_Subjective_Questions.docx`** - Answers to business-related questions.
- **`Summary_Report.pdf`** - 500-word report summarizing the project.

## How to Run the Project
1. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Lead_scoring_assignment.ipynb
   ```
3. Run the cells step by step to execute data cleaning, EDA, model building, and evaluation.

## Evaluation Criteria
This project is evaluated based on:
- **Data Preparation & EDA (30%)**: Proper handling of missing values, encoding, and data cleaning.
- **Model Building & Evaluation (40%)**: Feature selection, performance metrics, and business alignment.
- **Subjective Questions (10%)**: Clear and well-explained answers.
- **Presentation & Recommendations (10%)**: Structured insights and actionable takeaways.
- **Code Readability (5%)**: Well-documented, optimized, and easy to understand.
- **Summary Report (5%)**: Clear explanation of approach and learnings within 500 words.

## Conclusion
This lead scoring model successfully identifies **high-potential leads**, improves sales efficiency, and provides actionable business insights. By refining outreach strategies based on the model’s predictions, **X Education** can significantly enhance its **conversion rate and revenue generation**. 

