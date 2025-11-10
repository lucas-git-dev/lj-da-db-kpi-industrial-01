# Dashboard de KPIs Industrial

## Objetivo
Monitorar a performance de produção e qualidade de uma fábrica, com foco em atingir metas e reduzir defeitos.

## Contexto
- Setor: Manufatura
- Linhas de produção: Linha A, Linha B, Linha C
- Produtos: P1, P2, P3
- Periodicidade: Mensal

## Problemas para resolver
1) Estamos batendo a **meta de produção** por linha e produto?
2) Qual a **taxa de defeitos (%)** e como ela evolui no mês?
3) Onde estão os **maiores problemas** (linha/produto)?
4) Qual é a **eficiência** (produção real ÷ planejada)?
5) O **retrabalho** está crescendo ou caindo?

## KPIs
- **Produção Real (qtd)**
- **Meta de Produção (qtd)**
- **Atingimento da Meta (%) = Produção / Meta**
- **Defeitos (qtd)**
- **Taxa de Defeitos (%) = Defeitos / Produção**
- **Retrabalho (qtd)**

## Dados Utilizados
- **Producao_Mensal**: ano_mes, linha, produto, producao_real, meta_producao
- **Qualidade_Mensal**: ano_mes, linha, produto, defeitos, retrabalho
- **Dim_Linha**: linha, descrição
- **Dim_Produto**: produto, descrição, família

## Ferramentas
Excel para pré-tratamento de dados
Power BI para modelo
GitHub para versão e documentação

## O que estou aprendendo
1) Estou criando a estrutura do projeto
2) Importar os arquivos pelo powerbi e tratar pelo powerquery
3) Criar os relacionamentos entre tabelas pelo powerbi
4) Adicionar novas medidas
5) Criar o Layout do Dashboard
6) Editar as cores utilizando funções DAX
7) Gerar Insights a partir dos Dashboards

## Visão geral do Dashboard
![Dashboard](images/Dashboard Geral.png)

## Principais Insights

- A produção ficou **1,51% abaixo da meta** do ano, representando **12.530 peças a menos** que o planejado para o período
- O produto com maior impacto negativo foi a **Pastilha de Freio**
- A **Linha C** teve a maior produção total
- Entre maio e agosto houve um pico de desempenho, seguido de queda no último trimestre