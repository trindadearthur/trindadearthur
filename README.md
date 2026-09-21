# Arthur Trindade

**Data Analyst | SQL • Python • Power BI • Excel**

Estudante de Ciência da Computação com foco em análise de dados, Business Intelligence e automação.

Meu trabalho é voltado para transformar dados brutos em informação útil: estruturar bases, tratar inconsistências, construir consultas, criar indicadores e apresentar resultados de forma clara para apoiar decisões.

Atualmente desenvolvo projetos completos de dados, passando por **ETL, SQL, análise exploratória, modelagem, visualização e construção de dashboards**.

---

## Stack

### Data Analysis & Automation

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square\&logo=pandas\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square\&logo=numpy\&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square\&logo=microsoftexcel\&logoColor=white)

### Data & BI

![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square\&logo=postgresql\&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square\&logo=mysql\&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square\&logo=powerbi\&logoColor=black)

### Tools

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square\&logo=github\&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square\&logo=jupyter\&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square\&logo=visualstudiocode\&logoColor=white)

---

# Projetos em destaque

Os projetos abaixo foram pensados para reproduzir problemas encontrados no dia a dia de uma área de dados: vendas, clientes, qualidade de dados, indicadores, comportamento e tomada de decisão.

## E-commerce Sales Analytics

**Python • Pandas • SQL • MySQL • Power BI**

Análise end-to-end de uma operação de e-commerce, desde os dados transacionais brutos até a construção de indicadores e dashboards executivos.

O projeto envolve análise de aproximadamente 100 mil pedidos e busca responder questões relacionadas a faturamento, clientes, produtos, logística e experiência de compra.

### O que será analisado

* faturamento e evolução mensal
* ticket médio
* volume de pedidos
* categorias com maior receita
* desempenho por região
* comportamento dos clientes
* prazo e atraso de entregas
* impacto da logística nas avaliações
* desempenho de vendedores
* meios de pagamento

### Pipeline

`Raw Data → Python → Data Cleaning → SQL → Business Analysis → Power BI`

**Status:** Em desenvolvimento

[Ver projeto](https://github.com/trindadearthur/ecommerce-sales-analytics)

---

## Customer Churn Analytics

**Python • Pandas • SQL • Power BI**

Projeto focado em entender por que clientes deixam uma empresa e quais características estão mais relacionadas ao cancelamento.

A análise parte de dados de clientes, contratos e serviços para identificar padrões de churn e transformar os resultados em informações acionáveis.

### O que será desenvolvido

* tratamento e validação da base
* análise exploratória
* segmentação de clientes
* análise de churn por perfil
* comparação entre contratos e serviços
* indicadores de retenção
* consultas SQL
* dashboard de acompanhamento
* recomendações baseadas nos dados

**Status:** Planejado

[Ver projeto](https://github.com/trindadearthur/customer-churn-analytics)

---

## Sales Performance Dashboard

**Power BI • DAX • Power Query • SQL**

Projeto de Business Intelligence para acompanhamento do desempenho comercial de uma empresa com múltiplas lojas, produtos, vendedores e regiões.

O objetivo é construir uma visão executiva capaz de mostrar rapidamente onde a operação está crescendo, onde está perdendo desempenho e quais áreas precisam de atenção.

### Indicadores

* receita
* lucro
* margem
* pedidos
* ticket médio
* meta x realizado
* crescimento mensal
* desempenho por loja
* desempenho por vendedor
* desempenho por categoria
* análise regional

### Conceitos utilizados

* modelagem dimensional
* modelo estrela
* Power Query
* medidas DAX
* KPIs
* análise temporal
* drill-down

**Status:** Planejado

[Ver projeto](https://github.com/trindadearthur/sales-performance-dashboard)

---

## Data Quality & ETL Pipeline

**Python • Pandas • SQL • ETL**

Pipeline desenvolvido para receber dados provenientes de múltiplas fontes, identificar problemas de qualidade e gerar uma base consolidada pronta para análise.

O projeto reproduz um cenário comum em empresas onde informações chegam em formatos diferentes e apresentam inconsistências antes de poderem ser utilizadas.

### Problemas tratados

* registros duplicados
* valores ausentes
* datas inválidas
* tipos incorretos
* inconsistência de nomes
* valores fora do padrão
* registros sem relacionamento
* dados provenientes de CSV, Excel e JSON

### Pipeline

`Extract → Validate → Transform → Load → SQL`

Ao final do processamento, o pipeline também gera um relatório com indicadores de qualidade dos dados.

**Status:** Planejado

[Ver projeto](https://github.com/trindadearthur/data-quality-etl)

---

## Business Analytics Case

**SQL • Python • Power BI**

Investigação orientada por uma pergunta de negócio:

> **Por que a receita da empresa caiu nos últimos meses?**

Em vez de partir diretamente para gráficos, o projeto utiliza uma abordagem investigativa para decompor o problema e encontrar quais fatores realmente explicam a variação observada.

### Investigação

* evolução da receita
* quantidade de clientes
* ticket médio
* frequência de compra
* produtos
* categorias
* regiões
* canais
* margem
* sazonalidade

O projeto termina com um diagnóstico apoiado pelos dados e um conjunto de recomendações.

**Status:** Planejado

[Ver projeto](https://github.com/trindadearthur/business-analytics-case)

---

## Loot Analytics

**Python • SQL • Power BI • APIs • ETL**

Projeto de dados aplicado à **Loot Ofertas**, iniciativa própria voltada ao compartilhamento de promoções de diferentes marketplaces.

A proposta é criar uma estrutura analítica para acompanhar o desempenho das ofertas publicadas e transformar os dados da operação em indicadores para tomada de decisão.

### Dados analisados

* marketplace
* produto
* categoria
* preço
* desconto
* horário de publicação
* cliques
* conversões
* vendas
* comissão
* desempenho por canal

### Objetivos

* identificar melhores horários para publicação
* comparar marketplaces
* avaliar desempenho por categoria
* acompanhar conversões
* identificar ofertas com alto interesse e baixa conversão
* automatizar coleta e tratamento dos dados
* construir dashboard de acompanhamento da operação

### Arquitetura

`Marketplaces / Bot → Python → ETL → SQL → Power BI`

**Status:** Planejado

[Ver projeto](https://github.com/trindadearthur/loot-analytics)

---

# Outros trabalhos

Também desenvolvo projetos acadêmicos e experimentais envolvendo:

* análise exploratória de dados
* modelagem de banco de dados
* Machine Learning
* desenvolvimento Python
* automação
* aplicações web
* coleta e estruturação de dados

Parte desses trabalhos está disponível nos demais repositórios deste perfil.

---

# Atualmente estudando

```text
SQL avançado
├── CTEs
├── Window Functions
├── Subqueries
└── análise orientada a negócio

Power BI
├── Power Query
├── DAX
├── modelagem dimensional
└── dashboards executivos

Python para Dados
├── Pandas
├── automação
├── ETL
└── análise exploratória
```

---

# Formação

**Ciência da Computação**
Centro Universitário UNIPÊ

Foco atual em dados, banco de dados, programação e desenvolvimento de soluções orientadas a informação.

---

# GitHub

![Arthur's GitHub stats](https://github-readme-stats.vercel.app/api?username=trindadearthur\&show_icons=true\&hide_border=true\&include_all_commits=true\&count_private=true)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=trindadearthur\&layout=compact\&hide_border=true)

---

# Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Arthur_Trindade-0A66C2?style=flat-square\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/arthur-cunha-trindade/)

[![GitHub](https://img.shields.io/badge/GitHub-trindadearthur-181717?style=flat-square\&logo=github\&logoColor=white)](https://github.com/trindadearthur)
