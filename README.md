## # 📡 Telecom X II — Predição de Churn com Machine Learning

*Machine Learning aplicado à identificação de clientes com risco de cancelamento*

![Python](https://img.shields.io/badge/Python-Machine%20Learning-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Machine%20Learning-F7931E?logo=scikitlearn)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Classification-success)
![Alura](https://img.shields.io/badge/Oracle%20ONE-Alura-0A3871)

O **Telecom X II** é um projeto de Data Science desenvolvido para construir 
modelos preditivos capazes de identificar clientes com maior probabilidade de 
cancelamento dos serviços de uma empresa de telecomunicações.

O projeto representa a evolução da análise exploratória realizada no 
**Telecom X I**, avançando para preparação dos dados, seleção de variáveis, 
treinamento de modelos de classificação, avaliação de performance e 
interpretação dos fatores associados ao churn.

Desenvolvido durante a **Tech Foundation — Especialização Data Science**, 
integrante do programa **Oracle Next Education (ONE) G9 BR / Alura**.

---

## 📌 Objetivo

Utilizando Python e suas principais bibliotecas, coletar, tratar, analisar dados e desenvolver um Sistema Preditivo de Machine Learning, capaz de identificar quais clientes têm maior probabilidade de cancelar seus serviços. O projeto transforma dados históricos em ações estratégicas de retenção, permitindo à empresa economizar até R$ 1.020.000/ano.

---

✨ Destaques do Projeto

- 79.2% de Recall - Detecta a maioria dos cancelamentos antes que aconteçam
- 75.4% de Precisão - Alta confiabilidade nas previsões positivas
- 85.1% ROC/AUC - Excelente capacidade discriminativa
- Identificação de 3 perfis de alto risco com taxas de churn específicas
- Dashboard estratégico com plano de ação detalhado

---

## 🛠️ Tecnologias Utilizadas

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-yellow?logo=googlecolab&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple?logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-teal?logo=seaborn&logoColor=white)
![Scikit](https://img.shields.io/badge/Scikit--learn-1.3%252B-orange)
![NumPy](https://img.shields.io/badge/NumPy-1.24%252B-blueviolet)
![Joblib](https://img.shields.io/badge/Joblib-1.3%252B-yellowgreen)

---

## 📁 Estrutura do Projeto

telecomx-churn-predictor/
│
├── 📊 telecomx_model/              # Artefatos salvos
│   ├── modelo_churn_Random_Forest.pkl
│   ├── preprocessor.pkl
│   ├── feature_names.pkl
│   └── resumo_resultados.csv
│
├── 📈 visualizations/              # Gráficos e dashboards
│   ├── correlation_matrix.png
│   ├── feature_importance.png
│   └── roc_curves.png
│
├── 📋 TelecomX_Churn_Analysis.ipynb  # Notebook completo
├── 📄 README.md                     # Este arquivo
└── 📑 requirements.txt             # Dependências

---

## 🔍 Visualizações e Insights

🚨 Top 5 Fatores de Churn

- Tipo de Contrato (Mensal vs Anual) - Fator mais crítico
- Tempo como Cliente (< 3 meses = alto risco)
- Valor da Conta Mensal (> R$70 = risco 60% maior)
- Serviço Fiber Optic - Maior insatisfação
- Falta de Serviços Adicionais - Segurança e suporte reduzem churn

---

## 📎 Como Executar o Projeto

Instale as dependências:

- pip install pandas matplotlib seaborn
- Abra o notebook
- jupyter notebook
- Execute as células na ordem

---

## 🙏 Agradecimento

- A todas as professoras e professores da Alura nessa jornada
- Equipe de dados da TelecomX BR pelos dados fornecidos

---

## 📬 Contato

Projeto desenvolvido por Marcus Guedes  
📧 Email: [mclguedes@gmail.com]  
📱 LinkedIn: [https://www.linkedin.com/in/marcusguedes]



