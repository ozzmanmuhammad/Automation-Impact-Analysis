# Occupations, Education and Salaries by State and Likelihood of Automation

The following README provides an overview of the project "Occupations, Salaries by State and Likelihood of Automation" along with necessary instructions to run the code. The project aims to analyze various datasets related to occupations, salaries, education levels, and the likelihood of automation.

## Dataset

The project uses the following datasets:

1. [Salaries, median hourly/annual wages broken down by occupation, provided by BLS May 2021.](https://www.bls.gov/oes/current/oes_nat.htm#11-0000)
2. [Risk of automation broken down by occupation, provided by Carl Benedikt Frey and Michael A. Osborne](https://data.world/wnedds/occupations-by-state-and-likelihood-of-automation)
3. [Education and training assignments by detailed occupation](https://www.bls.gov/emp/tables/education-and-training-by-occupation.htm)
4. [Educational attainment for workers 25 years and older by detailed occupation](https://www.bls.gov/emp/tables/educational-attainment.htm)

## Libraries

The project uses the following Python libraries:

- Pandas
- Numpy
- Matplotlib
- Plotly Express
- Seaborn

## Preprocessing the Dataset

Before running the code, set the appropriate file paths for each dataset in the notebook. The datasets are assumed to be in Excel or CSV format.

## Analysis

The notebook performs various analyses on the combined dataset, exploring relationships between median income, probability of automation, total employment, and education levels. It visualizes the likelihood of job automation vs. total employment, likelihood of job automation vs. median income, and more.

* Which occupations contribute most to the American economy (in USD).
* What is the median wage for each typical level of education?
* Visualize the probability of automation vs total employment
* Likelihood of Job Automation by Education Level
* Likelihood of Job Automation vs Median Income
  ![newplot](https://github.com/ozzmanmuhammad/Automation-Impact-Analysis/assets/93766242/cac59214-904d-45c3-a2b8-8c8d61006ad1)
* Total number of jobs positions per state
* Jobs lost per state when we use automation thershold < 0.7

  

## Instructions

1. Download the necessary datasets and place them in the appropriate file paths mentioned in the notebook.
2. Ensure you have the required libraries installed by running the following command:
   ```
   pip install pandas numpy matplotlib plotly seaborn
   ```
3. Run the notebook in your preferred Python environment (e.g., Jupyter Notebook, Google Colab) to execute the code and generate visualizations.

Feel free to modify the code and explore further insights from the dataset.
