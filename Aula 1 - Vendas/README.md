# Aula 1 - Dashboard de Vendas

Este projeto foi desenvolvido como parte da **Aula 1** do Intensivão de Power BI.

O objetivo do dashboard é apresentar de forma visual e interativa os principais indicadores de desempenho de vendas, como faturamento total, produto mais vendido, e faturamento por marca, localidade e período.


[🔗 Acesse o dashboard criado aqui](https://app.powerbi.com/view?r=eyJrIjoiZDZkNjNhMjAtYWU1ZS00YmJlLTlhNmUtN2JhY2U5OTc5MzFkIiwidCI6ImEyODlmNTY1LTY5YzgtNDc3Zi05MWJhLTMzM2FkNGJlOWMwYSJ9)

## Principais aprendizados:

- **Tratamento de dados no Power Query**:
  - Remoção de colunas e linhas em branco.
  - Padronização de nomes (de “Sobrenome, Nome” para “Nome Sobrenome”).
  - Separação de colunas com delimitadores (País e Continente).
  - Criação de novas colunas como **Faturamento (Preço x Quantidade)**.
- **Criação de visuais no Power BI**:
  - Cartões com **valores únicos** (Faturamento Total, Produto mais vendido).
  - Uso de **filtro de N superiores** para exibir o produto mais vendido.
  - **Gráfico de colunas e linha** para análise de Faturamento e Quantidade Vendida por tempo (mês/ano).
  - **Gráfico de barras** para Faturamento por Marca.
  - **Gráfico de mapa** com Faturamento por Continente.