# Student Performance Research
This is a research project of Machine Learning about Student Performance based on internal and external factors that can affect it from the beginning of the semester to the middle of the semester to help them avoid bad grades at the end of the semester and i also want to compare conventional models and autoML which is rarely done in educational research.

## 📊 Dataset and Feature
The dataset that used in this research contains 5000 rows of student's data with feature which divided into two main categories : 
* **Internal Academic Factors :** Midterm Score, Assignments Average, Quizzes Average, Participation Score
* **Eksternal Academic Factors :** Study Hours per Week, Sleep Hours per Night, Age, Stress Level (Scale 1-10), Extracurricular Activities, Internet Access at Home, Parent Education Level, Family Income Level, Gender, and Department

## ⚙️ Model & Experimental Scenario
This research compares 5 classification models : 
1.  **XGBoost**
2.  **Random Forest**
3.  **AutoGluon** (AutoML)
4.  **FLAML** (AutoML)
5.  **PyCaret** (AutoML)

**Research Scenario:**
*   **Scenario 1 (4 classes - B, C, D, F):** Testing the model's robustness to extreme class imbalance (Class F minority). *Random Over-Sampling* (ROS) is strictly applied only to the *training set* to prevent *data leakage*.
*   **Skenario 2 (3 Kelas - B, C, D):** Evaluasi performa model ketika kelas minoritas (F) dihapus dari skenario untuk melihat perubahan *threshold* keputusan model.
