# PCA Formative Assignment: African Economic Analysis

This repository contains an implementation of Principal Component Analysis (PCA) from scratch using NumPy. The goal is to analyze the `ObservationData_lavlqce.csv` dataset, which contains economic indicators for various African countries, and reduce its dimensionality while retaining 95% of the variance.

## Files
* `PCA__Formative_Kabasinga_Arsene.ipynb`: The main Jupyter Notebook containing the code, analysis, and visualizations.
* `ObservationData_lavlqce.csv`: The dataset used for the analysis.

## Installation & Usage Instructions

To run this notebook locally, please follow these steps:

### 1. Prerequisites
Ensure you have Python installed along with the following libraries:
* NumPy
* Pandas
* Matplotlib

You can install them using pip:
```
pip install numpy pandas matplotlib
```

### 2. Running the Code
   #### 1. Clone this repository:

```
git clone https://github.com/KABASINGAarsene/PCA-Formative-Assignment.git
```

 ### 2. Navigate to the directory and open the notebook:
```
jupyter notebook PCA__Formative_Kabasinga_Arsene.ipynb
```
### 3. Important:
Ensure the dataset ObservationData_lavlqce.csv is in the same folder as the notebook.


### 4. Run all cells to reproduce the PCA steps, Scree Plot, and Benchmarking results.

### Key Features
* Data Cleaning: Handling missing values and non-numeric columns.

* PCA Implementation: Manual calculation of Covariance Matrix and Eigendecomposition using NumPy.

* Dynamic Selection: The script dynamically calculates that 13 components are required to explain 95% of the variance.

* Visualization: Comparison of Original Data vs. PCA Reduced Data.
