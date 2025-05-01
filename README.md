# FakeNewsDetectionUsingLogisticRegressio

### ✅ *Workflow for the Project*  
(as seen in the provided Colab link)

---

#### *Title:*  
*Fake News Detection using Logistic Regression*

---

### ⚙ *Workflow Steps*

1. *Importing Required Libraries*  
   - Libraries such as numpy, pandas, sklearn, and nltk are imported.
   - Purpose: To handle data manipulation, machine learning, and natural language processing.

2. *Loading the Dataset*  
   - Dataset is loaded using pandas.read_csv.
   - It contains news headlines labeled as real or fake.

3. *Data Cleaning and Preprocessing*  
   - Removing null values.
   - Dropping unnecessary columns.
   - Converting all text to lowercase.
   - Removing punctuation and stopwords.
   - Lemmatization (converting words to their base forms).

4. *Splitting the Dataset*

5. Text Vectorization*  
   - Using *TF-IDF Vectorizer* to convert text data into numerical format suitable for ML models.

6. *Model Training*  
   - Logistic Regression model is trained on the training data using LogisticRegression() from sklearn.

7. *Prediction and Evaluation*  
   - Model is evaluated using:
     - Accuracy
     - Confusion Matrix
     - Classification Report

8. *User Input Prediction (Optional)*  
   - Code may include a way to manually input a news headline and check if it’s real or fake.


