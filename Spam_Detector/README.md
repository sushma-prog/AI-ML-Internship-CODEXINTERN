# 📧 Spam Mail Detector

This project builds a machine learning model to classify SMS messages as **Spam** or **Ham (Not Spam)**.

---

## 📊 Dataset
- **Source:** SMS Spam Collection dataset (UCI Repository).
- **Size:** ~5,500 messages.
- **Target:** `spam` or `ham`.

---

## ⚙️ Process
1. **Load Data**
   - Loaded messages and labels (`ham`, `spam`).

2. **Preprocessing**
   - Lowercasing text.
   - Removing special characters & stopwords.
   - Tokenization.
   - Joined tokens back to clean text.

3. **Feature Extraction**
   - Converted text into numeric features using **Bag of Words (BoW)**.

4. **Model Training**
   - Algorithms used:
     - **Naive Bayes**
     - **Logistic Regression**

5. **Evaluation**
   - Accuracy Score
   - Precision Score
   - F1 Score

---

## 📈 Results
- **Logistic Regression** performed best with:
  - Accuracy ≈ 97–98%
  - High precision & recall for spam detection.

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- NLTK  

---

## 📂 File
- `task2.ipynb` → Jupyter Notebook with full code & results.

