# 📧 Email Spam Detection using Machine Learning

## 📌 Overview

This project focuses on building a machine learning model to classify emails as **Spam** or **Ham (Not Spam)**.
Different algorithms were applied and compared to select the best-performing model.

---

##  Dataset

* The dataset contains labeled emails:

  * **Spam (1)**
  * **Ham (0)**
* Text data was preprocessed before training.

---

## ⚙️ Preprocessing Steps

* Lowercasing text
* Removing punctuation
* Removing stopwords
* Tokenization
* TF-IDF Vectorization

---

## 🔀 Train-Test Split

* Data split into:

  * **80% Training**
  * **20% Testing**

---

## 🤖 Models Used

The following machine learning models were trained and evaluated:

1. Naive Bayes
2. Logistic Regression
3. Support Vector Machine (SVM)

---

## 📊 Model Evaluation
## 📊 Model Performance Comparison

The chart below shows Precision, Recall, and F1 Score for all models:

![Performance Chart](Email%20Spam%20Classifier/performance%20chart.png)
### 🔹 Naive Bayes

* Precision: 1.00
* Recall: 0.846
* F1 Score: 0.917

Confusion Matrix:

```
[[965   0]
 [ 23 127]]
```

---

### 🔹 Logistic Regression

* Precision: 0.918
* Recall: 0.893
* F1 Score: 0.905

Confusion Matrix:

```
[[953  12]
 [ 16 134]]
```

---

### 🔹 Support Vector Machine (SVM)

* Precision: 0.945
* Recall: 0.913
* F1 Score: 0.929

Confusion Matrix:

```
[[957   8]
 [ 13 137]]
```

---

## 🏆 Final Model Selection

Support Vector Machine (SVM) was selected as the final model because:

* It achieved the highest **F1 Score**
* It maintained a good balance between **Precision and Recall**
* It minimized both types of errors

---

## 📈 Key Insights

* High **Precision** ensures fewer normal emails are marked as spam
* High **Recall** ensures maximum spam emails are detected
* SVM provided the best trade-off between both

---

## 🧠 Technologies Used

* Python
* Scikit-learn
* Pandas
* NumPy

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/spam-detection.git

# Install dependencies
pip install -r requirements.txt

# Run the project
python main.py
```

---

## 📌 Conclusion

This project demonstrates how machine learning models can effectively detect spam emails.
Among all models, **SVM performed the best** and is recommended for deployment.

---

## ✨ Author

Zainab Bibi
