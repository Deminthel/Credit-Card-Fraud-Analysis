
# Credit Card Fraud Detection and EDA Analysis

## 📌 Overview

This repository contains the work for my **Term Project** focused on **Exploratory Data Analysis (EDA)** and building a **Machine Learning model** to detect credit card fraud. The dataset used includes transaction data with a highly imbalanced distribution of fraudulent and legitimate transactions.

The project involves:
- Performing **EDA** to uncover patterns and insights from the data.
- Implementing a **web application** using Streamlit to interactively explore data and make predictions.
- Creating a **Jupyter Notebook** for in-depth analysis and visualization.
- Building and training a **Machine Learning Model** (Multi-Layer Perceptron) to classify transactions as fraudulent or legitimate.

---

## 📁 Repository Structure

```plaintext
├── .gitignore                     # Files to ignore in version control
├── App.py                         # Streamlit application for fraud detection
├── LICENSE                        # MIT license for the repository
├── README.md                      # Project documentation
├── credit-card-fraud-eda.ipynb    # Jupyter Notebook with EDA and analysis
├── credit_card/                   # Contains processed data or relevant resources
├── credit_card2/                  # Additional resources or files
├── credit_card3/                  # Additional resources or files
```

---

## 💻 Key Features

### 1. **Exploratory Data Analysis (EDA)**
- Visualizations of transaction distributions and trends.
- Analysis of the imbalanced class distribution.
- Insights into transaction amounts and time.

### 2. **Streamlit Web App**
- Interactive user interface for:
  - Viewing transaction data and distributions.
  - Predicting fraudulent transactions based on user inputs.
  - Visualizing Precision-Recall Curve and evaluation metrics.

### 3. **Machine Learning**
- Implemented a **Multi-Layer Perceptron (MLP)** model using TensorFlow and Keras.
- Data preprocessing includes scaling and train-test splitting.
- Evaluation using metrics such as **Precision-Recall Curve** and **Area Under Curve (AUC)**.

### 4. **Jupyter Notebook**
- Detailed EDA and visualization.
- Step-by-step walkthrough of data preprocessing and model development.

---

## 🚀 How to Run the Project

### Clone the Repository
```bash
git clone https://github.com/shoaib1522/Credit-Card-Fraud-Analysis.git
cd Credit-Card-Fraud-Analysis
```

### Prerequisites
- Install Python (>=3.8)
- Install required libraries:
  ```bash
  pip install -r requirements.txt
  ```

### Run the Streamlit App
```bash
streamlit run App.py
```

### Jupyter Notebook
- Open `credit-card-fraud-eda.ipynb` using Jupyter or any notebook editor.

---

## 🗂️ Dataset

The dataset used in this project contains transaction data from a Kaggle competition. The key features include:
- **Time**: Seconds elapsed between this transaction and the first transaction in the dataset.
- **Amount**: Transaction amount.
- **Class**: Target variable (1 = Fraud, 0 = Legitimate).

*Note*: Due to size constraints, the dataset file is not included in the repository. You can download it from [Kaggle's Credit Card Fraud Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud).

---

## 📊 Visualizations and Insights
Here are some key visualizations included in the project:
- **Class Distribution**: Highlights the imbalance between legitimate and fraudulent transactions.
- **Transaction Amount Distribution**: Visualizes the distribution of transaction amounts.
- **Precision-Recall Curve**: Demonstrates the model's performance in detecting fraud.

---

## 🛠️ Tools and Libraries
- **Python**
- **Streamlit**
- **Pandas**
- **NumPy**
- **Matplotlib & Seaborn**
- **TensorFlow & Keras**
- **Scikit-learn**

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 📢 Author

Developed by **Shoaib Mughal** as part of the **Data Science Term Project**.

Feel free to explore, contribute, and provide feedback! If you have any questions or suggestions, feel free to reach out.

---
