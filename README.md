# 🏠 California Housing Price Prediction

## 📌 Sobre o Projeto
Este projeto tem como objetivo desenvolver um modelo de Machine Learning capaz de prever o valor médio de imóveis na Califórnia, utilizando dados do censo de 1990.

A partir de variáveis socioeconômicas e geográficas, buscamos identificar padrões e relações que influenciam o preço das residências, além de construir um modelo preditivo eficiente.

## 🎯 Objetivo
- Prever a variável alvo median_house_value
- Identificar os principais fatores que impactam o preço dos imóveis
- Aplicar um pipeline completo de ciência de dados

## 📊 Dataset

O conjunto de dados foi obtido no Kaggle:
[🔗 https://www.kaggle.com/datasets/camnugent/california-housing-prices/data]

  Principais variáveis:
- median_income → Renda média da região
- housing_median_age → Idade média das casas
- total_rooms → Total de cômodos
- population → População da região
- latitude / longitude → Localização geográfica
- ocean_proximity → Proximidade com o oceano

## 🔍 Etapas do Projeto
1. Análise Exploratória (EDA)
- Distribuição das variáveis
- Correlação entre features
- Identificação de outliers
- Visualizações geográficas

2. Pré-processamento
- Tratamento de valores ausentes
- Codificação de variáveis categóricas
- Normalização/Padronização

3. Engenharia de Features
- Criação de novas variáveis relevantes
- Relações entre população, renda e número de casas

4. Modelagem
- Modelos de regressão (ex: Linear Regression, ElasticNet, Ridge, etc.)
- Ajuste de hiperparâmetros

5. Avaliação
- Métricas utilizadas:
- RMSE
- MAE
- R²
