# Sonar Rock vs Mine Classification

##  Project Overview
This project builds a **machine learning classification system** to identify whether an object detected by sonar signals is a **Rock (R)** or a **Mine (M)**. The model is trained using the classic **Sonar Dataset**, where each sample contains 60 numerical features extracted from sonar signals.

The goal is to demonstrate a complete **end-to-end ML workflow** including data loading, exploration, preprocessing, model training, evaluation, and prediction.

---

##  Dataset Information
- **Dataset Name:** Sonar Dataset
- **Total Features:** 60 numerical attributes
- **Target Column:** Column 60
  - `R` → Rock
  - `M` → Mine
- **File Used:** `sonar data.csv`

Each row represents sonar signal energy values at different frequencies.

---

##  Machine Learning Model
- **Algorithm Used:** Logistic Regression
- **Library:** `scikit-learn`
- **Problem Type:** Binary Classification

Logistic Regression is chosen for its simplicity and effectiveness in binary classification problems.

---

##  Technologies & Libraries Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

##  Project Workflow
1. Import required libraries
2. Load the dataset
3. Exploratory Data Analysis (EDA)
   - Shape, size, statistical summary
   - Class distribution (Rock vs Mine)
4. Separate features and target labels
5. Split data into training and testing sets
6. Train Logistic Regression model
7. Evaluate model performance
   - Accuracy (training & testing)
   - Confusion Matrix visualization
8. Build a predictive system for new input data

---

##  Model Evaluation
- **Metrics Used:**
  - Accuracy Score
  - Confusion Matrix

## Accuracy Results

   - Training Accuracy: 82.89%
   - Testing Accuracy: 61.90%

The model performance is evaluated on both training and testing datasets to check for underfitting or overfitting.

---

##  Predictive System
The notebook includes a simple interactive prediction system where users can:
- Input 60 feature values (comma-separated)
- Get a prediction:
  - `Rock`
  - `Mine`

---

## ▶ How to Run the Project
1. Clone the repository
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Install dependencies
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```
3. Open the notebook
   ```bash
   jupyter notebook
   ```
4. Run all cells in sequence

---

##  Project Structure
```
├── sonar data.csv
├── sonar_rock_vs_mine.ipynb
├── README.md
```

---
---

##  Author
**Anjani Kumar Pokhrel**  
Aspiring Data Scientist  

---

 If you find this project useful, feel free to star the repository!