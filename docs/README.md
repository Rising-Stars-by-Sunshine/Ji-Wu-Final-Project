# Documentation for House Price Prediction Project

## Overview
This document provides detailed instructions on how to execute the code, understand the project structure, and replicate the analysis. The project integrates structured data with AI-generated textual descriptions to enhance house price prediction models.

## Contents
- **Data Preprocessing:** Description of how raw data is cleaned, transformed, and feature engineered.
- **Modeling:** Details on the supervised learning approach (e.g., Random Forest, XGBoost) and the incorporation of text features using TF-IDF and BERT embeddings.
- **Evaluation:** Instructions on model validation using RMSE, MAE, and R² metrics, along with cross-validation and hyperparameter tuning.
- **Causal Inference (Supplementary):** Brief overview of the regression discontinuity design (RD) applied to assess policy impacts.
- **Code Execution:** Step-by-step instructions on running scripts and notebooks.
- **Dependencies:** A list of libraries and tools used in the project.

## How to Run the Code
1. **Set Up Environment:**
   - Install Python 3.x and set up a virtual environment.
   - Install all dependencies using:  
     `pip install -r ../requirements.txt`
2. **Data Preparation:**
   - The raw data is stored in the `data/` directory. Follow the instructions in the `data/README.md` for preprocessing steps.
3. **Running Notebooks:**
   - Open the notebooks in the `code/` directory using Jupyter Notebook or JupyterLab.
   - Execute cells sequentially to reproduce the analysis.
4. **Generating Visualizations:**
   - Visualizations will be saved automatically to the `visualizations/` folder.
5. **Reviewing Results:**
   - Model evaluation results and causal inference outcomes are discussed in the final sections of the notebooks.
