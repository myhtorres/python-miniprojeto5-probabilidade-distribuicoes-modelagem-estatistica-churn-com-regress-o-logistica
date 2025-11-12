# 📊 Mini-Projeto 5 — Probabilidade, Distribuições e Modelagem Estatística de Churn com Regressão Logística

Projeto desenvolvido durante o curso **Fundamentos de Linguagem Python — Do Básico a Aplicações de IA**, da **Data Science Academy (DSA)**.  
O objetivo é aplicar conceitos fundamentais de **probabilidade, inferência estatística e regressão logística** para analisar o fenômeno de **churn** (cancelamento de clientes) em uma empresa fictícia de telecomunicações.

---

## 🧭 1. Contexto do Negócio

O **churn** representa a taxa de cancelamento ou perda de clientes em um determinado período.  
É um dos principais indicadores de **retenção, satisfação e fidelização** de clientes.  

Neste projeto, analisamos dados de uma empresa fictícia — **Connecta Telecom** — com o objetivo de **entender os fatores que influenciam o cancelamento** e propor ações baseadas em evidências para reduzir essa taxa:contentReference[oaicite:0]{index=0}.

---

## 🎯 2. Objetivo do Projeto

Aplicar técnicas de **análise estatística e modelagem preditiva** para identificar os principais fatores que impactam o churn, utilizando o modelo de **Regressão Logística**.  

O projeto busca:
- Traduzir resultados estatísticos em **insights de negócio**.  
- Avaliar o **impacto de variáveis** como tempo de contrato, valor da fatura e tipo de serviço.  
- Gerar um **modelo interpretável e explicável** para suporte à decisão.  

---

## 🧩 3. Conceitos Fundamentais

Este projeto consolida vários tópicos centrais da estatística e da ciência de dados, apresentados ao longo do módulo:

### 🔹 Amostra x População
- **População:** conjunto total de elementos sobre o qual queremos tirar conclusões.  
- **Amostra:** subconjunto representativo da população, utilizado para inferência estatística:contentReference[oaicite:1]{index=1}.  

### 🔹 Teoria da Probabilidade e Distribuições
A probabilidade mede o grau de incerteza de eventos e é base para todos os modelos estatísticos.  
As distribuições de probabilidade usadas incluem:contentReference[oaicite:2]{index=2}:
- **Normal (Gaussiana):** fenômenos contínuos e simétricos.  
- **Binomial:** eventos com dois resultados (sucesso/fracasso).  
- **Poisson:** contagem de ocorrências em um intervalo fixo.  
- **Exponencial:** tempo entre eventos sucessivos.  

### 🔹 Regressão Linear Múltipla
Utilizada para entender o impacto simultâneo de múltiplas variáveis independentes sobre uma variável dependente contínua — por exemplo, como tamanho, localização e preço influenciam o valor de uma casa:contentReference[oaicite:3]{index=3}.

### 🔹 Regressão Logística
Técnica usada para prever a **probabilidade de ocorrência de um evento binário**, como “cancelou” ou “não cancelou”.  
O modelo gera probabilidades entre 0 e 1 e é amplamente aplicado em negócios, marketing e análise de risco:contentReference[oaicite:4]{index=4}.

### 🔹 Biblioteca Statsmodels
Biblioteca estatística avançada usada para inferência e análise de modelos lineares e logísticos.  
Diferente do Scikit-learn (focado em previsão), o Statsmodels oferece **interpretação estatística completa**, incluindo:
- p-valores e intervalos de confiança;  
- análise de resíduos;  
- sumários detalhados do modelo:contentReference[oaicite:5]{index=5}.  

---

## 🧮 4. Escopo Analítico

Etapas principais do projeto:

1. **Importação e preparação dos dados** (Connecta Telecom).  
2. **Análise exploratória** (EDA) das variáveis de churn.  
3. **Construção do modelo de Regressão Logística** com `statsmodels`.  
4. **Avaliação estatística dos coeficientes** e interpretação das odds ratios.  
5. **Geração de recomendações** baseadas nos fatores de maior impacto.  

---

## 📈 5. Resultados e Insights

- **Tempo de fidelidade** e **tipo de contrato** mostraram-se as variáveis mais relevantes para a retenção.  
- Clientes com contratos mensais apresentaram **maior probabilidade de churn**.  
- Faturas mais altas correlacionaram-se com **menor satisfação e maior chance de cancelamento**.  
- O modelo possibilita **ações direcionadas** em grupos de risco e fundamenta campanhas de retenção.

---

## 🧰 6. Tecnologias Utilizadas

| Categoria | Ferramenta / Biblioteca |
|------------|------------------------|
| Linguagem | Python 3.12 |
| Estatística | Statsmodels, SciPy |
| Manipulação e Visualização | Pandas, NumPy, Seaborn, Matplotlib |
| Ambiente | Jupyter Notebook (VS Code) |
| Controle de Versão | Git e GitHub |

---

## 📂 7. Estrutura do Projeto

Python-MiniProjeto5/
│

├── Python-MiniProjeto5.ipynb # Notebook principal do projeto

└── README.md # Documentação do projeto

---

## 👩‍💻 8. Autora

**Myrelle Torres**  

---

> 🧠 *Este projeto marca a transição do estudo de estatística descritiva para modelagem preditiva, unindo teoria, prática e aplicação real em análise de churn corporativo.*

---
