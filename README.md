# Dashboard de Custos e Vendas | Power BI

## Objetivo
Dashboard desenvolvido para acompanhar o desempenho comercial, analisar faturamento e custos de vendas, identificar a participação dos clientes e monitorar o volume de produtos vendidos. A base de dados é fictícia, utilizada para fins de estudo e portfólio.

## Tecnologias e desenvolvimento
- Microsoft Power BI Desktop
- Medidas DAX
- Agregações de dados e hierarquia de datas
- Segmentação de dados e visualização de indicadores

O relatório utiliza a tabela `INDICADORES`, com os campos `NOME CLIENTE`, `DATA`, `INDICADOR`, `QUANTIDADE VENDIDA` e `CUSTO DE VENDA`. O painel combina medidas, somas de colunas, cartões, gráficos, tabelas e filtros interativos.

A origem da base, as etapas de tratamento no Power Query e as expressões DAX exatas não foram verificadas.

## Indicadores (KPIs)

| Indicador | Finalidade |
| --- | --- |
| Quantidade de clientes | Acompanhar o número de clientes contabilizados pela medida QTD_CLIENTES. |
| Faturamento | Monitorar o valor de vendas calculado pela medida FATURAMENTO. |
| Quantidade de produtos vendidos | Acompanhar o volume comercializado pela soma de QUANTIDADE VENDIDA. |
| Data atual | Exibir a referência temporal retornada pela medida DATA ATUAL. |

## Gráficos e tabelas

| Visual | Finalidade |
| --- | --- |
| Faturamento por indicador | Comparar o faturamento entre as categorias do campo INDICADOR. |
| Faturamento por ano e mês | Identificar variações de faturamento entre períodos. |
| Faturamento por cliente | Comparar a contribuição de cada cliente para o faturamento. |
| Resumo de qtde valor indicador | Detalhar cliente, quantidade vendida, total de vendas e indicador. |
| Valor de venda por cliente | Exibir data, soma do custo de venda, faturamento e indicador. O visual não contém o campo cliente; recomenda-se revisar o título ou incluir esse campo. |

## Filtros interativos
- **Ano e mês:** selecionar períodos pela hierarquia do campo DATA.
- **Indicador:** segmentar a análise pelas categorias registradas na base.

## Análises de negócio possibilitadas
- Identificar clientes com maior participação no faturamento.
- Comparar o desempenho comercial entre períodos e categorias.
- Acompanhar o volume de produtos comercializados.
- Comparar custos e faturamento nos detalhamentos disponíveis.

O painel não apresenta um KPI específico de lucro ou margem. As análises acima representam possibilidades de exploração, não conclusões numéricas verificadas.

## Como utilizar
1. Após a disponibilização do arquivo Projeto_custos_vendas.pbix neste repositório, faça o download.
2. Abra-o no Microsoft Power BI Desktop.
3. Utilize os filtros e explore os gráficos e tabelas.
4. Para atualizar os dados, verifique a disponibilidade da fonte original.

## Autoria
Sandra Tavares — projeto de análise de dados e Business Intelligence.
