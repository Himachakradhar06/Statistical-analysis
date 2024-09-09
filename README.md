# Heart Disease Dataset Analysis

This repository contains a detailed statistical analysis of a heart disease dataset. The analysis explores various statistical techniques, including descriptive and inferential statistics, and performs regression analysis to examine the relationships between attributes in the dataset.

## Dataset

The dataset used for the analysis is based on heart disease records with multiple attributes like age, sex, chest pain type (cp), resting blood pressure (trestbps), cholesterol (chol), and more. The target variable indicates the presence of heart disease (1 = disease, 0 = no disease).

### Sample Data:
| Age | Sex | CP | Trestbps | Chol | Fbs | Restecg | Thalach | Exang | Oldpeak | Slope | Ca | Thal | Target |
| --- | --- | --- | -------- | ---- | --- | ------- | ------- | ----- | ------- | ----- | -- | ---- | ------ |
| 63  | 1   | 3   | 145      | 233  | 1   | 0       | 150     | 0     | 2.3     | 0     | 0  | 1    | 1      |
| 57  | 0   | 0   | 120      | 354  | 0   | 1       | 163     | 1     | 0.6     | 2     | 0  | 2    | 1      |

## Analysis Breakdown

### 1. Descriptive Statistics
We began with a detailed overview of the dataset through descriptive statistics:
- **Mean**: The average values for each attribute.
- **Median**: The middle value, helpful in skewed distributions.
- **Mode**: The most frequent value.
- **Standard Deviation**: Measures the variation from the mean.
- **Variance**: The spread of data points in the dataset.
- **Range**: The difference between the maximum and minimum values.

**Key Findings:**
- The mean age of patients is approximately 51 years.
- Cholesterol levels vary significantly with a range of 162 units.

### 2. Inferential Statistics
We performed hypothesis testing, confidence intervals, and regression analysis:
- **Hypothesis Testing**: Conducted a t-test to determine whether chest pain type (cp) values significantly deviate from a hypothetical mean.
- **Confidence Intervals**: Computed for chest pain type, indicating that the true mean is likely between 0.44 and 1.81.
- **Regression Analysis**: Explored the relationship between chest pain (cp) and age, showing no strong linear relationship based on the model's R-squared value.

### 3. Visualization
Data visualization plays an important role in understanding patterns:
- **Scatter Plots**: Visualized the relationship between attributes such as chest pain type (cp) and age, sex, with regression lines to provide insights into their interactions.
  
### 4. Conclusions
- There is a significant skew in certain variables such as fasting blood sugar (fbs), suggesting most patients have normal fasting blood sugar levels.
- Regression analysis showed weak linear relationships between chest pain type and age, indicating that chest pain alone may not strongly predict the age of heart disease patients.
- Visualizations of relationships between variables offer insightful trends, helping to assess the need for more complex models in future studies.

## Requirements

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/heart-disease-analysis.git
