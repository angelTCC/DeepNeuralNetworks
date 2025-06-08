
# Modeling Energy & Agriculture Data with Random Forest, XGBoost, and Deep Neural Networks

## 🎯 Project Overview

This project aims to build a strong foundation in both **classical machine learning** and **deep learning** by training, tuning, and comparing widely used models on tabular datasets related to energy consumption and agricultural production.

The models included reflect realistic, real-world choices for tabular data:

- **Random Forest:** Robust and interpretable classical ensemble model  
- **XGBoost:** State-of-the-art gradient boosting algorithm widely used in industry  
- **Deep Neural Networks (DNN):** Feedforward networks to explore deep learning on tabular data  

Through this project, you will:

- Learn data preprocessing techniques tailored for both classical and deep models  
- Train and evaluate classical ML models and deep neural networks  
- Compare performance, training time, and practical trade-offs  
- Understand when deep learning adds value versus classical methods for tabular data  
- Build reproducible and modular code to support experimentation and deployment  

## Data

https://datosabiertos.gob.pe/dataset/consumo-de-energ%C3%ADa-el%C3%A9ctrica-de-los-clientes-de-adinelsa-setiembre-2024/resource/0cbf3a92

https://datosabiertos.gob.pe/dataset/producci%C3%B3n-agr%C3%ADcola-2018-2020-en-la-regi%C3%B3n-de-cusco

mercado de productos(negocio local), gasto publico (condicion economica local), cooperativa(personas trabajando en elsector)

classification of the best suited place to buy market and decided in what secto aboput agriculture invest. this is classification problem.

in regresio problem i use to to predict bases on the classification the future develop of the invest. also predict production in cuso, but this production can be stacionary, so study time seris befores

https://www.datosabiertos.gob.pe/dataset/presupuesto-y-ejecuci%C3%B3n-de-gasto


https://www.datosabiertos.gob.pe/dataset/censo-nacional-de-mercado-de-abastos-cenama-2016-ministerio-de-la-producci%C3%B3n-produce

https://www.datosabiertos.gob.pe/dataset/cooperativas-nivel-nacional-ministerio-de-la-produccion-produce


## ⚙️ Project Components

### 1. Data Preprocessing

- Cleaning and preparing the datasets  
- Handling missing values and outliers  
- Encoding categorical features (one-hot encoding, embeddings)  
- Feature scaling and normalization  
- Splitting data into training, validation, and test sets  

### 2. Classical Machine Learning Models

- **Random Forest** implementation with hyperparameter tuning  
- **XGBoost** training with early stopping and grid search  
- Baseline models such as Logistic Regression or Linear Regression where applicable  

### 3. Deep Learning Model

- Simple feedforward deep neural network designed for tabular input  
- Techniques like batch normalization, dropout, and learning rate scheduling  
- Experimentation with model architecture (depth, width, activation functions)  

### 4. Evaluation & Comparison

- Metrics: accuracy, F1-score, RMSE, MAE, depending on the prediction task  
- Analysis of training time and resource usage  
- Practical considerations: interpretability, scalability, deployment readiness  


## 📁 Project Structure

```

dl\_vs\_classical\_ml/
├── data/
│   ├── energy\_data.csv
│   ├── agriculture\_data.csv
│   └── preprocessing.py           # Data cleaning and feature engineering scripts
│
├── models/
│   ├── classical\_models.py        # Random Forest, XGBoost, and baseline classical models
│   ├── deep\_learning\_model.py     # Deep Neural Network training and evaluation
│   └── utils.py                   # Utility functions for metrics and plotting
│
├── notebooks/
│   └── analysis.ipynb             # Exploratory data analysis and results visualization
│
├── requirements.txt               # Python dependencies
├── README.md
└── .gitignore

```

## 🛠️ How to Use

1. Install the required libraries:

   ```bash
   pip install -r requirements.txt
```

2. Run data preprocessing:

   ```bash
   python data/preprocessing.py
   ```

3. Train classical ML models:

   ```bash
   python models/classical_models.py
   ```

4. Train deep learning model:

   ```bash
   python models/deep_learning_model.py
   ```

5. Analyze and compare results:

   ```bash
   jupyter notebook notebooks/analysis.ipynb
   ```

---

## 📈 Learning Outcomes

* Practical experience in training and tuning classical ML and DL models on real tabular datasets
* Understanding of the strengths and limitations of different modeling approaches
* Skills in data preprocessing for diverse model types
* Ability to evaluate model performance and resource efficiency critically
* Foundation for building deployable machine learning solutions

---

## 📄 License

MIT License © 2025 Your Name
