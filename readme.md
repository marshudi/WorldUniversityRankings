# World University Rankings Analysis

This project focuses on analyzing the World University Rankings dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/mylesoneill/world-university-rankings?select=cwurData.csv).

## Overview

In this project, we've performed a comprehensive analysis of the World University Rankings dataset. The analysis comprises several key steps:

1. **Data Import and Setup**: We started by importing the dataset (`data.csv`) and essential libraries for data analysis. Key libraries used include Pandas for data manipulation, NumPy for numerical operations, and scikit-learn for machine learning-related metrics.
   
2. **Data Preprocessing**: We conducted data preprocessing to address issues such as missing values and outliers. This step ensures that the data is clean and suitable for analysis.

3. **Exploratory Data Analysis (EDA)**: We used data visualization techniques to gain insights into the dataset. Matplotlib and Seaborn were employed for creating various plots and charts to help us better understand the data.

4. **Feature Selection**: We utilized feature selection techniques to identify the most relevant features for our analysis. This helps improve the efficiency and accuracy of subsequent machine learning models. Feature selection methods include F-classification and the Exhaustive Feature Selector.

5. **Machine Learning Models**: We applied machine learning models to the dataset. This includes using models such as Decision Tree Classifier, Extra Trees Classifier, and Linear Regression to make predictions or classify data.

## Project Structure

The project's structure includes the following files and folders:

- `data.csv`: The original dataset file.
- `Assignment.ipynb`: Jupyter Notebook file containing data import and preprocessing steps. 
- `Assignment.ipynb`: Jupyter Notebook file with exploratory data analysis.
- `Assignment.ipynb`: Jupyter Notebook file for feature selection.
- `Assignment.ipynb`: Jupyter Notebook file for applying machine learning models.

## Getting Started

To explore the project and its analysis, you can refer to the Jupyter Notebook files mentioned above. Each notebook contains detailed code, explanations, and visualizations.

## Usage

Feel free to use this project and its findings as a reference for your own data analysis and machine learning tasks. You can adapt and extend the code to suit your specific requirements.

## Dependencies

Ensure you have the following Python libraries installed to run the code successfully:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- mlxtend
- plotly

## Acknowledgments

- The dataset used in this project is sourced from Kaggle, and we appreciate the contributions of the Kaggle community.

Please explore the provided notebooks for a more detailed view of the analysis and results.

## Visualize correlation between variables
![image](https://github.com/marshudi/WorldUniversityRankings/assets/76883519/a9697ed3-bdd8-4d11-a303-588370092f34)

## negative Correlation between world_rank & score

![image](https://github.com/marshudi/WorldUniversityRankings/assets/76883519/cb723567-882a-4a67-b1bc-daf6f01f469d)

## Group the data by country and count the number of institutions
### as we can see the most institution are from the USA 

![image](https://github.com/marshudi/WorldUniversityRankings/assets/76883519/7432f9c8-49a9-4ec3-b04f-d50d17137c4a)

![image](https://github.com/marshudi/WorldUniversityRankings/assets/76883519/f8de641f-7230-4c4b-a5a7-e5a3d9afb9f3)


## Group the data by score and count the number of institution
### as you can see most institution have the score of around 25-50

![image](https://github.com/marshudi/WorldUniversityRankings/assets/76883519/2e41b5b8-1164-46f0-83bf-ba8b9bed0e98)


