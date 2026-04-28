# Formula 1 Finish Position Prediction

Course project in machine learning focused on predicting a Formula 1 driver's finishing position using historical race data.

## About the Project

This project uses the Formula 1 dataset from Kaggle. The main goal is to prepare the data, compare several machine learning models, and implement a custom neural network for predicting the target variable `position_num`.

The project is organized as three sequential notebooks:

1. `01_data_preparation.ipynb` - data loading, cleaning, table merging, and basic EDA.
2. `02_model_comparison.ipynb` - comparison of classical ML models and baseline PyTorch models.
3. `03_custom_neural_network.ipynb` - implementation of a custom neural network and comparison with a baseline.

## Repository Structure

```text
kursovaya_f1/
├── 01_data_preparation.ipynb
├── 02_model_comparison.ipynb
├── 03_custom_neural_network.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## Dataset

Data source:

- Kaggle Formula 1 World Championship Dataset:
  [https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020)

To run the project, download the source `.csv` files from the dataset and place them next to the notebooks.

After completing stage 1, the following final dataset is created:

- `f1_final_dataset.csv`

This file is used in stages 2 and 3.

## Technologies Used

- Python
- Jupyter Notebook / Google Colab
- `pandas`, `numpy`
- `matplotlib`, `seaborn`, `plotly`
- `scikit-learn`
- `torch`
- optionally: `xgboost`, `lightgbm`, `catboost`

## How to Run

1. Install dependencies:

```bash
pip install -r requirements.txt
```

2. Download the Formula 1 dataset from Kaggle.

3. Open and run the notebooks in order:

```text
01_data_preparation.ipynb
02_model_comparison.ipynb
03_custom_neural_network.ipynb
```

## Project Outcome

The project demonstrates the full workflow for solving the task:

- data preparation and analysis;
- feature engineering;
- model comparison;
- custom neural network training;
- evaluation using the main regression metrics.

## Note

This repository is an academic course project, so the main logic, experiments, and results are contained directly in the notebooks.
