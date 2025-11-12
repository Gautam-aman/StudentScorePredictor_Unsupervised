# 🎓 Student Score Predictor (Machine Learning Project)

### 🧠 Predict Student Performance using Logistic Regression

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)
![Pandas](https://img.shields.io/badge/Library-Pandas-yellow)
![Scikit-learn](https://img.shields.io/badge/ML-Scikit--learn-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📘 **Project Overview**

The **Student Score Predictor** is a **machine learning project** designed to predict whether a student will **pass or fail** based on key academic and behavioral features such as:

- ⏰ **Study hours per day**  
- 🎯 **Attendance percentage**  
- 📚 **Past academic performance**  
- 🌐 **Internet usage (non-academic)**  
- 😴 **Sleep duration per day**

Using these inputs, a **Logistic Regression model** predicts whether a student is likely to pass or fail, helping educators and mentors identify students who may need academic support.

---

## ⚙️ **Tech Stack**

| Component | Technology |
|------------|-------------|
| **Programming Language** | Python 🐍 |
| **Libraries** | pandas, numpy, scikit-learn, seaborn, matplotlib |
| **Algorithm** | Logistic Regression |
| **Dataset** | Custom-created dummy dataset (`student_score_dataset.csv`) |
| **IDE / Environment** | Jupyter Notebook or PyCharm / VS Code |

---

## 📊 **Dataset Information**

**File:** `student_score_dataset.csv`

| Column | Description |
|--------|--------------|
| `study_hours` | Daily study hours |
| `attendance` | Attendance percentage |
| `past_score` | Average of previous test marks |
| `internet_usage` | Hours spent online (non-academic) |
| `sleep_hours` | Average sleep hours |
| `passed` | 1 = Pass, 0 = Fail |

---

## 🔍 **Machine Learning Workflow**

1. **Data Collection:**  
   Load dataset (`student_score_dataset.csv`) into a pandas DataFrame.

2. **Data Preprocessing:**  
   - Handle missing data (if any)  
   - Scale features using `StandardScaler`  
   - Split data into training and test sets

3. **Model Training:**  
   Train a **Logistic Regression** model using scikit-learn.

4. **Model Evaluation:**  
   - Accuracy, Precision, Recall, F1-score  
   - Confusion Matrix (visualized with Seaborn heatmap)

5. **User Prediction Interface:**  
   The script accepts user inputs (study hours, attendance, etc.) and predicts **Pass/Fail** in real time.

---

## 📈 **Results**

- Achieved **~85–90% accuracy** on the dummy dataset.  
- Clear visualization of pass/fail prediction using a confusion matrix heatmap.  
- Allows **real-time user input prediction** directly from the terminal.

---

## 🚀 **How to Run**

1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/StudentScorePredictor.git
   cd StudentScorePredictor
   ```

2. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```

3. Run the program  
   ```bash
   python main.py
   ```

---

## 💡 **Key Learnings**

- Understanding of **data preprocessing and scaling**  
- Implementation of **supervised classification (Logistic Regression)**  
- Interpreting **confusion matrix and classification reports**  
- Creating user-interactive ML applications  

---

## 🤝 **Contributing**

Contributions, issues, and feature requests are welcome!  
Feel free to fork this repo and submit a pull request.

---



---

## 🧑‍💻 **Author**

**Aman Gautam**   
🌐 [GitHub Profile](https://github.com/your-username)  
✉️ Contact: amangautam2128@gmail.com
