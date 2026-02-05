# 📊 Análise de Performance de Vendas no Varejo de Moda

Este projeto tem como objetivo analisar a performance de vendas de um varejo de moda por meio de um dashboard interativo desenvolvido em **Power BI**, focando em indicadores-chave de negócio (KPIs), comportamento de produtos e evolução temporal das vendas.

O dashboard foi construído com foco em **clareza visual**, **análise exploratória** e **suporte à tomada de decisão**.
<img width="1412" height="650" alt="DashBoardImagem" src="https://github.com/user-attachments/assets/913b97cb-7a2a-4a0c-a2e9-ac797c261409" />


---

## 🎯 Objetivo do Projeto

- Analisar o desempenho geral de vendas do varejo de moda
- Identificar os produtos mais vendidos
- Avaliar a relação entre volume de vendas e avaliação média dos produtos
- Acompanhar a evolução das vendas ao longo do tempo (MoM)
- Gerar insights e recomendações estratégicas a partir dos dados

---

## 📌 Principais Medidas (DAX)

- **ValorTotalCompra**  
  Soma do valor total das compras realizadas.

- **Quantidade de Vendas**  
  Total de transações registradas.

- **TicketMedio**  
  Valor médio por venda, calculado a partir do total vendido dividido pela quantidade de vendas.

- **MediaRating**  
  Avaliação média dos produtos, normalizada para facilitar a análise.

- **Quantidade de Vendas MoM%**  
  Variação percentual da quantidade de vendas em relação ao mês anterior, utilizando inteligência de tempo.

---


## 📌 Principais KPI

- **Vendas Totais:** $430,95 mil  
- **Ticket Médio:** $156,71  
- **Quantidade de Vendas:** 2.750  
- **Rating Médio:** 2,7  

---

## 📈 Análises Realizadas

### 🔹 Produtos Mais Vendidos
Análise dos 5 produtos com maior volume de vendas, permitindo identificar os itens com maior impacto no faturamento.

### 🔹 Produtos com Melhor Avaliação Média
Ranking dos produtos mais bem avaliados pelos clientes, auxiliando na análise de qualidade percebida e satisfação.

### 🔹 Evolução das Vendas ao Longo do Tempo (MoM)
Análise da variação percentual das vendas mês a mês, evidenciando períodos de crescimento, queda e possíveis padrões sazonais.

### 🔹 Filtros Interativos
O dashboard permite segmentação por:
- Ano
- Mês
- Produto

Facilitando análises específicas e exploração dos dados.

---

## 💡 Principais Insights

- Os produtos mais vendidos **não são necessariamente os mais bem avaliados**, indicando um possível desalinhamento entre volume de vendas e satisfação do cliente.
- Produtos com melhor rating médio apresentam menor volume de vendas, sugerindo oportunidades de maior exposição ou estratégias de marketing.
- A variação mensal das vendas apresenta **alta volatilidade**, com quedas e picos significativos ao longo do período analisado.
- Existem meses com retração expressiva nas vendas, o que pode indicar sazonalidade, problemas de estoque ou impacto de campanhas.

---

## 🎯 Recomendações de Negócio

Com base nas análises realizadas, algumas recomendações estratégicas podem ser consideradas:

- **Revisar a qualidade ou fornecedores** dos produtos mais vendidos, buscando melhorar a satisfação do cliente.
- **Investir em campanhas de marketing** para produtos com alta avaliação, aumentando seu volume de vendas.
- Analisar em profundidade os períodos de queda nas vendas para identificar causas como:
  - falta de estoque
  - precificação
  - ausência de campanhas promocionais
- Utilizar o histórico de vendas para **planejamento de estoque** e definição de estratégias sazonais.

---

## 🛠️ Ferramentas Utilizadas

- Power BI
- Power Query (ETL)
- Visualização de Dados
- Análise Exploratória

---

## 📂 Estrutura do Repositório
📁 powerbi-varejo-moda
├── README.md
├── 📁 powerbi
│ └── dashboard_varejo_moda.pbix
├── 📁 images
│ └── dashboard_print.png
└── 📁 data
└── Fashion_Retail_Sales.csv


---

## 🔗 Dashboard Interativo

O dashboard foi desenvolvido em Power BI Desktop.  
O arquivo `.pbix` está disponível neste repositório para visualização local.
---

## 📬 Contato

Desenvolvido por **Cauã de Godoy**  
📌 Projeto para portfólio em Análise de Dados / Business Intelligence
Linkedin : https://www.linkedin.com/in/caua-de-godoy/
