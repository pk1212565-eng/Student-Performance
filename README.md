# 📊 Student Performance Prediction Using Machine Learning

Is project mein machine learning algorithms ka istemal karte hue students ki academic performance (**Performance Index**) ko predict kiya gaya hai. Isme baseline models (Linear Regression) aur advanced ensemble techniques (Random Forest & Gradient Boosting) ka comparison shamil hai.

## 🚀 Features & Project Structure

- **Data Preprocessing:** Auto missing values handling, categorical encoding (`LabelEncoder`), aur feature scaling (`StandardScaler`).
- **Multiple Model Evaluation:** Linear Regression ke sath sath Ensemble techniques ka comparison.
- **High Accuracy:** Gradient Boosting aur Random Forest models ke sath **>98% R² Score** achieve kiya gaya hai.

---

## 📂 Dataset Information

Dataset file ka naam `Student_Performance.csv` hai, jisme ye features shamil hain:
- **Hours Studied:** Parhai ke ghante.
- **Previous Scores:** Pehle ke exams ka score.
- **Extracurricular Activities:** Co-curricular activities mein hissa (Yes/No).
- **Sleep Hours:** Sone ka waqt.
- **Sample Question Papers Practiced:** Solve kiye gaye sample papers ki tadad.
- **Performance Index (Target):** Student ki final performance rating (10-100).

---

## 💻 Tech Stack & Libraries

Is project ko chalane ke liye aapko neeche di gayi libraries ki zaroorat hogi:
- **Language:** Python 3.x
- **Libraries:**
  - `pandas` (Data manipulation)
  - `numpy` (Numerical operations)
  - `scikit-learn` (Machine learning models & preprocessing)

---

## 🛠️ Installation & Setup

1. **Repository ko clone karein:**
   ```bash
   git clone https://github.com
   cd YOUR-REPOSITORY-NAME
   ```

2. **Required libraries install karein:**
   ```bash
   pip install pandas numpy scikit-learn
   ```

3. **Dataset place karein:**
   Apni `Student_Performance.csv` file ko project ke main folder (root directory) mein rakhein.

4. **Code run karein:**
   Jupyter Notebook open karein ya direct script run karein:
   ```bash
   python student_performance.py
   ```

---

## 📊 Model Performance Results

Models ko train karne ke baad milne wale R² Scores:

| Model | R² Score |
| :--- | :--- |
| 🌲 **Gradient Boosting Regressor** | **98.82%** |
| 🌲 **Random Forest Regressor** | **98.61%** |
| 📈 **Linear Regression** | *(Evaulated via MAE/RMSE)* |

---

## 🤝 Contribution
Agar aap is project mein mazeed improvements (jaise Hyperparameter Tuning ya Visualizations) add karna chahte hain, to zaroor **Pull Request** submit karein.
# Student-Performance
