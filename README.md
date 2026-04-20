# 🛳️ Titanic Survival Prediction 

 A **learning-focused project** where I explored the classic Titanic dataset, performed a mini EDA, preprocessed the data, and trained multiple ML models to predict passenger survival.  

---

## 📌 Project Overview  
The main goal of this project was to **learn the end-to-end ML pipeline** – from data exploration to model evaluation – using a well-known dataset.  

**Steps I followed:**  
1. **Mini EDA (Exploratory Data Analysis)**  
   - Checked basic statistics & distributions  
   - Explored correlations between features  
   - Visualized survival counts  

2. **Data Preprocessing**  
   - Removed unnecessary columns (like PassengerId, Name, Ticket, Cabin)  
   - Filled missing `Age` values using **Median Imputation**  
   - Encoded categorical features (`Sex`, `Embarked`) using **Label Encoding**  
   - Scaled numerical features with **Min-Max Scaling**  

3. **Model Training**  
   - Split data into train/test using `train_test_split`  
   - Trained multiple models:  
     - Logistic Regression  
     - Decision Tree  
     - Random Forest  
     - KNN  
     - SVM  
     - Naive Bayes  
   - **Random Forest** gave the best overall score 🎯  

---

##  Results  
| Model              | Performance (Accuracy) |
|-------------------|----------------------|
| Logistic Regression | 🔸 Decent |
| Decision Tree       | 🔸 Okay |
| Random Forest ✅   | ⭐ Best |
| KNN                | 🔸 Good |
| SVM                | 🔸 Good |
| Naive Bayes        | 🔸 Decent |

> **Winner:** Random Forest – balanced performance with good accuracy.  

---

## 🎯 Key Learnings  
- How to perform **basic EDA**  
- Handling **missing data** effectively  
- Feature scaling & encoding  
- Training and comparing multiple ML models  
- Evaluating model performance  

---

##  Future Improvements  
- Try feature engineering (combine or extract new features)  
- Use Hyperparameter tuning (GridSearchCV / RandomizedSearchCV)  
- Experiment with Ensemble techniques  

---

## 📂 Notebook  
You can check out the full implementation in my Jupyter Notebook in this repo.  
