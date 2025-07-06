# 📊 Mini Projeto: Análise de Crédito

Este projeto é um estudo simples para praticar **ETL com Python**, criação de **KPIs** e visualização de dados com **Power BI**, alinhado com desafios reais da área de Crédito e Cobrança.

---

## 📂 **Dados**

- `clientes_exemplo.csv` → base bruta (10 registros fictícios)
- `clientes_tratados.csv` → base limpa, com faixa etária criada via Pandas

---

## ⚙️ **Passos**

1️⃣ Extração: leitura do CSV original no **Python (Pandas)**  
2️⃣ Transformação: verificação de tipos, estatísticas (`describe`), criação de coluna `faixa_etaria`  
3️⃣ Cálculo de indicadores (ex: média por risco)  
4️⃣ Carga: exportação de CSV tratado  
5️⃣ Visualização: criação de painel no **Power BI** com:
   - Card: % de clientes com risco alto
   - Card: valor total de crédito concedido
   - Gráfico: valor médio de crédito por faixa etária

---

## 📸 **Dashboard**

![Dashboard](imagens/dashboard_print.png)

---

## 📈 **Principais Insights**

- **50%** dos clientes simulados possuem risco de crédito **alto**
- O total concedido simulado é **40 mil**
- As faixas **31–45** e **46–60** concentram os maiores valores médios de crédito (~4,9 mil)
- Jovens (18–30) têm valores médios significativamente menores

---

## 🚀 **Tecnologias Usadas**

- Python (Pandas)
- Google Colab
- Power BI
- Git/GitHub

---

## 💡 **Notas**

📌 Projeto **fictício**, apenas para fins de **estudo e portfólio**.

---

## 📬 **Contato**

📌 [LinkedIn](https://www.linkedin.com/in/lesley-damaceno/)  

---
