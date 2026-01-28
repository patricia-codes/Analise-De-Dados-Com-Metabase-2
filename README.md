# 📊 Dashboard Analítico de Pedidos — Metabase (Escola DNC)
### Projeto de Análise de Dados utilizando Metabase + Dataset da DNC

![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)
![Ferramentas](https://img.shields.io/badge/Metabase-Analytics-blue)
![Licença](https://img.shields.io/badge/License-MIT-lightgrey)
![Linguagem](https://img.shields.io/badge/Documentação-Markdown-yellow)

---

## 📝 Descrição do Projeto

Este projeto apresenta uma **análise exploratória e visual de pedidos e faturamento**, desenvolvida a partir de dados extraídos de um banco de dados da Escola DNC.  
O objetivo é fornecer **insights estratégicos** sobre faturamento, clientes, vendas com e sem desconto e volume de produtos vendidos ao longo do tempo.

---

## 🎯 Objetivo do Projeto

- Analisar o desempenho financeiro mensal
- Avaliar o impacto dos descontos nas vendas
- Entender o comportamento dos clientes ao longo do tempo
- Identificar tendências de faturamento e volume de vendas

---

## 🗂️ Fonte dos Dados

Os dados utilizados neste projeto foram extraídos do **Metabase**, a partir de um banco de dados disponibilizado para fins educacionais pela **DNC**.

🔗 Ambiente de dados:  
https://dex.dnc.group/browse 

📄 **Tabela analisada:** `Orders`

### Principais campos utilizados:
- `Created At` – Data do pedido  
- `Total` – Valor total do pedido  
- `Tax` – Valor de taxas  
- `Discount` – Valor de desconto  
- `Quantity` – Quantidade de itens  
- `User ID` – Identificação do cliente  
- `Product ID` – Identificação do produto  

---

## 📌 Principais KPIs

- 💰 **Faturamento Bruto:** `R$ 1.510.621,68`
- 🧾 **Total de Taxas:** `R$ 72.388,34`
- 🔖 **Desconto Total:** `R$ 9.924,83`
- 🛒 **Quantidade de Vendas sem Desconto:** `16.848`
- 🛍️ **Quantidade de Vendas com Desconto:** `1.912`

---

## 📈 Análises Realizadas

### 1️⃣ Faturamento Mensal
- O faturamento mensal se mantém relativamente estável ao longo de 2019
- O pico ocorre no início de 2020, indicando um possível aumento sazonal
- Em abril de 2020, observa-se uma queda significativa no faturamento

### 2️⃣ Clientes Ativos por Mês
- Média mensal entre **420 e 470 clientes**
- Janeiro de 2020 apresenta o maior número de clientes ativos
- Queda acentuada em abril de 2020, acompanhando a redução de faturamento

### 3️⃣ Quantidade de Produtos Vendidos
- Crescimento expressivo entre abril e agosto de 2019
- Pico de vendas em meados de 2019
- Redução gradual no final de 2019 e início de 2020

### 4️⃣ Vendas com vs. sem Desconto
- A maioria das vendas ocorre **sem desconto**
- Os descontos representam uma parcela pequena do total de vendas
- Indica que o faturamento não depende fortemente de políticas agressivas de desconto

---

## 🔍 Insights Estratégicos

- 📌 O negócio apresenta **estabilidade financeira**, com variações previsíveis ao longo dos meses
- 📌 Descontos não são o principal motor de vendas
- 📌 Existe uma possível **sazonalidade positiva no meio do ano**
- 📌 A queda em abril de 2020 pode indicar impacto de fatores externos ou mudança de comportamento do consumidor

---

## 🛠️ Ferramentas Utilizadas

- **Metabase** – Criação do dashboard e visualizações
- **Excel** – Exportação e apoio na análise dos dados
- **GitHub** – Versionamento e documentação do projeto

---

## 🖼️ Visual do Dashboard

![Dashboard de Pedidos](./Dashboard%20de%20Pedidos.png)

---


✨ *Projeto desenvolvido para fins educacionais e portfólio em Análise de Dados.*
