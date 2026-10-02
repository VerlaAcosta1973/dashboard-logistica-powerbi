# dashboard-logistica-powerbi

# Business Intelligence aplicado à Logística e Controladoria de Frotas de Carga 🚚📊

Repositório de uma empresa logística (ficticia) que resolve a grande maioria das dores de coordenar e reduzir ao máximo os custos através de análises bem estruturadas no Power Bi

[![GitHub](https://shields.io)](https://github.com/VerlaAcosta1973/dashboard-logistica-powerbi)
[![LinkedIn](https://shields.io)](www.linkedin.com/in/verla-acosta-ramos)

## 🎯 1. Contexto de Negócio e Objetivo

No setor de transporte rodoviário de cargas de grande porte, a margem de lucro é diretamente pressionada pela volatilidade dos custos operacionais (combustível, manutenção e depreciação de ativos). O maior desafio das lideranças não é a falta de dados, mas sim a consolidação de relatórios isolados em ferramentas analíticas que permitam uma tomada de decisão rápida e baseada em fatos.

**O Objetivo deste Projeto:** Desenvolver uma solução analítica ponta a ponta (End-to-End) no **Power BI**, simulando um cenário real de controle de frotas, auditoria de custos e análise de rentabilidade de ativos de transporte por marcas e modelos.

---

## 📈 2. Arquitetura do Dashboard e Indicadores Chave (KPIs)

O painel é estruturado em três visões analíticas de alto impacto para a tomada de decisão gerencial:

### 🔹 Visão 1: Visão Geral (Performance Operacional)
Focada no fluxo de volume e receita bruta gerada pela movimentação de mercadorias.
*   **Métricas Consolidadas:** Faturamento Bruto de Frete de **R\$ 100,28 Milhões**, suportando a movimentação de **R\$ 552,08 Milhões em valor de mercadorias** através de **16.285 viagens**.
*   **Análise de Sazonalidade Temporal:** Gráficos comparativos de barras exibindo o volume de frete e quantidade de viagens mês a mês contra o período anterior, permitindo prever vales de demanda e planejar paradas de manutenção preventiva.
*   **Distribuição de Capacidade:** Análise de peso transportado (toneladas) segmentado pelas marcas de ativos (Mercedes-Benz liderando com 3,3 Mil toneladas).

### 🔹 Visão 2: Análise de Custos (Controladoria de Frota)
O coração financeiro do projeto, desenhado para monitorar a eficiência de custos por quilômetro e toneladas movimentadas.
*   **Indicadores de Eficiência:** Custo Total de **R\$ 1,43 Milhão** distribuído em uma frota de **50 veículos ativos**.
*   **Métricas Unitárias:** Custo Total por Quilômetro de **R\$ 4,69** e Custo por Tonelada de **R\$ 119,74** — KPIs essenciais para calibrar a precificação de fretes e propostas comerciais.
*   **Gráfico de Área (Custo Fixo vs. Custo Variável):** Exibição da evolução temporal das despesas. Demonstra visualmente picos de custos variáveis (como combustível e manutenções corretivas em rodovias, atingindo pico de R\$ 116 Mil em novembro), permitindo auditorias minuciosas na conta de despesas de viagem.

### 🔹 Visão 3: Análise de Veículos (Rentabilidade e Margem)
Matriz cruzada que avalia a performance líquida real de cada ativo da frota de forma granular.
*   **Métrica de Lucro Final:** Apresentação do ganho líquido consolidado de **R\$ 98,84 Milhões**.
*   **Detalhamento Matricial por Marca e Categoria:** Divisão hierárquica por fabricantes (Ford, Iveco, Mercedes-Benz, Volvo, Scania, Volkswagen) abrindo em subcategorias de chassis (3/4, Carreta, Toco, Truck). Permite aos gestores identificar quais combinações de veículos geram as melhores margens de lucro final com base na quilometragem percorrida (`Km percorridos`) e custo operacional.

---

## 🛠️ 3. Engenharia de Dados Aplicada (ETL & Modelagem)

Para garantir a precisão contábil e a velocidade das consultas visuais, o projeto envolveu processos estruturados de:
*   **Tratamento de Dados (Power Query):** Limpeza de registros de viagens, tratamento de valores nulos e tipagem correta de variáveis geográficas e temporais.
*   **Modelagem de Dados Relacional:** Estruturação de relacionamentos (1 para Muitos) baseados em conceitos de Bancos de Dados (Chaves Primárias e Estrangeiras) conectando tabelas dimensionais de veículos à tabela de fatos de movimentação financeira.
*   **Linguagem DAX:** Desenvolvimento de medidas calculadas para comparações de períodos acumulados (Mês Atual vs. Mês Anterior) e métricas de rateio de custos.

---
*Projeto desenvolvido por **Verlã Acosta Ramos** — Graduando em Ciências Contábeis com vivência em logística internacional e análise de custos.*
