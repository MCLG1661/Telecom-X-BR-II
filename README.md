# 📡 Telecom X BR II — Predição de Churn com Machine Learning

> **Machine Learning aplicado à identificação de clientes com maior risco de cancelamento e apoio a estratégias preventivas de retenção.**

![Python](https://img.shields.io/badge/Python-Machine%20Learning-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Machine%20Learning-F7931E?logo=scikitlearn)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Classification-success)
![Alura](https://img.shields.io/badge/Oracle%20ONE-Alura-0A3871)

---

## 💼 Sobre o Projeto

O **Telecom X BR II** é um projeto de Data Science voltado à construção de modelos preditivos capazes de identificar clientes com maior probabilidade de churn em uma empresa de telecomunicações.

O projeto representa a evolução natural do **Telecom X BR I**, que concentrou a análise em ETL, Análise Exploratória de Dados e Business Insights.

Nesta segunda etapa, o foco passa a ser:

- preparação dos dados;
- feature engineering;
- seleção de variáveis;
- treinamento de modelos de classificação;
- avaliação de performance;
- interpretação dos resultados;
- aplicação das previsões ao contexto de retenção de clientes.

O projeto foi desenvolvido durante a **Tech Foundation — Especialização Data Science**, integrante do programa **Oracle Next Education (ONE) G9 BR / Alura**.

---

## 🎯 Objetivo

Construir um pipeline de Machine Learning capaz de utilizar dados históricos dos clientes para estimar o risco de churn e apoiar estratégias preventivas de retenção.

A proposta é transformar padrões observados nos dados em um mecanismo preditivo capaz de responder:

> **Quais clientes apresentam maior risco de cancelamento e devem ser priorizados em ações de retenção?**

---

## 🔗 Evolução do Projeto

O Telecom X BR II dá continuidade ao estudo iniciado no Telecom X BR I.

```text
Telecom X BR I
ETL + EDA + Business Insights
        ↓
Preparação dos Dados
        ↓
Feature Engineering
        ↓
Seleção de Variáveis
        ↓
Treinamento dos Modelos
        ↓
Avaliação
        ↓
Telecom X BR II
Machine Learning + Predição de Churn
        ↓
Identificação de Clientes de Risco
        ↓
Estratégias Preventivas de Retenção
```

🔗 [Acessar Telecom X BR I](https://github.com/MCLG1661/Telecom-X-BR-I)

---

## 🔬 Pipeline de Machine Learning

```text
Dados Históricos
      ↓
Tratamento
      ↓
Encoding
      ↓
Normalização
      ↓
Análise de Correlação
      ↓
Seleção de Features
      ↓
Treinamento
      ↓
Modelos de Classificação
      ↓
Avaliação
      ↓
Interpretação
      ↓
Predição de Churn
```

---

## 📊 Resultados do Projeto

Os modelos desenvolvidos apresentaram resultados relevantes na identificação de clientes com risco de evasão.

| Métrica | Resultado | Interpretação |
|---|---:|---|
| **Recall** | **79,2%** | Capacidade de identificar grande parte dos clientes que efetivamente apresentam churn |
| **Precisão** | **75,4%** | Confiabilidade das previsões positivas realizadas pelo modelo |
| **ROC/AUC** | **85,1%** | Capacidade discriminativa do modelo entre clientes com e sem churn |

Também foram identificados **três perfis de maior risco**, além de fatores relevantes associados à evasão.

---

## 🎯 Por que Priorizar Recall?

Em problemas de churn, um dos principais riscos do modelo é classificar como seguro um cliente que, na prática, está prestes a cancelar.

Esse tipo de erro representa um **falso negativo**.

Por isso, o Recall é uma métrica especialmente relevante:

> **Quanto maior o Recall, maior a capacidade do modelo de capturar clientes que realmente apresentam risco de churn.**

Com Recall de **79,2%**, o modelo consegue identificar uma parcela significativa dos clientes que efetivamente apresentam comportamento de evasão.

Do ponto de vista de negócio, isso pode ser mais importante do que maximizar apenas a acurácia global.

---

## 🚨 Principais Fatores Associados ao Churn

A análise identificou algumas características relevantes para a previsão:

- tipo de contrato;
- tempo de relacionamento com a empresa;
- valor mensal da conta;
- tipo de serviço de internet;
- contratação de serviços adicionais.

Essas variáveis ajudam a caracterizar perfis com diferentes níveis de risco.

---

## 💼 Aplicação ao Negócio

A utilização de modelos preditivos permite migrar de uma estratégia predominantemente reativa para uma abordagem mais preventiva.

```text
Modelo Preditivo
      ↓
Identificação de Risco
      ↓
Segmentação dos Clientes
      ↓
Priorização
      ↓
Ações de Retenção
      ↓
Monitoramento dos Resultados
```

Entre as possíveis aplicações estão:

- identificação antecipada de clientes com maior risco;
- priorização de campanhas de retenção;
- personalização de ofertas;
- revisão de planos e contratos;
- desenvolvimento de estratégias específicas por segmento;
- otimização dos recursos destinados à retenção.

---

## 🧠 Interpretação Gerencial

O valor do modelo não está apenas em prever churn, mas em apoiar decisões mais direcionadas.

A combinação entre **probabilidade de churn, perfil do cliente e fatores associados à evasão** pode ajudar a empresa a:

- identificar clientes prioritários;
- segmentar ações de retenção;
- reduzir desperdício de recursos;
- melhorar a eficiência das campanhas;
- antecipar possíveis perdas de receita.

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Aplicação |
|---|---|
| **Python** | Desenvolvimento e modelagem |
| **Pandas** | Manipulação e preparação dos dados |
| **NumPy** | Operações numéricas |
| **Scikit-learn** | Treinamento e avaliação dos modelos |
| **Matplotlib** | Visualização de resultados |
| **Seaborn** | Visualizações estatísticas |
| **Jupyter / Google Colab** | Desenvolvimento e execução |

---

## 📁 Estrutura do Projeto

```text
Telecom-X-BR-II/
│
├── Telecom_X_BR_II.ipynb
└── README.md
```

---

## 💡 Competências Demonstradas

O projeto aplica conhecimentos e práticas relacionados a:

- Machine Learning;
- Classification;
- Customer Churn Prediction;
- Python;
- Pandas;
- Scikit-learn;
- Data Preprocessing;
- Feature Engineering;
- Encoding;
- Normalização;
- Feature Selection;
- Model Evaluation;
- Precision;
- Recall;
- ROC/AUC;
- Data Visualization;
- Business Analytics;
- Data-Driven Decision Making.

---

## 🚀 Possíveis Evoluções

O projeto pode evoluir para uma solução mais próxima de produção por meio de:

- comparação sistemática entre novos algoritmos;
- otimização de hiperparâmetros;
- cross-validation;
- pipeline automatizado de pré-processamento;
- explicabilidade dos modelos;
- API para disponibilização das previsões;
- dashboard para acompanhamento de clientes de risco;
- deploy do modelo em Cloud;
- monitoramento de performance;
- detecção de drift;
- re-treinamento periódico.

---

## ⬅️ Etapa Anterior

### Telecom X BR I — ETL, EDA e Análise de Churn

🔗 [Explorar Telecom X BR I](https://github.com/MCLG1661/Telecom-X-BR-I)

---

## 📚 Contexto Acadêmico

Projeto desenvolvido durante a **Tech Foundation — Especialização Data Science**, integrante do programa **Oracle Next Education (ONE) G9 BR / Alura**.

A proposta foi evoluir da análise exploratória para a construção de modelos preditivos aplicados ao problema de Customer Churn.

---

## 👤 Autor

### Marcus Guedes

**Project Management | PMO | Operations & Performance | Data Analytics & AI for Business**

[GitHub](https://github.com/MCLG1661) • [LinkedIn](https://www.linkedin.com/in/marcusguedes/)

---

⭐ Projeto de estudo e portfólio focado em **Machine Learning aplicado à predição de churn e apoio a estratégias preventivas de retenção**.
