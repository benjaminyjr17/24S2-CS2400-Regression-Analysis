# 24S2-CS2400 Individual Assignment: Multiple and Polynomial Regression Analysis of Death Rate Determinants  

## Overview  
This repository contains a comprehensive statistical analysis of death rate determinants using multiple and polynomial regression techniques.  This analysis was completed as part of the CS2400 Individual Assignment at Nanyang Technological University (31-MARCH-2025).  

## Project Links  
•	[GitHub Repo](https://github.com/benjaminyjr17/CS2400-Regression-Analysis.git)  
•	[View Rendered Notebook](https://nbviewer.org/github/benjaminyjr17/24S2-CS2400-Regression-Analysis/blob/a7295c2262a5847b3626b0b302e7279e69aef10f/Benjamin_Oliver_Yick_U2120984H.ipynb)  

## Project Description  
This analysis examines how various socioeconomic and environmental factors influence regional death rates.  Two regression approaches were implemented:  
1.	Multiple Regression: Analyzing the relationship between death rates and two independent variables (schooling levels and non-white population percentage).  
2.	Polynomial Regression: Investigating the non-linear relationship between death rates and non-white population percentage.  

## Critical Files  
•	Benjamin_Oliver_Yick_U2120984H.ipynb: Jupyter notebook containing the complete analysis, visualizations, and findings.  
•	CS2400 Individual Assignment Briefs (AY24-25 - Semester 1).pdf: Official assignment requirements and guidelines from Nanyang Technological University, outlining the multiple and polynomial regression tasks, submission guidelines, and evaluation criteria.  
•	Individual Assignment Dataset (AY24-25 - Semester 1).csv: Extracted dataset used for the regression analysis.  
•	Report.md: 150-word summary of findings.  
•	Memorandum.md: 400-word memorandum suggesting additional variables for death rate prediction.  

## Methods Used  
•	Correlation analysis.  
•	Cramer’s Rule for solving standard equations.  
•	Data exploration and visualization.  
•	Multiple linear regression.  
•	Polynomial regression.  
•	Residual analysis.  

## Critical Findings  
•	Polynomial regression of x₉ revealed a non-linear relationship with death rates.  
•	Variables x₆ (schooling for persons over 22) and x₉ (percentage non-white population) showed strong correlations with death rates.  
•	The multiple regression model achieved an **R² score of 0.5628.**  
•	The polynomial regression model achieved an **R² score of 0.4157.**  
•	Three additional variables (healthcare access, chronic disease prevalence, and income inequality) were proposed to improve the prediction.  

## Final Equations  
The analysis yielded the following regression models for predicting death rates:  

### Multiple Regression Model  
**y = 1211.8562 + (-28.9793)x₆ + (3.9165)x₉**, **R² = 0.5628.**  

Where:  
•	y = death rate.  
•	x₆ = schooling for persons over 22.  
•	x₉ = percentage non-white population.  

This model explains approximately **56.28%** of the variance in death rates, with education level having a negative relationship with mortality, while non-white population percentage shows a positive correlation.  

### Polynomial Regression Model  
**y = 882.9963 + (5.2506)x₉ + (-0.0227)x₉²**, **R² = 0.4157.**  

This non-linear model captures the curvilinear relationship between nonwhite population percentage and death rates, explaining **41.57%** of the variance in mortality rates.  

These models demonstrate that socioeconomic factors significantly influence mortality outcomes, with education as a protective factor, while demographic composition shows more complex relationships requiring polynomial modeling.  

## Setup and Usage  

### Prerequisites  
•	Python 3.8+.  
•	Git.  
•	Jupyter Notebook or JupyterLab.  

### Step-by-Step Instructions  

1. **Clone this repository**  
   ```bash  
   git clone https://github.com/BenjaminYick/CS2400-Regression-Analysis.git  
   cd CS2400-Regression-Analysis  

2. **Set up a virtual environment (recommended)**  
   # Create virtual environment  
   python -m venv venv  

   # Activate virtual environment  
   # On Windows:  
   venv\Scripts\activate  
   # On macOS/Linux:  
   source venv/bin/activate  

3. **Install Required Dependencies**  
   # Install all required packages  
   pip install numpy pandas matplotlib seaborn statsmodels scikit-learn jupyter  

   # Verify installations  
   pip list | grep -E "numpy|pandas|matplotlib|seaborn|statsmodels"  

## Contact Information  
•	Benjamin Oliver Yick.  
•	Final-Year Data Science and Artificial Intelligence Undergraduate | Double Minors in Business and Communication Studies |  
•	Visiting Student, Wee Kim Wee School of Communication and Information (WKWSCI).  
•	Nanyang Technological University, Singapore.  
•	GitHub: github.com/benjaminyjr17  
•	🔗 [LinkedIn](https://www.linkedin.com/in/benjaminyjr17)  
•	📧 Academic Email: BENJ0045@E.NTU.EDU.SG  
•	For questions regarding this analysis or collaboration opportunities, please feel free to connect via GitHub or LinkedIn.  
