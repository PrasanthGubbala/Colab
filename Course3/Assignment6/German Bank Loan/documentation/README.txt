
# Loan Default Prediction Project

## Project Overview:

This project aims to build a machine learning model to predict whether a customer will default on a loan based on historical data from a German bank. 
The dataset contains information about various customer attributes, including employment duration, credit history, and existing loans. 
The goal is to assist the bank in identifying potential loan defaulters and mitigating financial risks.

## Project Organization:

The project is organized into the following sections:

1. **Data Exploration and Preprocessing:**
   - Jupyter Notebook: `1_data_exploration.ipynb`
   - Description: This notebook explores the dataset, handles missing values, encodes categorical variables, and prepares the data for model training.
   
   - Jupyter Notebook:	`2_manipulate_wrangle_visualize.ipynb`
   - Description: This notebook explores the dataset, manipulate, wrangle, visualize data

2. **Model Building and Evaluation:**
   - Jupyter Notebook: `3_model_building.ipynb`
   - Description: This notebook includes the selection of machine learning models, training, hyperparameter tuning, and evaluation of model performance.

3. **Results and Analysis:**
   - Jupyter Notebook: `3_model_building.ipynb`
   - Description: This notebook includes the selection of machine learning models, training, hyperparameter tuning, and evaluation of model performance. also this includes notebook presents the results of the model in the last cell which is marktown cell.

4. **Documentation:**
   - Folder: `documentation`
   - Files: 
     - `README.txt`: Comprehensive documentation on the project, including instructions for reproducing the results.
     - `model_documentation.md`: Details about the chosen machine learning models, hyperparameters, and preprocessing steps.

5. **Data:**
   - Folder: `data`
   - Files:
     - `German_bank.csv`: The raw dataset.

6. **Reports:**
   - Folder: `reports`
   - Files:
     - `German Bank Loan - Report.pdf`: The final report summarizing the project, including an introduction, methodology, results, discussion, and conclusions.

7. **Requirements:**
   - File: `requirements.txt`
   - Description: Lists the required dependencies to run the project. Install with `pip install -r requirements.txt`. before run this command chane dir to requirements.txt fle location

8. **Instructions for Reproducibility:**
   - File: `reproducibility_instructions.md`
   - Description: Provides step-by-step instructions on how to reproduce the project's workflow and regenerate the final report.

## How to Run:

1. Clone the repository: `git clone https://github.com/PrasanthGubbala/MS-in-Information-Science-Machine-Learning.git`
2. Checkout to dev branch: `git checkout dev`
2. Navigate to the Course3 and Assignment6: `cd Course3/Assignment6/`
2. Again navigate to the project directory: `cd "German Bank Loan"`
3. Install dependencies: `pip install -r requirements.txt`
4. Follow the instructions in `reproducibility_instructions.md` to reproduce the project.
