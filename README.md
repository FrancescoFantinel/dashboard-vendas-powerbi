# Dashboard de Vendas | Power BI

Projeto de Business Intelligence desenvolvido com dados **100% fictícios**, com o objetivo de simular um cenário corporativo real de análise de vendas e apoiar a tomada de decisão executiva.

O projeto cobre todo o ciclo de BI: modelagem de dados, definição de métricas em DAX, design visual e versionamento no GitHub.

## Objetivos do Projeto

- Analisar o desempenho de vendas ao longo do tempo  
- Avaliar a composição da receita por categoria  
- Identificar produtos com maior impacto na receita  
- Disponibilizar KPIs claros para acompanhamento executivo  

## Modelagem de Dados

O modelo segue o padrão **Star Schema**, composto por:

- **Fato:** Vendas  
- **Dimensões:** Produto, Cliente, Vendedor, Canal e Tempo  

Todos os cálculos de negócio são realizados por meio de **medidas DAX explícitas**, evitando agregações implícitas e garantindo maior controle semântico.

## Principais Métricas

- Receita Líquida  
- Lucro  
- Margem (%)  
- Total de Vendas  
- Receita por Período  
- Receita por Categoria  
- Top 10 Produtos por Receita  

## Visual e Design

- Dashboard em **tema escuro (dark theme)**  
- Layout organizado em **ilhas visuais**  
- Hierarquia clara entre KPIs, tendência e análises  
- Paleta de cores consistente definida via tema JSON

## Observação Importante

Todos os dados utilizados neste projeto são **fictícios** e foram criados exclusivamente para fins educacionais e de portfólio, sem qualquer relação com dados reais ou corporativos.

## Preview do Dashboard

Veja a imagem do dashboard na pasta `/images`.
 
