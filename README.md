# README.md

## Overview
This study analyzes the impact of missing values on machine learning models, focusing on three mechanisms: 

- **MCAR** (Missing Completely at Random)

- **MAR** (Missing at Random)

- **MNAR** (Missing Not at Random)

Various imputation strategies are evaluated to determine their effect on model performance across datasets.


## Objectives
- Understand missing data mechanisms.
- Evaluate imputation strategies (mean, median, KNN, MICE).
- Assess the influence on Model Performance.
- Estimate predictive accuracy,

## Methodology
- **Language/Environment:** Python, Jupyter Notebook
- **Libraries:** pandas, numpy, scikit-learn, scipy, mdatagen
- **Workflow:**
1. Collecting and Preparing Datasets
2. Simulating Missing Values
3. Classifying with Missing Values using Random Forest
4. Handling Missing Values with Data Imputation: Statistical, KNN, MICE Imputation
5. Analysing Results

## Key Results
• The Random Forest Classifier performed well in the above cases, providing satisfactory performance handling missing values.
• The various missing mechanisms affected performance in different ways, but with the most negative impact observed for MNAR.
• Among the various imputation strategies, KNN imputation performed the best, particularly in cases of MCAR and MAR, proving to be the most robust method.
• Mean and Median imputation provided similar results. Current methods struggled in the MNAR scenario.
• Future research may explore more advanced techniques or hybrid approaches to further improvement.

## Usage
1. Clone the repository:
   ```bash
   git clone <https://github.com/mivhvl/MCAR-MAR-MNAR-Analysis.git>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Structure
- `data/`: Datasets
- `notebook.ipynb`: Analysis notebooks
- `RAPORT.pdf`: Analysis raport and conclusions

## Databases
- Autism Screening Adult Dataset: https://archive.ics.uci.edu/dataset/426/autism+screening+adult
- Mushroom Dataset: https://www.kaggle.com/datasets/prishasawhney/mushroom-dataset
- Occupancy Detection Dataset: https://archive.ics.uci.edu/dataset/357/occupancy+detection

## License
Licensed under the MIT License.

