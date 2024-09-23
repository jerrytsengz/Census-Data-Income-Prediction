# Census Data Income Prediction

## About

This project aims to predict whether an individual earns more than $50,000 annually based on census data. The analysis involves exploring demographic factors that influence income and building a predictive model to accurately classify individuals into income groups. 

## Insights and Key Findings

### Overview

By analyzing census data, this project identifies significant features that contribute to income levels and develops machine learning models to predict whether an individual’s income exceeds $50,000. 

### Key Findings

1. **Feature Importance**
   - The analysis reveals that factors such as **education level**, **age**, and **occupation** have a substantial impact on income prediction. 
   - Individuals with higher education, specialized occupations, and more work experience generally have a higher likelihood of earning more than $50,000 annually.

2. **Model Performance**
   - Various machine learning models, including Logistic Regression, Decision Trees, and Random Forest, were evaluated. Among them, Random Forest performed the best, with an accuracy rate of over 85%.
   - Feature scaling and data preprocessing, such as handling missing values and encoding categorical variables, significantly improved model performance.

3. **Data Imbalance**
   - The dataset exhibits class imbalance, with more individuals earning less than $50,000. Methods such as SMOTE (Synthetic Minority Over-sampling Technique) were considered to address this imbalance and enhance model predictions for the minority class.

4. **Challenges**
   - **Non-linear Relationships**: Some relationships between features and income are non-linear, requiring more advanced modeling techniques like ensemble methods.
   - **Correlation**: Certain features, such as education and occupation, exhibit multicollinearity, which could affect model interpretability.

### Recommendations

Based on the analysis, the following recommendations are proposed:

- **Feature Engineering**: Additional feature engineering, such as creating interaction terms between education and occupation, may further improve the model’s accuracy.
- **Model Optimization**: Hyperparameter tuning of models like Random Forest or Gradient Boosting could yield better predictive power.
- **Addressing Class Imbalance**: Techniques like resampling or using cost-sensitive algorithms should be employed to handle class imbalance more effectively.
- **Automation and Scaling**: Automate model training and testing processes for scalability in real-world applications.

## Data

The dataset used for this project comes from the U.S. Census and includes demographic and income information on individuals. The data provides a detailed view of various personal attributes such as:

- Age
- Workclass
- Education Level
- Marital Status
- Occupation
- Relationship
- Race
- Sex
- Capital Gain/Loss
- Hours per Week
- Native Country

## Process

1. **Data Cleaning and Preprocessing**: Handled missing values, encoded categorical features, and performed feature scaling to prepare the dataset for model training.
   
2. **Exploratory Data Analysis (EDA)**: Conducted thorough EDA to uncover patterns, trends, and correlations between demographic factors and income levels.

3. **Modeling**: Built various classification models using Python libraries such as:
   - **Logistic Regression**
   - **Decision Trees**
   - **Random Forest**
   - **Gradient Boosting**

4. **Model Evaluation**: Evaluated models using accuracy, precision, recall, and F1-score metrics to determine the best performing algorithm for predicting income.

5. **Visualization**: Created informative visualizations using Matplotlib and Seaborn to help communicate key insights and trends within the dataset.

## Results

The best performing model achieved an accuracy of over 85%, demonstrating its potential for practical applications in predicting income categories based on demographic factors.

## Conclusion

This project highlights the value of machine learning techniques in predictive analytics, particularly in classifying income levels using census data. Future work could focus on further refining the model, addressing data imbalance, and exploring additional feature interactions.
