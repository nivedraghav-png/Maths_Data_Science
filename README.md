# Mathematics for Data Science
## Linear Algebra and Probability

### Project Overview
This project focuses on applying Linear Algebra and Probability concepts to the Red Wine Quality Dataset using Python.

The assignment covers data cleaning, vector extraction, covariance matrix calculation, eigenvalue and eigenvector decomposition, and probability distribution analysis.

### Project Files

- `Maths_LinearAlgebra_Probability.ipynb` – Jupyter Notebook containing Python code, outputs, and explanations.
- `winequality-red.csv` – Red Wine Quality Dataset.
- `README.md` – Project documentation.

### Dataset Information

- **Dataset:** Red Wine Quality Dataset
- **Total Records:** 1,599
- **Total Columns:** 12
- **Target Variable:** Quality
- **Features Used:** Alcohol, Citric Acid, Density

### Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

### Installation

Install the required Python libraries:

```bash
pip install pandas numpy notebook
```

### How to Run

1. Download or clone this repository.
2. Keep the Jupyter Notebook and CSV dataset in the same folder.
3. Open Jupyter Notebook.
4. Open `Maths_LinearAlgebra_Probability.ipynb`.
5. Run all cells sequentially.

### Assignment Tasks

**Question 1: Data Loading and Cleaning**

Load the dataset and handle missing values by replacing null values with the mean of the respective columns.

**Question 2: Vector Extraction**

Extract the following columns as vectors:
- Alcohol
- Citric Acid

**Question 3: Covariance Matrix**

Select Alcohol and Density as two features and calculate their covariance matrix using NumPy.

**Question 4: Eigenvalue and Eigenvector Decomposition**

Perform eigen decomposition on the covariance matrix and identify the two eigenvalues and their corresponding eigenvectors.

**Question 5: Wine Quality Distribution**

Identify the most common wine quality score and interpret the distribution of wine quality scores.

### Key Results

| Description | Result |
|---|---|
| Total Records | 1,599 |
| Total Columns | 12 |
| Missing Values | 0 |
| Alcohol Vector Length | 1,599 |
| Citric Acid Vector Length | 1,599 |
| Selected Features | Alcohol and Density |
| First Eigenvalue | 1.13564827 |
| Second Eigenvalue | 0.000002685 |
| Most Common Wine Quality | 5 |
| Frequency | 681 |

### Conclusion

This assignment demonstrates the practical application of Linear Algebra and Probability concepts using Python.

Through this analysis, we explored data cleaning, vector operations, covariance matrices, eigen decomposition, and the distribution of wine quality scores.

The analysis shows that quality score 5 is the most common among the 1,599 red wine samples.

---
**Project:** Mathematics and Statistics Assignment 1  
**Topic:** Linear Algebra and Probability  
**Language:** Python
