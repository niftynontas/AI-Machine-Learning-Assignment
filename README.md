# AI-Machine-Learning-Assignment
🎓 AI for SDG 4: Predicting Student Exam Performance using Machine Learning. This project uses a Linear Regression model to forecast math scores based on student background data, promoting inclusive and quality education for all. 📊

# 🎓 Predicting Student Performance — An AI Solution for SDG 4

## 🌍 UN Goal: Quality Education (SDG 4)
This project uses **Machine Learning** to predict student exam performance (math score) using background data like gender, parental education, and reading/writing scores.

By identifying patterns in student achievement, this project supports **SDG 4: Ensure inclusive and equitable quality education and promote lifelong learning opportunities for all.**

---

## 📁 Dataset
- Source: Kaggle — *Students Performance in Exams*
- Records: 1000 students
- Features include:
  - Gender
  - Race/ethnicity
  - Parental level of education
  - Lunch type
  - Test preparation course
  - Reading and writing scores

---

## ⚙️ Tools & Technologies
- Python
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `seaborn`, `matplotlib`, `scikit-learn`

---

## 🧠 Machine Learning Model
- **Model Used**: Linear Regression
- **Target Variable**: `math score`
- **Features Used**: All other columns (encoded where necessary)
- **Train/Test Split**: 80/20

---

## 📊 Results

### ✅ R² Score: 0.88
### ✅ Mean Squared Error (MSE): 29.10 

The model explains 88% of the variation in math scores and predicts scores with an average error of about 5 points, demonstrating its reliable ability to estimate student performance based on background data.

---

## 📈 Visualizations & Findings

### 📊 1. **Math Score Distribution**

- Most students scored between 60 and 80 in math.
- The distribution is slightly skewed, suggesting fewer students perform at the very high or very low ends.

---

### 📊 2. **Actual vs Predicted Math Scores**
- The scatter plot shows that **predicted scores are close to the real scores**.
- Points fall along a diagonal line → model predictions are strong and reliable.

---

### 📊 3. **Feature Importance**
- The strongest positive contributors to math score were:
  - **Reading score**
  - **Writing score**
- Other features like test preparation and lunch type also had visible effects.
- This insight shows that **language skills** and **access to resources** are strongly linked to math performance.

---

## 💬 Conclusion
This project shows that AI can contribute meaningfully to **education equity** by identifying students who may need academic support. It demonstrates how **data science aligns with global development goals** like SDG 4.

---

## 📂 Files Included
- assignment 2.ipynb`: Core notebook with training, testing, and plots
- screenshots: Visualization outputs for results
- csv file-'StudentsPerformance.csv'

---

## 🔗 Author
👩🏽‍💻 Created by : Nontando Myoli 
📚 For the PLP Academy – Week 2 Assignment  
🌍 Theme: **Machine Learning Meets the UN SDGs**


