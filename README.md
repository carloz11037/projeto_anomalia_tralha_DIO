📌 README.md
# 🚨 Detecção de Anomalias em Transações Financeiras

## 📊 Sobre o projeto

Este projeto tem como objetivo identificar transações anômalas (possíveis fraudes) utilizando técnicas de Machine Learning.

Foram aplicados modelos supervisionados para classificação, com foco em desempenho, equilíbrio de classes e interpretabilidade dos resultados.

---

## 🎯 Objetivo

Desenvolver um sistema capaz de:
- Identificar padrões normais e anômalos em transações
- Reduzir falsos negativos (fraudes não detectadas)
- Avaliar o desempenho de diferentes modelos de Machine Learning

---

## 🧠 Abordagem utilizada

O projeto segue um pipeline típico de Data Science:

1. 📥 Coleta e leitura dos dados  
2. 🧹 Tratamento e limpeza dos dados  
3. ⚖️ Balanceamento de classes (SMOTE)  
4. 📊 Análise exploratória dos dados (EDA)  
5. 🤖 Treinamento de modelos de Machine Learning  
6. 📈 Avaliação com métricas (Precision, Recall, F1-score)  
7. 🔍 Interpretação dos resultados (ex: SHAP)

---

## ⚙️ Tecnologias utilizadas

- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- XGBoost / RandomForest / logistic Regression
- SHAP (interpretação de modelos)
- Imbalanced-learn (SMOTE)

---

## 📊 Modelos testados

- Random Forest Classifier
- XGBoost Classifier

---

## 📈 Métricas utilizadas

- Accuracy
- Precision
- Recall
- F1-score
- Matriz de Confusão

---

📌 Resultados

O modelo final apresentou bom desempenho na detecção de anomalias, com foco principal em:

Alta capacidade de identificar fraudes (Recall)
Equilíbrio entre precisão e sensibilidade

👨‍💻 Autor

Projeto desenvolvido por Carlos Daniel como parte de estudos em Machine Learning e detecção de anomalias.

📎 Observações
Este projeto pode ser expandido com técnicas de Deep Learning
Futuras melhorias incluem tuning de hiperparâmetros e engenharia de features
