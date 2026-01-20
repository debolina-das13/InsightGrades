# InsightGrades – Student Performance Prediction

**InsightGrades** is a Python-based machine learning project built in **Google Colab** to predict a student’s semester GTU marks using academic and attendance data. By analyzing features like lecture and lab test marks, mid-term evaluations, attendance, and internal assessments, it provides actionable insights for students, teachers, and institutions.

---

## Features
- Predict student GTU marks using machine learning models
- Analyze trends and correlations in student performance data
- Visualize performance patterns with intuitive plots
- Fully implemented in Google Colab – no setup required

---

## Dataset
- The project uses the dataset: `testing_final_data_csv.csv`  
- Contains features like:
  - `sem_present_count` – Number of classes attended
  - `sem_absent_count` – Number of classes missed
  - `sem_eval_lec_test_1_mark` – Lecture Test 1 marks
  - `sem_eval_lab_test_1_mark` – Lab Test 1 marks
  - `semester_evaluation_mid_mark` – Mid-term evaluation marks
  - `sem_eval_lec_test_2_mark` – Lecture Test 2 marks
  - `sem_eval_lab_test_2_mark` – Lab Test 2 marks
  - `semester_evaluation_pre_gtu_mark` – Pre-GTU evaluation marks
  - `semester_evaluation_internal_mark` – Internal evaluation marks
  - `semester_evaluation_gtu_mark` – Final GTU marks (target)

---

## Tech Stack
- Python 3.x
- Google Colab
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

---

## How to Run
1. Open the project notebook in Google Colab:  
   [Open in Colab](#) *(replace # with your Colab link)*

2. Upload `testing_final_data_csv.csv` to Colab if not already uploaded

3. Run the notebook cells to:
   - Load and preprocess data  
   - Explore data and visualize trends  
   - Train ML models and evaluate performance  
   - Predict student GTU marks

---

## Workflow
1. **Data Loading & Preprocessing** – Clean missing values, select relevant features  
2. **Exploratory Data Analysis (EDA)** – Analyze feature correlations and distributions  
3. **Model Training** – Linear Regression, Decision Tree, Random Forest  
4. **Evaluation** – MAE, MSE, R² Score  
5. **Visualization** – Scatter plots of actual vs predicted GTU marks

---

## Future Enhancements
- Predict grade categories (A, B, C…) instead of raw marks  
- Include more features like online activity or participation  
- Build a Streamlit dashboard for real-time predictions  

---

