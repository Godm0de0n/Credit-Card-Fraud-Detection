# 📌 Project Overview

This project focuses on **Credit Card Fraud Detection** using machine learning algorithms. The goal is to build a model that can accurately identify fraudulent transactions, minimizing false positives and ensuring customer security.

## 📊 Dataset

The dataset used for this project is sourced from Kaggle:
[Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)

The dataset contains transactions made by credit cards in September 2013 by European cardholders. It has 284,807 transactions, out of which 492 are fraudulent.

## 🛠 Dependencies

Ensure you have the following dependencies installed:

- Pandas
- NumPy
- Scikit-learn


## 🚀 Installation

1. Clone the repository:
```bash
git clone <repository_link>
```
2. Navigate to the project directory:
```bash
cd Credit_Card_Fraud_Detection
```
3. Launch Jupyter Notebook:
```bash
jupyter notebook
```
4. Open `Credit_Card_Fraud_Detection.ipynb`.

## 🔄 Data Processing

1. Load the dataset using Pandas.
2. Check the data and info
3. Take 1000 random Legit Transaction and all 492 Fraudulent Transaction
4. Create a new dataframe with them as primary data

## 💡 Model Training

- Used algorithms:
  - Logistic Regression
  - Random Forest
- Split data into training and testing sets (75-25 split).

## 📈 Model Evaluation

- Metrics used:
  - Accuracy **(Both model has ~94% accuracy)**

## 🔥 Future Enhancements

- Implement deep learning models like LSTM for sequential data analysis.
- Deploy the model using Flask for real-time fraud detection.
- Integrate with cloud platforms for scalability.

## 🤝 Contribution

Contributions are welcome! Feel free to fork the repo and submit a pull request.

## 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

