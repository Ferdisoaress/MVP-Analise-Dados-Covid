# 📌 Análise Exploratória e Pré-processamento de Dados – COVID-19 & Vacinação

Este repositório contém um projeto completo de análise exploratória de dados (EDA) com foco na relação entre o avanço da vacinação contra a COVID-19 e a evolução dos casos e mortes pela doença em diferentes países. Além disso, foram aplicadas diversas técnicas de pré-processamento para transformar os dados brutos em informações úteis, prontas para análises futuras ou aplicação de modelos.

🔗 [Notebook no Google Colab](https://colab.research.google.com/drive/1cb-XHZOtuzTgY3sLnJwrT9Or3p8Rib6i?authuser=1#scrollTo=0-Q0LwOSVqZw)

---

## 📚 Bases de Dados Utilizadas

- [COVID-19 World Vaccination Progress (Kaggle)](https://www.kaggle.com/datasets/gpreda/covid-world-vaccination-progress)
- [Novel Coronavirus 2019 Dataset (Kaggle)](https://www.kaggle.com/datasets/sudalairajkumar/novel-corona-virus-2019-dataset)

Ambos os conjuntos trazem dados consolidados e atualizados sobre o avanço da pandemia, com informações por país, incluindo casos, mortes, população e vacinação.

---

## 🎯 Objetivo

- Investigar padrões e correlações entre o avanço da vacinação e os dados epidemiológicos (casos, mortes, testagem).
- Preparar o dataset com transformações e tratamentos adequados para análises mais profundas ou uso em modelos preditivos.

---

## 🧪 Etapas do Projeto

- **Importação e limpeza** dos dados brutos, incluindo conversão de formatos numéricos e remoção de inconsistências.
- **Criação de variáveis normalizadas per capita** (por 100 mil habitantes) para permitir comparações justas entre países.
- **Análise descritiva** com estatísticas (mínimo, máximo, média, mediana, moda, desvio-padrão, valores ausentes).
- **Visualizações exploratórias** para identificar padrões, dispersões e correlações.
- **Padronização (z-score)** dos dados normalizados.
- **Discretização por quartis**, criando uma variável categórica de gravidade da pandemia.
- **Insights baseados em visualizações e na distribuição das variáveis criadas**.

---

## 📊 Principais Insights

- Países com taxas elevadas de vacinação tendem a apresentar menor gravidade nos indicadores de casos e mortes.
- A normalização por população foi essencial para revelar realidades ocultas por números absolutos.
- Boxplots e scatterplots revelaram a existência de outliers e correlações importantes entre variáveis.
- A variável "Gravidade", construída com discretização por quartis, se mostrou útil para análises qualitativas e segmentações por risco.

---

## ⚙️ Tecnologias Utilizadas

- Python
  - Pandas
  - NumPy
  - Seaborn
  - Matplotlib
  - Scikit-learn
- Google Colab

---

## 📁 Estrutura do Repositório

- `MVP_COVID_ANALISE_VF.ipynb`: Notebook principal com todas as etapas descritas acima, incluindo código, gráficos e interpretações.
- `README.md`: Este arquivo com descrição do projeto.

---

## ✍️ Autoria

Projeto acadêmico desenvolvido por Fernanda Soares, como parte da disciplina **Análise Exploratória e Pré-processamento de Dados**.

---
