#Previsão de Consumo Energético Residencial

MVP — Pós‑Graduação em Ciência de Dados e Analytics | PUC‑Rio  
Autora: Debora Jansen

Este projeto desenvolve um modelo de previsão para o consumo energético residencial utilizando técnicas de regressão aplicadas a séries temporais. O objetivo é demonstrar domínio do fluxo completo de um projeto de Machine Learning, desde a análise exploratória até a avaliação dos modelos e discussão dos resultados. O dataset utilizado é proveniente do UCI Machine Learning Repository, garantindo reprodutibilidade e acesso público.

#Objetivo

Construir um MVP capaz de prever o consumo energético residencial com base em dados históricos, avaliando diferentes modelos de regressão e identificando a abordagem mais eficaz para capturar padrões temporais do consumo.

#Metodologia

**1. Coleta e Carregamento dos Dados**
Dataset oficial do UCI Machine Learning Repository

Carregamento via URL raw do GitHub para garantir reprodutibilidade

Arquivo utilizado: individual+household+electric+power+consumption.zip

**2. Preparação e Limpeza**
Conversão de datas e criação de índice temporal

Tratamento de valores ausentes

Criação de atributos temporais (lags) para modelagem

**3. Análise Exploratória**
Visualização da série temporal

Identificação de padrões de consumo

Avaliação de autocorrelação e comportamento ao longo do tempo

**4. Modelagem e Avaliação**
Modelos utilizados:

Regressão Linear (baseline)

Árvore de Decisão

Random Forest

Métricas aplicadas:

MSE
MAE
R²

Comparação entre modelos e análise das previsões

#Dados Utilizados

**Fonte:** UCI Machine Learning Repository
**Arquivo:** individual+household+electric+power+consumption.zip  
**URL raw:** https://raw.githubusercontent.com/DeboraJansen95/mvp-previsao-consumo-energetico-residencial-pos-puc-rj/main/individual+household+electric+power+consumption.zip
**Variável-alvo:**
Global_active_power (consumo energético em kW)

#Tecnologias e Ferramentas

Python

Pandas

Matplotlib

Scikit‑Learn

Google Colab

GitHub

#Estrutura do Repositório

mvp-previsao-consumo-energetico-residencial-pos-puc-rj
├── README.md
├── data/
│   └── household_power_consumption.txt
└── notebook/
    └── mvp_previsao_consumo.ipynb

#Referências

UCI Machine Learning Repository — Fonte original dos dados

Documentação do Pandas — https://pandas.pydata.org/docs/

Documentação do Scikit‑Learn — https://scikit-learn.org/stable/

Documentação do Matplotlib — https://matplotlib.org/stable/
