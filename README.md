# 💰 Financial Fraud Detection  

This project focuses on detecting fraudulent financial transactions using machine learning techniques. The goal is to build an accurate and efficient model that can identify fraudulent transactions and help prevent financial losses.  

## 📌 Project Overview  

Financial fraud is a significant challenge in the banking and financial sectors. This project applies advanced machine learning algorithms to analyze transaction data and classify whether a transaction is fraudulent.  

The dataset consists of transaction details, including amounts, account balances, and recipient information. The project involves:  

✔️ **Data Preprocessing** – Cleaning and normalizing transaction data  
✔️ **Feature Engineering** – Extracting meaningful insights from raw data  
✔️ **Handling Imbalanced Data** – Using techniques like **SMOTE** to balance the dataset  
✔️ **Feature Selection** – Applying **chi-square tests** to select relevant features  
✔️ **Model Training & Evaluation** – Implementing and comparing models like **CNN, KNN, and RNN**  
✔️ **Performance Metrics** – Evaluating accuracy, precision, recall, and F1-score  

## 🏆 Key Results  

🔹 The **CNN model** outperformed other models with an accuracy of **99.72%**  
🔹 Feature selection improved the model’s efficiency by reducing redundant data  
🔹 Handling imbalanced data led to better fraud detection rates  

## 🛠️ Technologies Used  

🔹 Python  
🔹 Pandas, NumPy, Scikit-learn  
🔹 TensorFlow/Keras (for CNN model)  
🔹 Matplotlib & Seaborn (for data visualization)  

## 📂 Dataset  

The dataset includes transaction details such as:  
- `step` – Time unit of transaction  
- `type` – Type of transaction (e.g., CASH_OUT, TRANSFER)  
- `amount` – Transaction amount  
- `oldbalanceOrg`, `newbalanceOrig` – Sender’s balance before & after the transaction  
- `oldbalanceDest`, `newbalanceDest` – Receiver’s balance before & after the transaction  
- `isFraud` – Label indicating whether the transaction is fraudulent  

## 📈 Model Comparison  

| Model  | Accuracy  | Precision | Recall | F1-Score |  
|--------|----------|-----------|--------|----------|  
| KNN    | 95.3%    | 94.8%     | 91.2%  | 93.0%    |  
| RNN    | 98.1%    | 97.5%     | 95.6%  | 96.5%    |  
| **CNN** | **99.72%** | **99.5%** | **99.1%** | **99.3%** |  

## License

This project is licensed under the MIT License 

## 📢 Conclusion  

This project demonstrates how machine learning can significantly enhance financial fraud detection by identifying suspicious transactions with high accuracy.  

