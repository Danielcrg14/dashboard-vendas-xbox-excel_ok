# Dashboard de Vendas — Xbox (Excel)

Dashboard de vendas desenvolvido no **Microsoft Excel**, usando **Tabelas Dinâmicas**, **Segmentação de Dados** e indicadores (KPIs) para transformar uma base bruta em informações visuais úteis para decisão.

---

## 🎯 Objetivo
Criar um dashboard que permita analisar o desempenho de vendas de assinaturas e add-ons do ecossistema Xbox, com filtros por tipo de assinatura.

---

## 📁 Dados utilizados
Arquivo: `base.xlsx`

Campos principais:
- **Subscription Type** (Monthly / Quarterly / Annual)
- **Plan** (Core / Standard / Ultimate)
- **Total Value** (valor total considerando itens e desconto)
- **EA Play Season Pass Price**
- **Minecraft Season Pass Price**
- **Auto Renewal** (Yes/No)
- **Subscriber ID** (contagem de assinantes)

---

## 📊 O que o dashboard responde (insights)
O painel permite visualizar rapidamente:

### 1) Receita Total (por tipo de assinatura)
Card **Xbox Game Pass** mostra a soma do **Total Value** filtrado por *Subscription Type*.

### 2) Receita de Add-ons
Cards mostram a receita total dos add-ons:
- **EA Play Season Pass**
- **Minecraft Season Pass**

### 3) Renovação automática (previsibilidade)
Gráfico **Auto Renewal (Yes/No)** mostra quanto da receita vem de assinaturas com renovação automática.

### 4) Receita por Plano (mix de produto)
Gráfico **Revenue by Plan** mostra a distribuição de receita entre:
- Core / Standard / Ultimate

### 5) Volume e Ticket Médio
- **Subscribers**: quantidade de assinantes no filtro atual
- **ARPU**: receita total / número de assinantes

---

## 🧠 Como usar
1. Abra `dashboard_xbox_desafio.xlsx`
2. Vá até a aba **Dashboard**
3. Use o filtro **Subscription Type** (Monthly/Quarterly/Annual)
4. Os cards e gráficos atualizam automaticamente

---

## 🗂️ Estrutura do repositório
.
├── base.xlsx
├── dashboard_xbox_desafio.xlsx
├── README.md
└── images/
└── dashboard.png


---

## 🖼️ Preview

![Dashboard Preview](images/dashboard.png)
