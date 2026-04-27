# Impact of Macroeconomic Factors on Housing Prices

## Project Overview
This project explores the relationship between local property features and broader economic trends. Using the classic California Housing dataset and simulated macroeconomic indicators, we built predictive models to determine how factors like interest rates, inflation, and unemployment influence property values. 

This project was developed as a final exam for the Data Science course (April 2026), adhering to strict technical and academic guidelines.

---

## Key Objectives
* **Data Consolidation**: Successfully merged two independent data sources (housing data and macroeconomic data).
* **Mathematical Rigor**: Implemented and explained the theory behind Multiple Linear Regression and Random Forest models.
* **Predictive Modeling**: Compared a baseline linear model with an advanced non-linear model to improve accuracy.
* **Technical Quality**: Followed best practices for clean code, documentation, and version control.

---

## Data Sources
1.  **Housing Data**: California Housing Dataset (Property-level features like median income, house age, and location).
2.  **Macroeconomic Data**: Simulated historical trends for Interest Rates, Inflation, and Unemployment (1990–2010).

---

## Technical Stack
* **Language**: Python
* **Environment**: Jupyter Notebook (`.ipynb`)
* **Core Libraries**: 
    * **Pandas**: Data manipulation and merging.
    * **NumPy**: Numerical operations and data simulation.
    * **Matplotlib**: Data visualization and EDA.
    * **Scikit-learn**: Model training, splitting, and evaluation.

---

## Project Structure
* `project.ipynb`: The primary deliverable containing English analysis, LaTeX math formulas, and Python code.
* `housing.csv`: The property dataset.
* `macro.csv`: The generated macroeconomic dataset.
* `requirements.txt`: List of dependencies for project reproducibility.

---

## Mathematical Foundation
The project utilizes the **Multiple Linear Regression** hypothesis to model price predictions:
$$h_\theta(x) = \theta_0 + \theta_1 x_1 + \dots + \theta_n x_n$$

Performance is validated using **Root Mean Squared Error (RMSE)** to measure the average prediction error in dollars:
$$RMSE = \sqrt{\frac{1}{n}\sum_{i=1}^{n}(y_i - \hat{y}_i)^2}$$

---

## Compliance & Integrity
* **Meaningful Commits**: This repository contains at least 15 meaningful commits documenting the incremental development process.
* **Academic Integrity**: All sources are documented, and the work is original. No plagiarism was involved.
* **Functional Code**: All code cells in the notebook are verified to run without errors.
* **Legal Compliance**: This project complies with the law in Bulgaria as of the exam date (April 2026).
