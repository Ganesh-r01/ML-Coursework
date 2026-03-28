Spam Email Detection

Description

This project aims to classify emails as **Spam** or **Not Spam (Ham)** using Machine Learning techniques. The model analyzes the content of emails and predicts whether they are malicious or legitimate.

## Dataset

* **Source:** Kaggle – Spam Mails Dataset (venky73)
* **Description:**
  The dataset contains labeled email messages with:

  * `text`: Email content
  * `label`: Spam or Ham
  * `label_num`: Numeric representation (0 = Ham, 1 = Spam)

## Steps Performed

1. **Data Cleaning**

   * Removed unnecessary columns (e.g., `Unnamed: 0`)
   * Handled missing values

2. **Exploratory Data Analysis**

   * Checked distribution of spam vs ham emails
   * Reviewed sample messages

3. **Feature Extraction**

   * Used **TF-IDF Vectorization** to convert text into numerical features

4. **Model Building**

   * Applied **Logistic Regression** for classification
   * Split dataset into training and testing sets

5. **Evaluation**

   * Measured performance using:

     * Accuracy
     * Precision
     * Recall
     * F1-score
   * Generated confusion matrix

Results

* Achieved high accuracy (~95–99%)
* Model successfully distinguishes spam emails using keyword patterns
* Spam emails often contain words like *“free”, “win”, “urgent”*

Tools Used

* Python
* Pandas, NumPy
* Scikit-learn
* TF-IDF Vectorizer

Conclusion

The project demonstrates that machine learning models can effectively detect spam emails. Logistic Regression combined with TF-IDF provides strong performance for text classification tasks.

Author

Ganesh
