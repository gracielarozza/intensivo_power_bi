# Aula 2 - Dashboard de Produção

Este projeto foi desenvolvido como parte da **Aula 2** do Intensivão de Power BI.

O objetivo do dashboard é visualizar indicadores de desempenho da produção, como quantidade produzida, peças rejeitadas, horas produtivas e paradas. A construção do painel tem foco no uso de medidas com DAX, gráficos percentuais e filtros interativos.


[🔗 Acesse o dashboard criado aqui](https://app.powerbi.com/view?r=eyJrIjoiNzJjZWIwNzAtMDNhZi00OTRjLThiMWMtZGIyZjhkNzgxN2FhIiwidCI6ImEyODlmNTY1LTY5YzgtNDc3Zi05MWJhLTMzM2FkNGJlOWMwYSJ9)

## Principais aprendizados:
- **Criação de medidas com DAX**:
  - `SUM` para totalizar colunas como Qtd. Produzida e Qtd. Rejeitada.
  - `CALCULATE` para somas com condicional (ex: Horas Produtivas = Soma do total de horas sem ocorrência).
  - Fórmulas de percentual (ex: % Qualidade = Total de Peças Aprovadas / Total de Peças Produzidas).
- **Criação de visuais no relatório**:
  - Cartões com valores calculados para exibir indicadores principais.
  - Gráfico de área para análise de produção mensal.
  - Gráficos de velocímetro para percentuais.
  - Uso de filtros para variáveis categóricas.