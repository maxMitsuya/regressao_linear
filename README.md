# regressao_linear
Case de estudo do curso DNC
# Projeto de Regressão Linear para Previsão de Preços de Imóveis

Este projeto tem como objetivo prever o preço de imóveis nos Estados Unidos com base em características como renda média da área, idade média da casa, número de quartos, número de banheiros e população da área. O modelo de regressão linear foi implementado utilizando a biblioteca `scikit-learn` em Python.

## Dataset

O conjunto de dados utilizado é o **USA_Housing.csv**, que contém as seguintes colunas:

- **Avg_Area_Income**: Renda média da área.
- **Avg_Area_House_Age**: Idade média das casas na área.
- **Avg_Area_Number_of_Rooms**: Número médio de quartos nas casas da área.
- **Avg_Area_Number_of_Bedrooms**: Número médio de banheiros nas casas da área.
- **Area_Population**: População da área.
- **Price**: Preço do imóvel (variável alvo).

## Estrutura do Código

1. **Importação de Bibliotecas**:
   - Foram utilizadas bibliotecas como `pandas`, `numpy`, `seaborn`, `plotly`, `scikit-learn` e `matplotlib` para análise de dados, visualização e modelagem.

2. **Análise Exploratória de Dados (EDA)**:
   - Visualização de distribuições e correlações entre as variáveis.
   - Geração de gráficos como boxplots, pairplots e heatmaps.

3. **Pré-processamento de Dados**:
   - Renomeação de colunas para facilitar o manuseio.
   - Remoção da coluna `Address`, que não é relevante para o modelo.

4. **Divisão dos Dados**:
   - Os dados foram divididos em conjuntos de treino (70%) e teste (30%).

5. **Modelagem**:
   - Um modelo de regressão linear foi treinado utilizando o conjunto de treino.
   - O modelo foi avaliado utilizando o coeficiente de determinação \( R^2 \).

6. **Visualização dos Resultados**:
   - Comparação entre os valores reais e os valores previstos pelo modelo.

7. **Previsão**:
   - O modelo foi utilizado para prever o preço de um imóvel com base em valores hipotéticos.

## Como Executar o Projeto

### No Google Colab

1. Clique no botão abaixo para abrir o notebook no Google Colab:
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1XZtg6Swi6ulJ0Ht4mcURq7tJHBfJ0Bts?usp=sharing)

2. Faça uma cópia do notebook na sua conta do Google Drive.
3. Execute as células na ordem para reproduzir os resultados.

### Localmente

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
