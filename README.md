# 👥 HR-Employee-Attrition

Projeto de análise e predição da **rotatividade de funcionários (attrition)** com base em dados de Recursos Humanos.  
O objetivo é identificar os fatores que levam colaboradores a deixarem a empresa e prever, com base em dados históricos, quais funcionários estão propensos a se desligar.

---

## 🎯 Objetivo

Desenvolver modelos de **Machine Learning** capazes de prever a probabilidade de desligamento de colaboradores com base em variáveis como:

- Idade
- Tempo de empresa
- Carga horária
- Salário
- Satisfação no trabalho
- Número de promoções
- Distância de casa
- Entre outros fatores organizacionais e pessoais

Além disso, gerar **insights estratégicos** para o setor de RH com base em análises estatísticas e visuais.

---

## 💾 Conjunto de Dados

O dataset utilizado contém os seguintes atributos:

- `Age`
- `BusinessTravel`
- `Department`
- `DistanceFromHome`
- `Education`, `EducationField`
- `EnvironmentSatisfaction`
- `JobInvolvement`, `JobLevel`, `JobSatisfaction`
- `MonthlyIncome`, `OverTime`, `YearsAtCompany`, etc.
- `Attrition` (Yes/No)

📌 **Fonte**: [IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

---

## ⚙️ Tecnologias e Bibliotecas

- Python 3.10+
- Pandas, NumPy
- Scikit-learn
- XGBoost, LightGBM
- Matplotlib, Seaborn, Plotly
- Jupyter Notebook

---

## 📊 Etapas do Projeto

1. **Análise Exploratória (EDA)**:
   - Correlações, distribuição das variáveis e análise de desbalanceamento da classe `Attrition`.
2. **Pré-processamento**:
   - Tratamento de dados ausentes, codificação de variáveis categóricas, normalização.
3. **Modelagem Preditiva**:
   - Treinamento de modelos supervisionados (Random Forest, XGBoost, etc.)
   - Validação cruzada e análise de métricas (accuracy, precision, recall, f1-score).
4. **Interpretação de Modelos**:
   - Feature importance
   - SHAP values
5. **Recomendações de RH**:
   - Estratégias para retenção de talentos com base nos insights obtidos.
