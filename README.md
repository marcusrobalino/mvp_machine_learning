# 🎓 Machine Learning: Predição de Churn em Clientes de Telecom

Este projeto foi desenvolvido como MVP da disciplina de **Machine Learning** na pós-graduação em **Ciência de Dados e Analytics da PUC-Rio**.

O objetivo do trabalho é prever o **churn (cancelamento de contrato)** de clientes de telecom, a partir de dados contratuais, demográficos e de serviços.  
A solução busca identificar clientes em maior risco de saída, permitindo a priorização de ações de retenção.

---

## 🧠 Problema investigado
O churn é um dos maiores desafios em empresas de telecomunicações.  
Manter clientes é significativamente mais barato do que adquirir novos, mas exige a capacidade de prever **quem tem maior risco de cancelamento**.  
Este projeto aplica algoritmos de Machine Learning para **classificar clientes** e apoiar estratégias de retenção.

---

## 📊 Etapas realizadas
- Definição do problema de negócio  
- Exploração e análise estrutural do dataset  
- Pré-processamento dos dados (imputação, normalização, encoding)  
- Estabelecimento de baselines (DummyClassifier, Logistic Regression)  
- Treinamento de modelos candidatos (Random Forest, Gradient Boosting)  
- Tuning de hiperparâmetros com validação cruzada (GridSearchCV)  
- Avaliação em conjunto de teste com métricas diversas (ROC-AUC, F1, Recall, Accuracy)  
- Interpretação e explicabilidade (feature importance, permutation importance)  
- Definição de limiar ótimo de decisão para priorizar Recall  
- Conclusões e recomendações de negócio  

---

## 🔍 Dataset utilizado
- **Nome:** Telco Customer Churn  
- **Fonte:** Kaggle (https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
- **Repositório GitHub:** [link do dataset raw utilizado](https://raw.githubusercontent.com/marcusrobalino/mvp_machine_learning/refs/heads/main/telco_churn_dataset.csv)  
- **Amostra:** ~7.000 clientes de uma operadora de telecom  
- **Variável target:** `Churn` (binária: sim/não)  

---

## 📦 Tecnologias e bibliotecas
- Python 3.12  
- Google Colab (execução em ambiente gratuito)  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn (pré-processamento, modelagem, avaliação)  

---

## ▶️ Executar no Google Colab
Clique no botão abaixo para abrir o notebook diretamente no Colab:

[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1YNnk7MLDyVKlqct2kGOnlQHJoVhaw6xc?usp=sharing)

---

## 👤 Autor
Marcus Vinicius Robalino de Almeida  
Pós-graduação em Ciência de Dados e Analytics – PUC-Rio  

---

## 📚 Referências
- Dataset original: Kaggle – Telco Customer Churn  
- Documentação oficial: [scikit-learn](https://scikit-learn.org/stable/), [pandas](https://pandas.pydata.org/), [numpy](https://numpy.org/), [matplotlib](https://matplotlib.org/), [seaborn](https://seaborn.pydata.org/)  
- Material didático da disciplina *Machine Learning – PUC-Rio*  
