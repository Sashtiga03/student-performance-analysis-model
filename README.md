# Student Performance Analysis

## Overview

This project analyzes student performance using a dataset and implements linear regression models with interaction terms to understand how various factors influence academic outcomes. The analysis covers data exploration, model fitting, and performance evaluation.

## Project Structure

- `data/`: Contains the dataset (`student_performance.csv`).
- `notebooks/`: Jupyter notebook (`student_performance_analysis.ipynb`) for data exploration, model fitting, and diagnostic analysis.
- `results/`: Includes generated plots and model summaries.

## Dataset

- **Filename**: `student_performance.csv`
- **Description**: A dataset containing information on student study hours, previous scores, extracurricular activities, sleep hours, and performance index.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/student-performance-analysis.git
2. Navigate to the project directory:
   ```bash
   cd student-performance-analysis
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
## Usage

1. **Data Exploration**:
   - Open `student_performance_analysis.ipynb` in Jupyter Notebook.
   - Load the dataset and review summary statistics and visualizations.

2. **Model Fitting**:
   - Fit linear regression models with and without interaction terms.
   - Compare model summaries to evaluate the impact of interaction terms.

3. **Diagnostics**:
   - Plot residuals vs. predicted values and Q-Q plots to assess model assumptions.
   - Identify outliers using diagnostic plots such as leverage vs. Cook's distance.

4. **Run the Notebook**:
   - Ensure you have the necessary packages installed. Commonly required packages include:
     - `numpy`
     - `pandas`
     - `matplotlib`
     - `seaborn`
     - `statsmodels`
   - Install packages using pip:
     ```bash
     pip install numpy pandas matplotlib seaborn statsmodels
     ```
   - Start Jupyter Notebook and open `student_performance_analysis.ipynb`:
     ```bash
     jupyter notebook
     ```

5. **Results**:
   - Follow the notebook to interpret model outputs and diagnostic plots to understand the effects of predictors and interactions on student performance.

