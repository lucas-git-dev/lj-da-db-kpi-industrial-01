# Dashboard de KPIs Industrial

## Objetivo
Monitorar a performance de produção e qualidade de uma fábrica, com foco em atingir metas e reduzir defeitos.

## Contexto
- Setor: Manufatura
- Linhas de produção: Linha A, Linha B, Linha C
- Produtos: P1, P2, P3
- Periodicidade: Mensal

##Problemas para resolver
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
Excel para pré-tratamento
Power BI para modelo
GitHub para versão e documentação