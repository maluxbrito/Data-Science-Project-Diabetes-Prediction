# 🧠 Diabetes Prediction — Data Science Project
---

## 📌 Overview

Projeto de Ciência de Dados desenvolvido em Python com foco em análise exploratória, pré-processamento e modelagem supervisionada para previsão de diabetes utilizando o dataset **Pima Indians Diabetes**.

O projeto aborda desde a compreensão e limpeza dos dados até treinamento, validação e otimização de modelos de Machine Learning.

---

## 🎯 Objectivos

- Realizar Análise Exploratória de Dados (EDA)
- Identificar padrões e correlações relevantes
- Tratar valores ausentes e outliers
- Aplicar técnicas de pré-processamento
- Comparar algoritmos supervisionados
- Avaliar desempenho dos modelos

---

## 🛠️ Technologies

![Python](https://img.shields.io/badge/python-111111?style=for-the-badge&logo=python)
![Jupyter](https://img.shields.io/badge/jupyter-111111?style=for-the-badge&logo=jupyter)
![Pandas](https://img.shields.io/badge/pandas-111111?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/numpy-111111?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/matplotlib-111111?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/seaborn-111111?style=for-the-badge)
![Scikit Learn](https://img.shields.io/badge/scikit--learn-111111?style=for-the-badge&logo=scikit-learn)

---

## 📊 Exploratory Data Analysis

Durante a análise exploratória foram investigados:

- Distribuição das variáveis
- Assimetria e presença de outliers
- Correlação entre atributos
- Valores inconsistentes e ausentes
- Relação entre variáveis e diagnóstico de diabetes

### Visualizations

<p align="center">
  <img width="400" src="images/heatmap.png">
  <img width="400" src="images/boxplot.png">
</p>

---

## ⚙️ Data Preprocessing

Técnicas aplicadas no pipeline de pré-processamento:

- Tratamento de valores ausentes
- Remoção e análise de outliers
- Padronização com `StandardScaler`
- Normalização com `MinMaxScaler`
- Redução de dimensionalidade com PCA

---

## 🤖 Machine Learning Models

Modelos supervisionados utilizados:

- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Decision Tree**

Cada modelo foi treinado e avaliado para comparar desempenho, capacidade de generalização e adequação ao problema de classificação do dataset Pima Indians Diabetes.

---


### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score

---

## 🏆 Results

| Model | Accuracy | Precision | Recall | F1-Score |
|---|---|---|---|---|
| Logistic Regression | 0.78 | 0.67 | 0.60 | 0.64 |
| KNN | 0.76 | 0.60 | 0.69 | 0.64 |
| Decision Tree | 0.75 | 0.58 | 0.71 | 0.64 |

---

## 💡 Main Insights

- A variável **Glucose** apresentou forte relação com o diagnóstico de diabetes
- Algumas variáveis continham valores inconsistentes iguais a zero
- PCA reduziu dimensionalidade mantendo boa variância explicada
- Modelos treinados com dados escalados apresentaram melhor desempenho

---

## 📂 Project Structure

```bash
├── data/
├── notebooks/
├── images/
├── README.md
```

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook
```

---

## 👩🏻‍💻 Author
Malu Brito

**Malu Brito**  
Computer Science @ UFBA
