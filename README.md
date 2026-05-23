# saude-mental-rs
Análise de internações por saúde mental no RS (2018-2023) usando Excel, Power Query e Power BI
# 🧠 Saúde Mental no RS — Análise de Internações 2018-2023

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![DATASUS](https://img.shields.io/badge/Fonte-DATASUS-blue?style=for-the-badge)

## 📋 Sobre o Projeto

Análise exploratória das internações por transtornos mentais e comportamentais (CID-10: F00–F99) no estado do Rio Grande do Sul entre 2018 e 2023, utilizando dados públicos do SUS.

## 🎯 Objetivos

- Analisar a evolução das internações por saúde mental no RS ao longo de 6 anos
- Identificar os diagnósticos mais frequentes
- Traçar o perfil dos pacientes internados (sexo e faixa etária)
- Mapear os municípios com maior concentração de casos

## 📊 Principais Insights

- **226.937 internações** por transtornos mentais no RS entre 2018 e 2023
- **Queda de 19%** nas internações em 2020-2021, coincidindo com a pandemia de COVID-19
- **Transtornos de humor** (depressão, bipolar) são o diagnóstico mais frequente — 73.684 casos
- **60% dos pacientes são do sexo masculino**
- Faixas etárias de **20 a 49 anos** concentram a maioria das internações
- **Porto Alegre** lidera com quase 40 mil internações no período

## 🛠️ Ferramentas Utilizadas

- **Excel + Power Query** — coleta, limpeza e transformação dos dados
- **Power BI Desktop** — criação do dashboard interativo
- **DATASUS/TABNET** — fonte dos dados públicos de saúde

## 📁 Estrutura do Projeto

📁 saude-mental-rs/
├── 📊 SMRS.pbix              ← Dashboard Power BI
├── 📋 saude_mental_rs.xlsx   ← Dados tratados no Excel
└── 📖 README.md

## 🗂️ Páginas do Dashboard

| Página | Descrição |
|---|---|
| Visão Geral | Total de internações e evolução temporal |
| Perfil do Paciente | Análise por sexo, faixa etária e diagnóstico |
| Distribuição Geográfica | Top 20 municípios com mais internações |
| Diagnósticos por Ano | Evolução dos principais diagnósticos 2018-2023 |

## 📥 Fonte dos Dados

Ministério da Saúde — Sistema de Informações Hospitalares do SUS (SIH/SUS)  
Acesso via [DATASUS TABNET](http://tabnet.datasus.gov.br)  
Capítulo CID-10: V — Transtornos Mentais e Comportamentais (F00–F99)

## 👩‍💻 Autora

**Camila Fernanda Henz dos Santos**  
[LinkedIn](https://linkedin.com/in/camila-henz-114715202/) | [GitHub](https://github.com/CamiHenz93)
