# Payment Fraud Detection

## Description
This project demonstrates how to use machine learning for detecting fraudulent transactions. Using a dataset of online payment records, a logistic regression model is trained to classify transactions as fraud or non-fraud. The project includes data preprocessing, model training, and evaluation to achieve high accuracy in detecting fraudulent transactions.

---

## Project Workflow

### 1. Data Preprocessing
- Loaded the dataset directly from a public URL.
- Checked and confirmed no missing values in the dataset.
- Encoded categorical columns (e.g., transaction types) into numerical format for model compatibility.

### 2. Exploratory Data Analysis (EDA)
- Visualized the distribution of transaction types using a pie chart.
- Analyzed the correlation between features to understand their impact on fraud detection.

### 3. Model Training
- Used logistic regression for binary classification (fraud vs. non-fraud).
- Split the dataset into training (67%) and testing (33%) sets.
- Achieved high accuracy in detecting fraudulent transactions.

### 4. Model Evaluation
- Evaluated the model's performance using accuracy and a confusion matrix.
- Verified the model's ability to correctly identify fraudulent and non-fraudulent transactions.

---

## Usage

### Running the Project
1. Clone the repository:
    ```
    git clone https://github.com/yourusername/payment-fraud-detection.git
    ```
2. Install the required libraries:
    ```
    pip install -r requirements.txt
    ```
3. Run the project script:
    ```
    python payment_fraud_detection.py
    ```

---
    
## Example Input:
A new transaction with the following features:

- **Transaction Type**: Transfer  
- **Transaction Amount**: $9,000.60  
- **Sender's Old Balance**: $9,000.60  
- **Sender's New Balance**: $0.00  

---

## Example Output:
**Predicted Label**: Fraud  

---

## Results
- The logistic regression model achieved an accuracy of **100%** on the test set.
- **Confusion Matrix**:
  ```lua
  [[12753     0]
   [    0   190]]
  ```
  
---

## Dependencies
- Python 3.7+
- Pandas
- NumPy
- Scikit-learn

---

## Future Improvements
- Use advanced algorithms like Random Forest or Gradient Boosting for better fraud detection in imbalanced datasets.
- Add real-time transaction data streaming and fraud alerts.
- Deploy the model as a web or mobile application.

---

## License
This project is licensed under the **MIT License**.

---

## Acknowledgements
- **Dataset**: Sourced from [Aman Kharwal's GitHub Repository](https://github.com/amankharwal/Website-data/blob/master/payment_fraud.csv).
- **Inspiration**: Inspired by Aman Kharwal's article on fraud detection with machine learning.

