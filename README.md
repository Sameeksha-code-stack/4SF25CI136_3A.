# Airline Passenger Satisfaction – Milestone 1

## Overview

This project is part of **Milestone 1 – CIE: Data Transformation, Null Value Handling, Insight Generation, and Visualization**.

The objective is to analyze airline passenger data using Python. The project focuses on understanding the dataset, handling missing values, performing data transformations, generating useful insights, and creating visualizations.

## Dataset

The project uses the Airline Passenger Satisfaction dataset (`train.csv`).

The dataset contains passenger information such as:

- Gender
- Customer Type
- Age
- Type of Travel
- Class
- Flight Distance
- Inflight Service Ratings
- Departure Delay
- Arrival Delay
- Passenger Satisfaction

## Operations Performed

1. **Data Reading:** Loaded the CSV dataset using Pandas.
2. **Data Understanding:** Examined the dataset shape, columns, data types, and statistical information.
3. **Data Cleaning:** Identified missing values and duplicate records.
4. **Null Value Handling:** Used mean imputation to handle missing numerical values.
5. **Data Transformation:** Removed unnecessary columns and created a new `Total Delay` column.
6. **Insight Generation:** Analyzed passenger satisfaction, age, flight distance, travel class, and customer type.
7. **Data Sorting:** Identified the top 10 longest flights.
8. **Data Visualization:** Used Matplotlib and Seaborn to create different graphs and plots.

## Visualizations

The following visualizations were created:

- Passenger Satisfaction Count Plot
- Gender Distribution Count Plot
- Flight Distance Histogram
- Age Distribution Histogram
- Correlation Heatmap
- Satisfaction vs Flight Distance Box Plot
- Age vs Flight Distance Scatter Plot

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Files Included

- `MILE_STONE.ipynb` – Jupyter Notebook containing the complete analysis.
- `train.csv` – Dataset used for the project.
- `README.md` – Project documentation.

## How to Run

1. Download or clone this repository.
2. Keep `train.csv` and `MILE_STONE.ipynb` in the same folder.
3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

4. Open the notebook using Jupyter Notebook.
5. Run all cells to view the analysis and visualizations.

---

**Repository:** 4SF25CI136_3A.  
**Project:** Milestone 1 – Data Transformation and Visualization
