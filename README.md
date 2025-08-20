# 🛒 Olist – Análise de Vendas no Power BI

## 📌 Sobre o Projeto

Este projeto tem como objetivo analisar os **dados de pedidos da Olist Store** utilizando o **Power BI**, integrando múltiplas fontes de dados e aplicando conceitos de **ETL, modelagem, medidas DAX e storytelling com dados**.

A proposta é transformar dados brutos em **dashboards interativos** que auxiliam na tomada de decisão, trazendo insights sobre clientes, produtos, formas de pagamento e desempenho de vendas.

---

## 🗄️ Estrutura dos Dados

As bases utilizadas foram:

- **Itens dos Pedidos** (`olist_itens_pedidos.csv`) → Detalhes de cada item comprado.  
- **Pedidos** (`olist_pedidos.xlsx`) → Informações gerais de cada pedido (datas, status, cliente).  
- **Pagamentos** (`olist_pagamentos.xml`) → Tipos de pagamento, valores e número de parcelas.  
- **Produtos** (`olist_produtos.json`) → Catálogo de produtos e categorias.  
- **Tema** (`Tema.json`) → Padronização de cores e identidade visual.  

Cada dataset foi tratado no **Power Query** para garantir consistência, normalização e relacionamento entre as tabelas.

---

## 📊 Estrutura do Dashboard

O relatório foi dividido em diferentes perspectivas:

- **📦 Produtos** → Categorias mais vendidas, volume de itens e ticket médio.  
- **💳 Pagamentos** → Distribuição por método de pagamento (cartão, boleto, voucher) e número médio de parcelas.  
- **📈 Vendas no Tempo** → Evolução mensal de faturamento e sazonalidade.  
- **👥 Clientes** → Padrões de compra e comportamento de consumo.  
- **🛒 Carrinho de Compras** → Valor médio por pedido e combinações de itens.  

---

## ▶️ Como Executar

1. Clone este repositório.  
2. Abra o arquivo `PowerBi Projeto.pbix` no **Power BI Desktop**.  
3. Certifique-se de que os arquivos de dados (`CSV`, `XLSX`, `XML`, `JSON`) estejam no mesmo diretório para manter os relacionamentos.  
4. Navegue pelas páginas do dashboard para explorar as análises.  

---

## 🚀 Tecnologias Utilizadas

- **Power BI Desktop**  
- **Power Query (ETL)**  
- **DAX (Data Analysis Expressions)**  
- **Modelagem Relacional**  
- **Arquivos CSV, Excel, XML e JSON**  

---

## 📌 Objetivo de Aprendizado

Este projeto foi desenvolvido para praticar:

- Integração de múltiplas fontes de dados.  
- Modelagem de dados no Power BI.  
- Criação de medidas e KPIs em DAX.  
- Design de dashboards interativos e responsivos.  
- Comunicação visual de insights para tomada de decisão.  

---

