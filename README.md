# Predictive-Analytics-Lab-Exam-2

# Classification using Logistic Regression with Decision Boundary

This project demonstrates a complete **machine learning workflow** including:

* Exploratory Data Analysis (EDA)
* Data preprocessing
* Building a **Logistic Regression** classification model
* Visualizing the **decision boundary**
* Evaluating model performance

---

## Dataset

The dataset contains:

* **Feature1** – Input variable
* **Feature2** – Input variable
* **Target** – Output class label (Yes/No or 0/1)

---

## Exploratory Data Analysis (EDA)

The following steps were performed:

* Checked dataset structure and summary statistics
* Handled missing values (removed rows with missing target values)
* Visualized feature relationships using scatter plots
* Generated correlation heatmap for numerical features

---

## Data Preprocessing

* Selected relevant features (`Feature1`, `Feature2`)
* Converted categorical target values (Yes/No → 1/0)
* Split dataset into training and testing sets
* Applied **feature scaling** using StandardScaler

---

## Model Building

* Used **Logistic Regression** for classification
* Trained the model on training data
* Predicted outcomes on test data

---

## Decision Boundary Visualization

* Created a mesh grid
* Plotted classification regions
* Visualized how the model separates different classes

---

## Model Evaluation

The model was evaluated using:

* **Accuracy Score**
* **Confusion Matrix**
* **Classification Report (Precision, Recall, F1-score)**

---

## How to Run

1. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

2. Place your dataset file in the project folder

3. Update dataset path in the script:

   ```python
   df = pd.read_csv("your_dataset.csv")
   ```

4. Run the Python script or Jupyter Notebook

---

## Key Learnings

* Importance of EDA before model building
* Handling missing and categorical data
* Logistic Regression fundamentals
* Visual interpretation using decision boundaries

---

## Conclusion

The Logistic Regression model successfully classifies the data and the decision boundary provides a clear visualization of how the model separates different classes.

---

## Author

* PAVITHRA K M

---
