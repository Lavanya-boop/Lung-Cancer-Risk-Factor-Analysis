# Lung-Cancer-Risk-Factor-Analysis# 

## Project Overview
This repository contains the code, data, and documentation for an analysis of lung cancer risk factors. The project investigates multiple factors that potentially influence lung cancer severity and constructs predictive models to evaluate risk. This work was completed as part of the I501 course at Indiana University-Purdue University Indianapolis.

## Team Members
- Jonathan Liu (Project Manager)
- Sameer Mohammad
- Bhargav Varidi
- Teja Pavani Jyesta
- Lavanya Ranganatham
- Pallavi Vandanapu

## Project Aims
1. Determine which risk factors are associated with lung cancer severity
2. Identify interactions between risk factors
3. Construct models to predict lung cancer risk

## Repository Structure
- `LungCancer_Analysis.ipynb`: Main Jupyter notebook containing data cleaning, analysis, visualization, and modeling
- `LungCancer_BackupCode.ipynb`: Additional modeling approaches and exploratory analysis
- `ProjectReport.md`: Comprehensive report detailing methodology, results, and discussion
- `ProjectTaskOutline.md`: Overview of project tasks and team member responsibilities

## Dataset
The analysis uses a dataset of 1,000 lung cancer patients, examining 23 unique parameters including:
- Demographics (age, gender)
- Behaviors (alcohol use, diet, smoking)
- Health conditions (dust allergy, genetic risk, chronic lung disease, obesity)
- Environmental conditions (air pollution, occupational hazards, passive smoking)
- Health symptoms (chest pain, coughing, fatigue, weight loss, shortness of breath, etc.)

## Methodology
The project follows a comprehensive data science methodology:
1. **Data Cleaning/Processing**: Converting categorical variables, handling outliers, scaling variables
2. **Data Analysis**: Correlation analysis between factors and severity, inter-factor correlation analysis
3. **Visualization**: Bar charts, heatmaps, scatter plots, and forest plots to identify patterns
4. **Model Development**: Three prediction models (linear regression, decision tree classification, k-nearest neighbors)

## Key Findings
- Statistically significant correlations were found between all examined factors and lung cancer severity
- Top factors correlated with severity: obesity, coughing of blood, alcohol use, dust allergy
- Surprisingly, smoking ranked 13th in correlation strength
- Predictive models achieved varying accuracy (60-100% depending on model and features)

## Models Developed
1. **Linear Regression**: Continuous numerical prediction of risk on a 1-9 scale
2. **Decision Tree Classification**: Categorical prediction based on hierarchical factors
3. **K-nearest Neighbors**: Prediction based on similarity to existing patients

## Limitations
- Dataset patterns show discrepancies with established medical literature
- Potential issues with data validity (particularly regarding smoking's relatively low ranking)
- All subjects already had lung cancer, limiting generalizability
- Potential model overfitting suggested by extremely high accuracy rates

## Getting Started
1. Clone this repository
2. Install required dependencies: `pip install -r requirements.txt`
3. Open Jupyter notebooks for detailed analysis

## Dependencies
- Python 3.8+
- pandas
- numpy
- scipy
- matplotlib
- seaborn
- scikit-learn

## License
This project is provided under the MIT License.

## Acknowledgments
- Dataset provided by Prithivraj (2017) via Data.World
- Professor and teaching assistants of I501 at IUPUI
