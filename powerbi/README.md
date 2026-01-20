# Power BI Dashboard

Esta pasta contém o arquivo final do dashboard desenvolvido no Power BI Desktop.

## Arquivo

- `dashboard_vendas.pbix`  
  Arquivo principal do projeto, contendo:
  - Modelo dimensional em estrela (Star Schema)
  - Medidas DAX explícitas para métricas de negócio
  - Dashboard executivo com KPIs, tendência temporal, composição e análise de performance

## Modelagem de Dados

O dashboard utiliza um modelo em estrela composto por:
- Tabela fato de vendas
- Dimensões de produto, cliente, vendedor, canal e tempo

Todos os cálculos financeiros (receita, desconto, lucro, margem) são realizados via DAX, evitando agregações implícitas e garantindo maior controle semântico.

## Visual e Design

- Tema visual customizado via arquivo JSON
- Layout baseado em ilhas visuais
- Paleta de cores escura (dark theme) focada em legibilidade e hierarquia visual
- Visualizações orientadas à tomada de decisão executiva

## Observação

O arquivo `.pbix` utiliza exclusivamente dados fictícios, criados para fins educacionais e de portfólio, sem qualquer vínculo com dados reais ou corporativos.

---

Projeto desenvolvido por Francesco Fantinel.
