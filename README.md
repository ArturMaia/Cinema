<p align="center">
  <img src="https://github.com/ArturMaia/Cinema/blob/main/Cinema.jpeg" alt="Filmes" style="width: 150px; border-radius: 10px;">
</p>

# Recomendador de Filmes

O **Recomendador de Filmes** é um projeto de ciência de dados que utiliza técnicas de aprendizado de máquina para sugerir filmes aos usuários com base em suas preferências e no histórico de avaliações de outros usuários. O projeto foi desenvolvido com o objetivo de explorar dados de filmes e avaliações, aplicar análises exploratórias e construir um sistema de recomendação eficiente.
Dados: [Link](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset/data)
## Objetivo

O projeto visa criar um sistema de recomendação personalizado de filmes utilizando dados de avaliações de usuários e informações sobre os filmes. Com isso, os usuários podem receber sugestões de filmes com base em suas preferências de gêneros, avaliações passadas e no comportamento de outros usuários.

## Funcionalidades

- **Análise Exploratória de Dados (EDA)**: Análise de dados sobre filmes e avaliações, incluindo a distribuição de classificações e gêneros.
- **Sistema de Recomendação**: Implementação de um sistema de recomendação baseado em filtragem colaborativa para sugerir filmes aos usuários.
- **Visualização de Dados**: Gráficos e visualizações para entender padrões e insights dos dados de filmes e avaliações.

## Tecnologias Utilizadas

- **Python 3**
- **Bibliotecas**:
  - `pandas`: Manipulação e análise de dados.
  - `numpy`: Operações numéricas.
  - `matplotlib`, `seaborn`: Visualização de dados.
  - `scikit-learn`: Algoritmos de aprendizado de máquina e avaliação de modelos.
  - `surprise`: Biblioteca para recomendação de filmes baseada em filtragem colaborativa.

1. **Pré-processamento dos Dados**:
   - Carregamento dos dados de filmes (`movies.csv`) e avaliações (`ratings.csv`) com a biblioteca `pandas`.
   - Limpeza dos dados para tratar valores nulos e transformar informações, como os gêneros dos filmes.

2. **Modelo de Recomendação**:
   - O sistema utiliza um algoritmo de **filtragem colaborativa** para gerar recomendações personalizadas. A recomendação é baseada no comportamento de usuários similares e nas avaliações de filmes já feitas.

3. **Avaliação do Modelo**:
   - O desempenho do modelo é avaliado por meio de métricas como **precisão** e **erro quadrático médio (RMSE)**.

4. **Geração de Recomendação**:
   - O sistema sugere filmes para um usuário com base em sua avaliação prévia e nos dados dos outros usuários.
