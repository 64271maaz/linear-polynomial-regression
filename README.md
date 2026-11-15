# Linear and Polynomial Regression

This project implements **Linear Regression** and **Polynomial Regression** on a salary dataset from Kaggle. The work is done in a Google Colab notebook and includes data exploration, model training, evaluation, and comparison.

## Dataset

- **Name:** Salary Dataset (Simple Linear Regression)
- - **File:** `Salary_dataset.csv`
- **Features:** `YearsExperience` (years of work experience)
- **Target:** `Salary` (annual salary)

## Models Implemented

1. **Linear Regression**
   - Computed manually using the closed-form least-squares formula (slope and intercept).
   - Verified with scikit-learn's `LinearRegression`.
2. **Polynomial Regression**
   - Degrees 2, 3, 4, and 5 using `PolynomialFeatures` with `LinearRegression`.
   - Compared to find the degree with the best generalization.

## Methodology

1. Load the dataset and check for missing values.
2. Visualize the relationship between experience and salary.
3. Split the data into training (80%) and testing (20%) sets with `random_state=42`.
4. Train each model on the training set.
5. Evaluate on the test set using MSE, RMSE, and R².
6. Compare the models and select the best one.

## Results

| Model                  | MSE   | RMSE  | R²     |
|------------------------|-------|-------|--------|
| Linear                 | <...> | <...> | <...>  |
| Polynomial (degree 2)  | <...> | <...> | <...>  |
| Polynomial (degree 3)  | <...> | <...> | <...>  |
| Polynomial (degree 4)  | <...> | <...> | <...>  |
| Polynomial (degree 5)  | <...> | <...> | <...>  |

*Replace the `<...>` values with the output from your notebook.*

## Conclusion

<Write which model performed best and why. For example: "Linear regression performed well because the relationship between experience and salary is approximately linear. Higher-degree polynomial models did not improve test performance and showed signs of overfitting.">

## Requirements

- Python 3.x
- numpy
- pandas
- matplotlib
- scikit-learn

Install with:

```bash
pip install numpy pandas matplotlib scikit-learn
```

## How to Run

**Option 1: Google Colab**
1. Open the notebook in Colab using the link below.
2. Upload `kaggle.json` (or the dataset CSV) when prompted.
3. Run all cells in order (**Runtime → Run all**).

**Option 2: Local machine**
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   cd <your-repo>
   ```
2. Place `Salary_dataset.csv` in the project folder.
3. Open the notebook with Jupyter or run it as a script:
   ```bash
   jupyter notebook
   ```

## Repository Structure

```
├── linear_polynomial_regression.ipynb   # Main Colab notebook
├── Salary_dataset.csv                   # Dataset (optional if downloaded via Kaggle API)
└── README.md                            # Project documentation
```

## Colab Notebook

<Paste your Colab link here, e.g. https://colab.research.google.com/drive/...>

## Author

- **Name:** <Your Name>
- **Roll No.:** <Your Roll Number>
- **Course:** <Course Name>
