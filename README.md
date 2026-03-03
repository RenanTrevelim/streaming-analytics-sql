# 📊 Streaming Data Analytics  
### SQL + Python + PostgreSQL

Projeto de análise de dados de uma plataforma de streaming com foco em **métricas de engajamento, consumo e comportamento de usuários**.

Este repositório demonstra a aplicação de **SQL avançado (CTEs, agregações, filtros temporais)** integrado ao ecossistema Python para geração de insights analíticos e visualizações.

---

## 🎯 Objetivo do Projeto

Transformar dados relacionais em indicadores estratégicos que permitam responder perguntas como:

- Quais conteúdos geram maior engajamento?
- Usuários mais ativos concentram-se em quais planos?
- Existe sazonalidade no consumo?
- Avaliações refletem popularidade?
- Existe relação entre tempo assistido e nota média?

---

## 🧠 Metodologia

A análise segue três etapas principais:

### 1️⃣ Extração de Dados (SQL)

- Uso de `JOIN`, `GROUP BY`, `ORDER BY`
- CTEs (`WITH`) para organização lógica
- Filtros temporais por ano/mês
- Cálculo de métricas agregadas
- Aplicação de thresholds mínimos (ex.: mínimo de avaliações)

### 2️⃣ Transformação e Análise (Python)

- Manipulação com **Pandas**
- Criação de métricas derivadas
- Ordenação e filtragem estratégica
- Preparação de dados para visualização

---

## 📈 Principais Análises Desenvolvidas

- 🎬 Top conteúdos por tempo total assistido
- ⭐ Ranking por média de avaliação (com mínimo de avaliações)
- 👤 Usuários mais ativos por período
- 📅 Evolução mensal de visualizações
- 💳 Engajamento por tipo de plano
- 🌍 Distribuição geográfica de usuários
- 📊 Relação entre número de visualizações e avaliações

