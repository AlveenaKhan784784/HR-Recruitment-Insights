# HR-Recruitment-Insights

# HR Analytics: Job Data Analysis

## Dataset:
[Here](https://www.kaggle.com/datasets/arashnic/hr-analytics-job-change-of-data-scientists)

## Objective
The objective of this project is to analyze HR job data to identify trends and insights related to hiring practices. We aim to explore the relationship between various candidate features (e.g., gender, experience, education) and the hiring outcome, represented as a binary target variable (1 for hired, 0 for not hired). This analysis will help uncover potential biases and improve recruitment strategies.

## Dataset
The dataset used in this analysis contains the following columns:
- **gender**: Gender of the candidate (e.g., Male, Female)
- **enrolled_university**: Type of university the candidate enrolled in (e.g., Full-time, Part-time, No enrollment)
- **experience**: Years of experience of the candidate
- **target**: Hiring outcome (1 = Hired, 0 = Not Hired)

## Data Preprocessing
### 1. Handling Missing Values
- Missing values were identified and filled appropriately:
  - Categorical features were filled with 'unknown' for missing entries.
  - Numerical features were filled with median values where applicable.
 
  ### 2. Handling Duplicates
- No duplicated were found in data.

### 3. Outlier Detection
- Outliers were analyzed for relevant numerical features, particularly in city development index and training hours.
- Outliers were kept as it is, as they contains useful information.

### 4. Encoding and Scaling
- Since this analysis focuses on visualizations rather than machine learning, encoding and scaling of categorical and numerical features were not necessary.

## Visualizations
### 1. Gender vs. Target
- A bar plot showing the distribution of hiring outcomes based on gender was created to visualize potential biases.

### 2. Experience vs. Target
- A box plot was generated to illustrate the distribution of experience across hired and non-hired candidates, highlighting trends in hiring preferences based on experience.

### 3. Enrolled University vs. Target
- A bar plot visualized the hiring rates based on the type of university candidates enrolled in, indicating if specific institutions are favored.

### 4. Correlation Analysis
- A heatmap was used to visualize correlations between numerical features, providing insights into factors affecting hiring decisions.

## Conclusion
Through visualizations and analyses, this project aimed to uncover insights into the hiring process. The results can inform HR practices and strategies for more equitable recruitment.
