# Reproducibility Instructions

## Project Setup
1. Clone the repository:
   ```
   git clone https://github.com/PrasanthGubbala/MS-in-Information-Science-Machine-Learning.git
   git checkout dev
   cd Course3/Assignment6/
   cd "German Bank Loan"
   ```

2. Create a virtual environment (optional but recommended or if you have jupyter notebook run models directly there becuase I'm not added jupyter notebook libraries into the requirements.txt):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install project dependencies:
   ```
   pip install -r requirements.txt
   ```

## Data Exploration and Preprocessing
1. Run the Jupyter notebook for data exploration and preprocessing:
   ```
   jupyter notebook 1_data_exploration.ipynb
   ```

   - Follow the instructions in the notebook to explore and preprocess the dataset.

2. Save the cleaned and splitted data using `%store` magic command.


## Data Manipulation, Wrangling and Visualization
1. Execute the Jupyter notebook for Manipulation, Wrangling and Visualization:
   ```
   jupyter notebook 2_manipulate_wrangle_visualize.ipynb
   ```

   - This notebook contains code for Manipulation, Wrangling and Visualization.

2. Ensure that the required datasets are available under /data/ folder dataset: German_bank.csv

3. Analyze Visualizations and take decicion for model selection

## Machine Learning Models
1. Execute the Jupyter notebook for training machine learning models:
   ```
   jupyter notebook 3_model_building.ipynb
   ```

   - This notebook contains code for training and evaluating multiple machine learning models.

2. Ensure that the required datasets are loaded using `%store -r`.
   ```train and test data will loaded from stored variables so run 1_data_exploration.ipynb before 3_model_building.ipynb```

3. Observe the model evaluation results, and trained models will be saved in the project directory.



## Instructions for Model Evaluation

### Execution Steps
1. Run the Jupyter notebook for model evaluation:
   ```
   jupyter notebook 3_model_building.ipynb
   ```
   - This notebook contains the code for training and evaluating multiple machine learning models.

2. Ensure that the required datasets are loaded using `%store -r`.
   ```python
   # Load data from stored variables
   %store -r X_train X_test y_train y_test
   ```
   - Make sure to run the data exploration notebook (`1_data_exploration.ipynb`) before executing the model-building notebook.

3. Observe the model evaluation results within the notebook, including accuracy, precision, recall, F1-score, and confusion matrices.

4. Review the final results section in the notebook for a comprehensive summary of key findings, observations, and recommendations based on the model evaluations.

5. Save the trained models, which are automatically stored in the project directory, for future use.



By following these steps, you can reproduce the model evaluation workflow, ensuring consistent and replicable results. The comprehensive documentation and use of stored variables facilitate a seamless reproducibility process for anyone revisiting or extending this project.