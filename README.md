# Iris Flower Classification

## Project overview
This beginner-friendly machine learning project predicts the species of an Iris flower using four measurements: sepal length, sepal width, petal length, and petal width. It compares two classification models: Decision Tree and K-Nearest Neighbors (KNN).

## Dataset
The Iris dataset is included with scikit-learn and contains 150 samples, four numeric features, and three species.

Dataset documentation: https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_iris.html

## Requirements
- Python 3.9 or later recommended
- Jupyter Notebook
- pandas
- NumPy
- scikit-learn
- Matplotlib
- Seaborn

## Setup instructions

1. Download or clone this repository.
2. Open a terminal in the project folder.
3. (Optional but recommended) Create and activate a virtual environment.
4. Install dependencies:

   ```bash
   python -m pip install notebook pandas numpy scikit-learn matplotlib seaborn
   ```

5. Start Jupyter:

   ```bash
   jupyter notebook
   ```

6. Open `iris_flower_classification.ipynb` and choose **Run All**.

## Workflow
1. Load the Iris dataset.
2. Inspect the data and check for missing values.
3. Separate features and target.
4. Split data into training and testing sets.
5. Train a Decision Tree and a scaled KNN pipeline.
6. Compare accuracy and display confusion matrices.
7. Try a sample prediction and write a conclusion based on the actual outputs.

## Results
Run the notebook to generate the model accuracy scores, classification reports, and confusion matrices. The best-performing model is determined from the test-set accuracy printed by the notebook. Results should be reported from the notebook output rather than guessed in advance.

## Conclusion
The project demonstrates a complete introductory classification workflow and compares two models using the same held-out test set. A single train/test split provides an initial comparison; further validation could be used for a more robust assessment.

## Files
- `iris_flower_classification.ipynb` — complete notebook with code, visualisations, evaluation, and conclusion.
- `README.md` — project overview and setup instructions.
