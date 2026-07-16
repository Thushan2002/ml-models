# Student Score Predictor

A linear regression model that predicts a student's **Performance Index** (0-100) from study habits and background factors.

## Project 1 — Score Predictor

**Notebook:** [`models/project_1.ipynb`](models/project_1.ipynb)
**Data:** [`data/project_1.csv`](data/project_1.csv) (10,000 student records)

### Features used
- Hours Studied
- Previous Scores
- Extracurricular Activities (Yes/No, encoded as 1/0)
- Sleep Hours
- Sample Question Papers Practiced

### Approach
1. Load and explore the dataset (nulls, unique values, distributions).
2. Visualize relationships (e.g. Previous Scores vs Performance Index).
3. Encode `Extracurricular Activities` as binary.
4. Split data 80/20 into train/test sets (`random_state=42`).
5. Train a `LinearRegression` model with scikit-learn.
6. Evaluate using MAE, RMSE, and R².
7. Plot actual vs. predicted scores.
8. Predict the performance index for new, unseen students.

### Requirements
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
