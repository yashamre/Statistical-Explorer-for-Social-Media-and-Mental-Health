# Statistical Explorer for Social Media and Mental Health

This repository contains the research and codebase for the project *Statistical Explorer for Social Media and Mental Health*. The study investigates the relationship between social media usage and mental health using statistical methods such as **Exploratory Data Analysis (EDA)**, **hypothesis testing**, and **bootstrapping**. It highlights demographic factors influencing mental health and provides actionable insights for targeted interventions.

---

## Overview

### Objective
The study aims to explore the influence of social media usage on mental health outcomes, with a focus on:
- Demographic insights (age, gender).
- Mental health metrics (depression, concentration, sleep patterns).
- Statistical robustness through bootstrapping and hypothesis testing.

### Key Findings
- Younger individuals and females exhibit higher mental health impacts from social media.
- Excessive usage (4+ hours/day) correlates with negative mental health indicators.
- Bootstrapping confirms robust confidence intervals for observed metrics.

---

## Methodology

### Data Preparation
- Cleaned dataset to address missing values and categorical inconsistencies.
- Consolidated demographics for consistent analysis.

### Statistical Techniques
1. **Exploratory Data Analysis (EDA):**
   - Uncovered patterns in platform usage and time spent.
   - Correlation analysis between usage patterns and mental health indicators.
2. **Hypothesis Testing:**
   - ANOVA, T-tests, and Chi-square tests to validate observed differences.
3. **Bootstrapping:**
   - Provided confidence intervals for metrics like difficulty concentrating and depressive feelings.

### Technologies
- Python for data processing and visualization.
- Pandas, NumPy, Matplotlib, and Seaborn for EDA.
- SciPy for hypothesis testing.
- Bootstrapping via custom Python scripts.

---

## Repository Structure

- **/data/**: Cleaned and raw datasets.
- **/notebooks/**: Jupyter Notebooks detailing the analysis steps.
- **/scripts/**: Python scripts for statistical analysis and visualizations.
- **/results/**: Plots, tables, and bootstrapping outputs.
- **README.md**: Project overview and documentation.

---

## Getting Started

### Prerequisites
- Python 3.8 or above.
- Required libraries:
  ```
  pip install pandas numpy matplotlib seaborn scipy
  ```

### Running the Analysis
1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo/statistical-explorer.git
   cd statistical-explorer
   ```
2. Open the notebook in `/notebooks/` for step-by-step analysis:
   ```bash
   jupyter notebook notebooks/EDA_Hypothesis_Bootstrapping.ipynb
   ```

---

## Results and Visualizations
### Key Plots
1. Social Media Usage vs. Negative Mental Health Impact.
2. Bootstrapping Confidence Intervals for Gender Differences.
3. Demographic Breakdown of Platform Preferences.

### Recommendations
- Implement screen-time monitoring tools.
- Create targeted mental health awareness campaigns.

---

## Authors
- **Pratik Patil** - [prpa4639@colorado.edu](mailto:prpa4639@colorado.edu)
- **Om Kokate** - [omko8394@colorado.edu](mailto:omko8394@colorado.edu)
- **Yash Amre** - [yaam5835@colorado.edu](mailto:yaam5835@colorado.edu)

---

## References
1. [Mental Health Analysis in Social Media Posts: A Survey](https://link.springer.com/article/10.1007/s11831-022-09863-z)
2. [Social Media and Mental Health: Benefits, Risks, and Opportunities for Research and Practice](https://link.springer.com/article/10.1007/s41347-020-00134-x)
