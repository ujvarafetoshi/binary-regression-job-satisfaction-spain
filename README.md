# Economic Fluctuations and Job Satisfaction in Spain

## Project Introduction

This repository contains the data science project "How Economic Fluctuations Influence Job Satisfaction Among Employees in Spain". It utilizes data from the European Social Survey's 10th round (2020) to explore the relationships between economic conditions, job security, work-life balance, and their impacts on job satisfaction levels among Spanish employees.

## Dataset Overview

- **Full Dataset - Spain.csv & Full Dataset - Spain.html**: Initial datasets for variable selection.
- **Full Dataset - Spain - Variable Selection - Stage 1 - FINAL.xlsx**: Prepared dataset for model implementation, derived from the initial datasets.

## Project Structure

1. **01_Preliminary_Variable_Selection.ipynb**
   - Focuses on the preprocessing of raw data and selection of relevant variables.
2. **02_Data_Analysis_Modelling_Prediction.ipnyb**
   - Covers exploratory data analysis, model building, predictions and validation processes.

## Getting Started with Google Colab

Google Colab is a free, cloud-based service that allows you to run Jupyter Notebooks without any local setup. It's perfect for this project as it simplifies the process of running complex data analysis and model training sessions. Follow these steps to use Colab:

### Step 1: Access Google Colab

- Navigate to [Google Colab](https://colab.research.google.com/). Log in with your Google account if prompted.

### Step 2: Open Project Notebooks

- Once in Colab, click on `File` > `Open notebook`.
- Select the `GitHub` tab in the popup window.
- Enter the URL of this GitHub repository and press Enter.
- You will see a list of available Jupyter notebooks (`.ipynb` files) in the repository. Click on the one you wish to open.


### Step 3: Uploading Data Files

Some notebooks may require access to the dataset files listed in the Dataset Overview section. Follow these steps to upload data files to Colab:

- In the Colab notebook, click on the folder icon on the left sidebar to open the Files tab.
- Click on the upload icon (📤) and select the data files from your computer.
- For '01_Preliminary Variable Selection.ipynb' notebook, upload these files 'Full Dataset - Spain.csv' & 'Full Dataset - Spain.html'
- For '02_Data_Analysis_Modelling_Prediction.ipynb' notebook, upload 'Full Dataset - Spain - Variable Selection - Stage 1 - FINAL.xlsx'
- Wait for the upload to complete. You can then access these files from the notebook.

### Step 4: Running Notebooks

- After uploading the files, you can run the code cells sequentially by clicking on the play button (▶️) on the left side of each code cell.
- To run all cells in the notebook, you can go to `Runtime` > `Run all`.

## Analysis Phases

### Preliminary Variable Selection

- **Notebook**: `01_Preliminary_Variable_Selection.ipynb`
- **Objective**: To clean and select relevant variables from the raw dataset.
- **Key Steps**:
  1. Data cleaning, including handling missing values and renaming columns for clarity.
  2. Preliminary analysis to identify variables significantly impacting job satisfaction.

### Model Implementation

- **Notebook**: `02_Data_Analysis_Modelling_Prediction.ipynb`
- **Objective**: To build predictive models that assess the impact of various factors on job satisfaction.
- **Key Steps**:
  1. Exploratory Data Analysis (EDA) to understand data distribution and underlying patterns.
  2. Creation of a richer set of covariates, including handling multicollinearity and variable transformation.
  3. Model building, including Logistic Regression and Probit models, to estimate the influence of selected variables on job satisfaction.
  4. Model validation and selection based on performance metrics like AUC, R2 Efron, and classification accuracy.

## Key Findings

- **Economic Fluctuations**: Strongly influence job satisfaction, with employees feeling less secure during economic downturns.
- **Job Security and Work-Life Balance**: Emerged as significant predictors of job satisfaction.
- **Socio-Demographic Factors**: Gender, age, and household composition also play a crucial role in determining job satisfaction.
- **Model Insights**: The logistic regression model binned model(Model 1) provided the best fit, indicating that both individual perceptions and broader economic conditions significantly impact job satisfaction.


## Contributing

We welcome contributions to improve the project. Please fork the repository, make your changes, and submit a pull request with a description of your modifications.

## Acknowledgments

- European Social Survey for the comprehensive data on Spain.
- Our professors and colleagues for their invaluable feedback and support throughout this project.

