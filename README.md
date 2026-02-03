# A-B-Testing-Hypothesis-Testing-in-Python-Task-11
This task focuses on performing an A/B Testing analysis to evaluate the effectiveness of advertisements on user conversion. The objective is to compare user behavior between a control group (no ads) and a treatment group (shown ads) using statistical methods and draw data-driven conclusions.

# Dataset Used
  - Dataset Name: marketing_AB (Task11).csv
  - Key Columns:
      - user id – Unique identifier for users
      - test group – Indicates Control or Treatment group
      - converted – Conversion outcome (True/False)
      - total ads – Number of ads shown to a user
      - most ads day – Day with maximum ad exposure
      - most ads hour – Hour with maximum ad exposure

# Tools & Technologies
 - Python
 - Jupyter Notebook
 - Pandas & NumPy
 - SciPy (Statistical Testing)
 - Matplotlib / Seaborn (visualization)

# Data Preparation Steps
 - Loaded dataset into Jupyter Notebook
 - Converted converted column from True/False to 1/0
 - Separated data into Control and Treatment groups
 - Verified data types and handled missing values

# A/B Testing Methodology
 - Defined Null Hypothesis (H₀): No difference in conversion rates between control and treatment groups
 - Defined Alternative Hypothesis (H₁): Treatment group has a different conversion rate
 - Used Independent Two-Sample T-Test
 - Confidence level set at 95% (α = 0.05)

# Key Results
 - Conversion Rate (Control): ~1.78%
 - Conversion Rate (Treatment): ~2.55%
 - T-statistic: -8.657
 - P-value: 5.11e-18

# Interpretation & Insights
 - The p-value is significantly smaller than 0.05
 - The null hypothesis is rejected
 - There is a statistically significant difference between the two groups
 - Advertisements have a positive impact on conversion rate

# Business Conclusion
 - The A/B test confirms that users exposed to advertisements convert at a significantly higher rate than users who were not shown ads.
 - This indicates that the marketing strategy is effective and should be continued or scaled.


# Learning Outcomes
 - Understood A/B testing concepts and hypotheses
 - Gained hands-on experience with statistical testing
 - Learned to interpret t-statistics and p-values
 - Applied data-driven decision-making in a business context
   
