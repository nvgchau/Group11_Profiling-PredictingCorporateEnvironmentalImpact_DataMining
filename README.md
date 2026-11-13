# Group 11 – Corporate Environmental Impact Analysis

This repository contains the datasets and Jupyter notebooks for the Group 11 Data Mining course project at the National Economics University.

The project analyzes corporate environmental impact using the Impact-Weighted Accounts dataset. The notebooks are organized into data cleaning, exploratory data analysis (EDA), and three research questions.

## Repository Contents

| File | Description |
|---|---|
| `Corporate-Environmental-Impact-Data-2020.xlsx` | Original dataset |
| `cleaned_environmental_impact_data.xlsx` | Cleaned dataset used in the analysis |
| `GROUP_11_DATA_CLEANING.ipynb` | Data inspection and cleaning |
| `GROUP_11_EDA.ipynb` | Exploratory data analysis |
| `GROUP_11_RQ1.ipynb` | Explanatory analysis of Environmental Intensity |
| `GROUP_11_RQ2.ipynb` | Clustering and environmental-impact profiling |
| `GROUP_11_RQ3.ipynb` | Environmental Intensity prediction |
| `README.md` | Repository documentation |

## Execution Order

Run the notebooks in the following order:

1. `GROUP_11_DATA_CLEANING.ipynb` – prepare the cleaned dataset from the original workbook.
2. `GROUP_11_EDA.ipynb` – explore the cleaned data.
3. `GROUP_11_RQ1.ipynb` – conduct the explanatory analysis.
4. `GROUP_11_RQ2.ipynb` – identify company environmental-impact profiles.
5. `GROUP_11_RQ3.ipynb` – train and evaluate predictive models.

The cleaned dataset is included in the repository. If you use this file, you can start directly from the EDA notebook.

## Environment and Dependencies

The notebooks are written in Python and can be run in Jupyter Notebook or Google Colab.

The project uses the following Python libraries:

- pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- scikit-learn
- XGBoost
- SHAP
- openpyxl

Install any missing packages in your notebook environment before running the relevant notebook. Make sure the required Excel files are available in the working directory or update the file paths to match your environment.

## Dataset Source

Corporate Environmental Impact Data 2020 – Impact-Weighted Accounts Project:

https://ifvi.org/impact-accounting-in-practice/resources/

## Project Report

The accompanying report is titled **“Profiling and Predicting Corporate Environmental Impact Using Impact-Weighted Environmental Data.”**
