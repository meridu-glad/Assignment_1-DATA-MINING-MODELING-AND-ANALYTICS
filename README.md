# DSC8307: Data Mining, Modeling and Analytics
## Advent 2026 Semester Assignment 1

**Programme:** Master of Science in Data Science and Analytics  
**Institution:** Uganda Christian University (UCU)  
**Department:** Computing and Technology  
**Academic Year:** 2026  
**Semester:** Advent 2026  


## 1. Project Overview

This repository contains the two projects completed as part of the DSC8307 Data Mining, Modeling and Analytics course assignment.

The assignment applies data mining, statistical analysis and machine learning techniques to two real-world prediction problems. The projects involve exploratory data analysis, data preparation, baseline development, model selection, model evaluation and interpretation of findings.

The two projects are:

### Project 1: Bank Marketing – Term Deposit Subscription Prediction

**Objective:** Develop and evaluate machine learning models to predict whether a bank customer will subscribe to a term deposit following a telephone marketing campaign.

The analysis covers:
- Exploratory data analysis and understanding of the dataset.
- Data cleaning and preprocessing.
- Class distribution and majority-class baseline.
- Selection and comparison of suitable machine learning algorithms.
- Model evaluation and comparison.
- Decision threshold selection.
- Interpretation of the trade-off between unnecessary marketing calls and missed potential subscribers.

**Dataset:** `bank-additional-full.csv`

### Project 2: Concrete Compressive Strength Prediction

**Objective:** Develop predictive models to estimate concrete compressive strength based on the composition of concrete mixtures and curing age.

The analysis covers:
- Exploratory data analysis.
- Data cleaning and preparation.
- Mean-prediction baseline.
- Comparison of linear and non-linear modelling approaches.
- Model performance evaluation.
- Residual analysis and identification of weaknesses in model predictions.
- Interpretation of the relationship between cement content and concrete strength, including the limitations of predictive associations for real-world decisions.

**Dataset:** `Concrete_Data.csv`

---

## 2. Repository Structure

The repository is organised as follows:

```text
DSC8307-Data-Mining-Assignment/
│
├── Project_1.ipynb
│
├── Project2.ipynb
│
├── requirements.txt
│
├── README.md
│
└── data/
    ├── bank-additional-full.csv
    └── Concrete_Data.csv
```

**File descriptions:**

- `Project_1.ipynb`: Jupyter Notebook containing the Bank Marketing prediction project.
- `Project2.ipynb`: Jupyter Notebook containing the Concrete Compressive Strength prediction project.
- `requirements.txt`: Lists the Python libraries required to execute both projects.
- `README.md`: Provides an overview of the assignment, repository structure and instructions for running the notebooks.
- `data/`: Contains the datasets used for the analysis, if included in the repository.

---

## 3. Technologies and Libraries Used

The projects were developed using Python and Jupyter Notebook.

The following libraries are required:

| Library | Purpose |
|---|---|
| NumPy | Numerical computations |
| Pandas | Data manipulation and analysis |
| SciPy | Scientific computations |
| Matplotlib | Data visualization |
| Seaborn | Statistical data visualization |
| Scikit-learn | Machine learning and model evaluation |
| Statsmodels | Statistical modelling |
| XGBoost | Gradient boosting modelling |
| Notebook | Jupyter Notebook environment |

---

## 4. Installation and Setup

### Step 1: Clone the repository

Clone the public GitHub repository to your local computer:

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

Navigate to the project directory:

```bash
cd YOUR-REPOSITORY
```

### Step 2: Install the dependencies

Ensure Python is installed, then execute:

```bash
pip install -r requirements.txt
```

This installs the Python libraries required for both projects.

### Step 3: Launch Jupyter Notebook

Run:

```bash
jupyter notebook
```

Open the relevant notebook to execute the analysis.

---

## 5. Running the Projects

The projects are provided as separate Jupyter Notebooks.

1. Open `Project_1.ipynb` to execute the Bank Marketing prediction analysis.
2. Open `Project2.ipynb` to execute the Concrete Compressive Strength prediction analysis.
3. Execute the notebook cells sequentially, from the first cell to the last cell.

**Important:** Ensure that the datasets are available in the locations specified in the notebooks before executing the analysis.

Both notebooks should execute from beginning to end after installing the dependencies and configuring the dataset paths.

---

## 6. Reproducibility and Documentation

To promote reproducibility, the repository includes:

- Complete Python Jupyter Notebooks for both projects.
- A dependency file (`requirements.txt`) specifying the required Python libraries.
- Documented data preparation and analytical procedures.
- Model evaluation and comparison.
- Visualisations and interpretation of analytical findings.

The notebooks are organised to allow another user to follow the analytical process and reproduce the results.

-

## 8. Author

**Student:** Eridu Moses  
**Programme:** Master of Science in Data Science and Analytics  
**Institution:** Uganda Christian University  
**Course:** DSC8307 – Data Mining, Modeling and Analytics  
**Semester:** Advent 2026



