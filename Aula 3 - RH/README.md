# Aula 3 - Dashboard para Recursos Humanos

Este projeto foi desenvolvido como parte da **Aula 3** do Intensivão de Power BI.

O dashboard tem como objetivo visualizar indicadores de desempenho da área de Recursos Humanos, como número de contratações, funcionários ativos, demissões, turnover e distribuição por cidade, gênero, área e cargo. A construção do painel tem foco no uso de medidas com DAX, novos visuais como árvore hierárquica e gráfico de funil, além de recursos de interatividade como Tooltip e filtros personalizados.

[🔗 Acesse o dashboard criado aqui](https://app.powerbi.com/view?r=eyJrIjoiZGY4Yjk3MDAtZTQyNC00NjJlLTk5YTQtMGUzNWZhZTU1MTQyIiwidCI6ImEyODlmNTY1LTY5YzgtNDc3Zi05MWJhLTMzM2FkNGJlOWMwYSJ9)

> **Observação:** O Power BI não dá suporte à árvore hierárquica na Publicação Web. Por este motivo, esse visual ficará desconfigurado no link. Para visualizar o dashboard completo, adicionei um PDF com o visual correto.

## Principais aprendizados:
- **Criação de medidas com DAX** para cálculo de:
  - Total de contratações e demissões.
  - Funcionários ativos.
  - % de Turnover.
- **Uso de funções como** `COUNTROWS` e `CALCULATE`.
- **Novos visuais aprendidos**:
  - Gráfico de **Sparkline** para mostrar evolução de contratações ao longo dos anos.
  - Gráfico de **Funil** (funcionários por cidade).
  - Gráfico de **Árvore Hierárquica** (Área > Cargo).
- **Configuração de Tooltip (Dica de Ferramenta)** com visual dedicado.
- **Filtros e interatividade** sem poluir o dashboard.