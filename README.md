# 📊 Análise do Ecossistema E-commerce Olist — Tech Challenge FIAP (Fase 1)

> **Projeto de Pós-Graduação em Data Analytics — FIAP**  
> *Estudo focado no comportamento de vendas, sazonalidade e análise da concentração de receita entre vendedores no marketplace Olist.*

---

## 📌 Visão Geral do Projeto

Este repositório contém a solução desenvolvida para a Fase 1 do **Tech Challenge** da FIAP. O objetivo principal foi realizar uma análise exploratória de dados (EDA) profunda e quantitativa a partir das bases de dados do e-commerce Olist.

A análise abrange todo o pipeline de dados:
1. **Sanitização e Tratamento de Dados (ETL):** Limpeza, tipagem correta de variáveis temporárias/financeiras e cruzamento relacional dos dados.
2. **Análise Temporal e Sazonalidade:** Estudo da evolução mensal do faturamento (2017–2018), identificação de picos de vendas (*Black Friday*) e variação do ticket médio.
3. **Distribuição e Concentração de Sellers:** Aplicação da **Curva de Pareto (Regra 80/20)**, **Índice de Gini** e **HHI (Herfindahl-Hirschman Index)** para mensurar a dependência da plataforma em relação aos maiores vendedores.

---

## 🛠️ Tecnologias Utilizadas
- **Linguagem:** Python 3.10+
- **Manipulação de Dados:** Pandas, NumPy
- **Visualização de Dados:** Matplotlib, Seaborn
- **Ambiente de Desenvolvimento:** Google Colab
- **Controle de Versão:** Git & GitHub

---

## 📂 Estrutura do Repositório

Os slides de apresentação e relatórios detalhados deste projeto encontram-se na pasta [docs/](./docs). 

```text
fiap-tech-challenge-olist/
│
├── data/                  # Bases de dados tratadas (.csv / parquet)
├── notebooks/             # Notebooks Python (.ipynb) com EDA e código completo
├── outputs/               # Gráficos em alta resolução e tabelas de resumo exportadas
├── .gitignore             # Regras para ignorar dados locais e arquivos temporários
├── requirements.txt       # Bibliotecas e dependências do projeto
└── README.md              # Documentação principal