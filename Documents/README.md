# EMPLOYEE SENTIMENT ANALYSIS

## Project Overview
This project aims to analyze employee sentiment and engagement through NLP and statistical analysis. The objective is to label employee messages as Positive, Negative, or Neutral, compute sentiment scores, rank employees, identify flight risks, and develop a predictive model to forecast sentiment trends.

## Key Steps and Deliverables

1. **Sentiment Labeling:** 
   - Used NLP techniques to label messages as Positive, Negative, or Neutral.
   - Applied a pre-trained model for accurate labeling.

2. **Exploratory Data Analysis (EDA):**
   - Analyzed sentiment distribution.
   - Visualized trends over time.
   - Examined anomalies and patterns.

3. **Employee Score Calculation:**
   - Calculated monthly sentiment scores for each employee.
   - Aggregated scores based on message sentiment.

4. **Employee Ranking:**
   - Ranked employees based on positive and negative sentiment scores.
   - Identified top three positive and negative employees each month.

5. **Flight Risk Identification:**
   - Detected employees at risk of leaving based on frequent negative messages.
   - Defined flight risk as sending 4 or more negative messages in a 30-day rolling window.

6. **Predictive Modeling:**
   - Built a linear regression model to predict sentiment trends.
   - Evaluated model accuracy using R-squared and Mean Squared Error.

## Visualizations
- The visualizations used for analysis and modeling are stored in the `visualizations/` folder. Key plots include:
  - Sentiment Distribution Plot
  - Correlation Matrix (Heat map)
  - Monthly Sentiment Scores Distribution
  - Employee Sentiment Trend
  - Monthly Sentiment Comparison Plot
  - Top 3 and Bottom 3 Employees
  - Sentiments Word Cloud
  - Message Lenght by Sentiment Boxplot
  - Monthly Sentiment Distribution Trend
  - Positive and Negative Ranking Plot
  - Flight Risk Plot

## Key Findings
- The analysis revealed that a small subset of employees had consistent negative sentiment, indicating potential flight risk.
- The predictive model achieved good accuracy, highlighting time-based patterns in sentiment trends.

## How to Run
1. Clone the repository.
2. Install dependencies.
3. Run the Jupyter Notebook file to reproduce the analysis.

## Contact
For any inquiries, please reach out to EMMANUEL UMEOGU at [emmanuelumeogu@gmail.com].
