
# CS5228 Project - Group 39

 The main aim of this project is
to provide a comprehensive solution to the housing challenges
faced by both potential renters and landlords in Singapore. By
harnessing historical data and predictive analytics, we strive to
equip individuals and stakeholders with valuable insights into
the Singaporean housing market.Please follow the below steps to navigate through the repository.

Github Link : https://github.com/bansal-parul/CS5228-Group39
## Table of Contents

- [1. Install Dependencies](#1-install-dependencies)
- [2. Repository Structure](#2-repository-structure)
- [3. Code Execution](#3-code-execution)



## Content

### 1. Install Dependencies

Ensure you have the required dependencies installed:

- Python 3.x
- Scikit Learn
- Numpy 
- Pandas
- seaborn
- matplotlib
- Jupyter Notebook / Colab
- lightgbm `pip install lightgbm` 
-  xgboost `pip install xgboost`

### 2. Repository Structure

The repo conatins the following files:

- `Data_Preprocessing.ipynb`: This notebook file encompasses exploratory data analysis (EDA) and comprehensive data preprocessing steps.
- `train_pdf_stock.csv` - This CSV file contains preprocessed train features derived from the comprehensive data preprocessing steps detailed in the previous notebook
- `test_pdf_stock.csv - This CSV file contains preprocessed test features derived from the comprehensive data preprocessing steps detailed in the previous notebook
- `Data_Superset.ipynb`: This notebook focuses on feature encoding techniques. It takes in the above mentioned csv files to generate the final dataset namely `train_superset.csv` and `test_superset.csv`
- `Linear_Regression.ipynb` : This notebook delves into the exploration of a Linear Regression model.
- `Random_Forest.ipynb `: This notebook delves into the exploration of a Random Forest model.
-  `XG_Boost.ipynb `: This notebook delves into the exploration of XG Boost model.
-  `Lgbm.ipynb`: This notebook delves into the exploration of LGBM model.
-  `Error_Analysis.ipynb` : This notebook perform error analysis on LGBM model ( best result among the 4 models )

### 3. Code Execution

This code can be executed on either Jupyter Notebook or Google Colab. Ensure to adjust the file paths according to your requirements before running the code. 

- Order of file execution
	-  `Data_Preprocessing.ipynb`
	-  `Data_Superset.ipynb`
	-  `Linear_Regression.ipynb`,`Random_Forest.ipynb `,`XG_Boost.ipynb `, `Lgbm.ipynb`
	-  `Error_Analysis.ipynb`

