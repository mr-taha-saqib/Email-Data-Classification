# Text Classification and Analysis  

## Steps  

### Step 0: Dataset Preparation  
- Use the labeled dataset from the last lab.  
- Split the data into training and validation sets using `train_test_split`.  
- Use the cleaned and pre-processed version of the data from the previous lab.  

---

### Step 1: Naive Bayes Classification  
- Implement the **Naive Bayes algorithm** for text classification from scratch.  
- Classify text into positive or negative classes using the implemented model.  

---

### Step 2: Logistic Regression Using scikit-learn  
- Use the `LogisticRegression` class from scikit-learn to create a text classification model.  
- Train the model using the dataset and evaluate its accuracy.  
- Plot the confusion matrix to visualize model performance.  

---

### Step 3: Handcrafted Features  
- Extract the following handcrafted features from the text data:  
  1. **Length of text**  
  2. **Average word length**  
  3. **Number of capital letters**  
  4. **Punctuation count**  
  5. **Number of numerals**  
  6. **Frequency of top words**  
- Use logistic regression on these handcrafted features for classification.  

---

### Step 4: Positive and Negative Word Count  
- Check each sentence in the dataset and count the number of positive and negative words.  
- Use the **`nltk` library**, specifically the `SentimentIntensityAnalyzer` class, for sentiment analysis.  
- Visualize the distribution of positive and negative word counts.  

---

### Step 5: Regularization in Python  
- Implement **L1 (Lasso)** and **L2 (Ridge)** regularization techniques.  
- Apply these techniques to the Logistic Regression model from Step 2 using the `LogisticRegression` class from scikit-learn.  
- **Key considerations for implementation:**  
  - Use the `'l1'` penalty with the `'saga'` solver for L1 regularization.  
  - Use the `'l2'` penalty for L2 regularization (compatible with most solvers).  
  - Adjust the **C parameter** (inverse of regularization strength) to balance overfitting and underfitting.  
  - Evaluate model performance for different C values to find the optimal parameter configuration.  

---
