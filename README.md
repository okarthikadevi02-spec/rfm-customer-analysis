# RFM Analysis and Customer Segmentation using Machine Learning

## Project Overview
This project focuses on analyzing customer purchasing behavior using RFM (Recency, Frequency, Monetary) analysis and cohort analysis. It also applies machine learning techniques to predict high-value customers.

---

## Dataset Information
The dataset contains 541,909 transactions with the following features:

- InvoiceNo: Invoice number
- StockCode: Product code
- Description: Product description
- Quantity: Quantity purchased
- InvoiceDate: Date of transaction
- UnitPrice: Price per unit
- CustomerID: Unique customer ID
- Country: Customer location

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Workflow
1. Data Cleaning
2. Exploratory Data Analysis
3. RFM Feature Engineering
4. Customer Segmentation
5. Cohort Analysis
6. Machine Learning Model Building
7. Model Evaluation

---

## Data Preprocessing
- Removed missing CustomerID values
- Filtered negative quantity and price
- Converted date columns
- Created TotalAmount feature

---

## RFM Analysis
- Recency: Days since last purchase
- Frequency: Number of transactions
- Monetary: Total spending

---

## Cohort Analysis
Cohort analysis is used to analyze customer retention over time based on their first purchase month.

---

## Machine Learning Models
- Logistic Regression
- Random Forest Classifier

---

## Model Evaluation
- Accuracy Score
- Classification Report
- Confusion Matrix

---

## Key Insights
- Customers with higher frequency and monetary value are high-value customers
- Recency plays an important role in customer behavior
- Cohort analysis helps understand retention trends

---

## Conclusion
The project successfully segments customers and predicts high-value customers using machine learning. It provides valuable insights into customer behavior and business strategy.

---

## Future Improvements
- Use advanced models such as XGBoost
- Perform hyperparameter tuning
- Deploy the model

---

## Project Structure
rfm-analysis-ml/
│
├── rfm_analysis.ipynb
├── OnlineRetail.csv
├── README.md

---

## Author
Karthikadevi O

---

## Note
This project is for educational purposes and demonstrates customer analytics techniques.
