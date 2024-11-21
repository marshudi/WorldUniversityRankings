
# World University Rankings Analysis

This project explores the **World University Rankings** dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/mylesoneill/world-university-rankings?select=cwurData.csv), to uncover insights about global institutions, their rankings, and their performance metrics.

---

## Overview

The analysis focuses on the following key steps:

1. **Data Import and Setup**: 
   - Imported the dataset (`WorldUniversityRankings.csv`) and utilized essential libraries for analysis, including `Pandas`, `NumPy`, and `scikit-learn`.

2. **Data Preprocessing**: 
   - Cleaned the dataset by handling missing values and outliers, ensuring accurate and reliable analysis.

3. **Exploratory Data Analysis (EDA)**: 
   - Visualized trends and patterns using `Matplotlib` and `Seaborn`, offering insights into the relationships between variables.

4. **Feature Selection**: 
   - Identified key features using techniques like F-classification and Exhaustive Feature Selector to enhance the performance of machine learning models.

5. **Machine Learning Models**: 
   - Applied models such as `Decision Tree Classifier`, `Extra Trees Classifier`, and `Linear Regression` to classify data and predict outcomes.

---

## Key Insights

### 1. Correlation Between Variables
- Visualized correlations to understand relationships between different features.
![Correlation](https://github.com/marshudi/WorldUniversityRankings/assets/76883519/a9697ed3-bdd8-4d11-a303-588370092f34)

### 2. Negative Correlation Between `world_rank` and `score`
- Observed a strong negative correlation: as the rank improves (lower number), the score increases.
![Negative Correlation](https://github.com/marshudi/WorldUniversityRankings/assets/76883519/cb723567-882a-4a67-b1bc-daf6f01f469d)

### 3. Distribution of Institutions by Country
- The United States has the most institutions in the dataset.
![Institutions by Country](https://github.com/marshudi/WorldUniversityRankings/assets/76883519/7432f9c8-49a9-4ec3-b04f-d50d17137c4a)
![Institutions by Country](https://github.com/marshudi/WorldUniversityRankings/assets/76883519/f8de641f-7230-4c4b-a5a7-e5a3d9afb9f3)

### 4. Distribution of Institutions by Score
- Most institutions have scores in the range of 25-50.
![Institutions by Score](https://github.com/marshudi/WorldUniversityRankings/assets/76883519/2e41b5b8-1164-46f0-83bf-ba8b9bed0e98)

---

## Project Structure

The project includes the following files and folders:

- **`WorldUniversityRankings.csv`**: Original dataset file.
- **`Assignment.ipynb`**: Jupyter Notebook files for:
  - Data import and preprocessing.
  - Exploratory Data Analysis (EDA).
  - Feature selection.
  - Machine learning model implementation.

---

## Getting Started

1. Clone the repository and navigate to the project directory.
2. Install the required dependencies (see below).
3. Open the Jupyter Notebook files to explore the analysis steps and results.

---

## Dependencies

Make sure you have the following Python libraries installed:
- `Pandas`
- `NumPy`
- `Matplotlib`
- `Seaborn`
- `scikit-learn`
- `mlxtend`
- `plotly`

Install them using:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn mlxtend plotly


---

## Usage

- Use this project to analyze university rankings, identify trends, and practice feature selection and machine learning techniques.
- Adapt the code to explore additional datasets or apply new algorithms.

---

## Acknowledgments

- Dataset: [Kaggle - World University Rankings](https://www.kaggle.com/datasets/mylesoneill/world-university-rankings?select=cwurData.csv)
- Tools: Python, Jupyter Notebook, and various data analysis libraries.

Feel free to explore and extend this project for your own analysis needs. Contributions are welcome!
