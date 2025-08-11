# Decision Trees and Random Forests - Heart Disease Classification

## Objective
The goal of this task is to learn and implement tree-based machine learning models for classification, visualize them, and compare their performance.

We use the **Heart Disease Dataset** to predict whether a patient has heart disease based on health-related features.

---

## Dataset
- **File:** `heart.csv`
- **Target variable:** `target` (1 = disease, 0 = no disease)
- The dataset contains multiple features such as age, sex, cholesterol, blood pressure, and more.

---

## Steps Implemented

1. **Import Libraries**
   - `pandas`, `numpy` for data handling
   - `matplotlib`, `seaborn` for visualization
   - `sklearn` for ML models and metrics
   - `graphviz` for tree visualization

2. **Load Dataset**
   - Dataset is uploaded manually (`heart.csv`).

3. **Data Exploration**
   - Checked dataset shape and previewed first few rows.

4. **Train/Test Split**
   - Used `train_test_split` with 80% training and 20% testing data.

5. **Decision Tree Classifier**
   - Trained a basic Decision Tree model.
   - Visualized the tree using `plot_tree`.

6. **Overfitting Analysis**
   - Limited tree depth (`max_depth=4`) to reduce overfitting.

7. **Random Forest Classifier**
   - Trained a Random Forest with 100 trees.
   - Compared accuracy with Decision Tree.

8. **Feature Importance**
   - Plotted feature importances from Random Forest.

9. **Cross-Validation**
   - Calculated mean accuracy scores using 5-fold cross-validation.

---

## Results

| Model                      | Test Accuracy | CV Accuracy (mean) |
|----------------------------|--------------|--------------------|
| Decision Tree (full)       | ~XX%         | ~XX%               |
| Decision Tree (max_depth=4)| ~XX%         | ~XX%               |
| Random Forest              | ~XX%         | ~XX%               |

*(Replace XX% with actual results after running the notebook.)*

---

## How to Run

1. Open the notebook in **Google Colab**.
2. Upload the `heart.csv` file when prompted.
3. Run all cells sequentially.
4. Review visualizations and performance metrics.

---

## Key Learnings
- Decision Trees can overfit easily without depth control.
- Random Forest generally improves accuracy by reducing variance.
- Feature importance helps in understanding which features impact predictions most.
- Cross-validation provides a more reliable estimate of model performance.

---
