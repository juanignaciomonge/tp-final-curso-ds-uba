# Churn Prediction Project

## Project Overview

This project is a final assignment for my data science course, aiming to create a model that predicts customer churn. The objective is to explore the data, engineer features, train different models, and evaluate them to determine the best-performing model for predicting churn.

## Dataset

The dataset includes information on customer behavior and attributes, which can be used to analyze and predict customer churn. The data was provided in a CSV file, and a separate XLSX file contains additional metadata describing the dataset fields.

* **Data files**:
  * `data/raw/Modelo_Clasificacion_Dataset.csv`: Original dataset
  * `data/raw/Modelo_Clasificacion_Diccionario_de_Datos.xlsx`: Description of dataset fields and data types
* **Additional file**:
  * `docs/TRABAJO_CLASIFICACION.pdf`: PDF containing the main task of the assignment

## Project Structure

Here’s an overview of the folder structure in this repository:

```
uba-assessment-churn-prediction/
├── data/
│   ├── raw/                   # Original data files (e.g., CSV and XLSX files)
│   ├── processed/             # Cleaned and preprocessed data files
│   └── external/              # Additional external data sources
│
├── notebooks/                 # Jupyter notebooks for data exploration, EDA, etc.
│   ├── 01_data_exploration.ipynb
│   └── 02_feature_engineering.ipynb
│
├── src/                       # Source code for the project
│   ├── data/                  # Scripts to load and process data
│   ├── features/              # Scripts to create and transform features
│   ├── models/                # Scripts to train, evaluate, and save models
│   └── visualization/         # Scripts to create visualizations and plots
│
├── models/                    # Serialized models (e.g., saved model files)
│
├── reports/                   # Folder for reports
│   └── figures/               # Figures and images to include in the report
│
├── docs/                      # Documentation files
│   └── assessment_task.pdf    # Task description for the final assignment
│
├── tests/                     # Unit tests for the code in src/
│
├── README.md                  # Project overview and setup instructions
├── requirements.txt           # List of dependencies
└── .gitignore                 # Files and folders to ignore in Git
```

## Setup Instructions

1. **Clone the repository**:
```
git clone https://github.com/juanignaciomonge/uba-assessment-churn-prediction.git
cd uba-assessment-churn-prediction
```
2. **Install dependencies**:
```
pip install -r requirements.txt
```
3. **Data**: Place `customer_data.csv` and `data_description.xlsx` in the `data/raw/` folder (these files are not included in the repository).
4. **Run Notebooks**:
    * Open Jupyter Notebook and run the notebooks in the `notebooks/` folder for exploratory data analysis and feature engineering.
5. **Training and Evaluation**:
    * Run scripts in `src/models/` to train and evaluate different models.

## Project Workflow

1. **Data Exploration**: Use `notebooks/01_data_exploration.ipynb` to explore the dataset, understand the distribution of features, and identify missing values.
2. **Feature Engineering**: In `notebooks/02_feature_engineering.ipynb`, transform raw data into features for model training.
3. **Model Training**: Use the scripts in `src/models/` to train various models and evaluate their performance.
4. **Evaluation**: Compare model performance and choose the best model for deployment.

## Results

The final report with model evaluation results can be found in the `reports/` folder. Key findings and model metrics will be summarized here after analysis is complete.

## Dependencies

List of dependencies is provided in `requirements.txt`. To install, run:
```
pip install -r requirements.txt
```

## License

This project is for educational purposes as part of a data science course.

