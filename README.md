# 🍺 EDA — Mercado de Cervejas (Beer Reviews Dataset)

Análise exploratória de 1,5 milhão de avaliações de cervejas coletadas entre 1996 e 2012,
com foco em qualidade sensorial, estilos e cervejarias.

## Objetivo

Identificar padrões de qualidade, preferências por estilo e o papel do ABV na percepção
sensorial — aplicável a contextos de controle de qualidade e análise de mercado no setor
de bebidas.

## Dataset

- **Fonte:** [Beer Reviews — Kaggle](https://www.kaggle.com/datasets/rdoume/beerreviews)
- **Volume:** 1.586.614 reviews | 56.847 cervejas | 5.742 cervejarias | 104 estilos
- **Período:** 1996 – 2012

## Principais Insights

- **American IPA** domina em volume de avaliações, reflexo do boom do movimento craft beer
- **ABV não determina qualidade** — correlação praticamente nula com a nota geral
- **Sabor e paladar** são as dimensões sensoriais com maior correlação com a nota overall
- **Brouwerij Westvleteren** lidera em nota média entre cervejarias com volume relevante
- Volume de reviews cresce consistentemente até 2011 — queda em 2012 é artefato de coleta

## Stack

- Python 3.x | Pandas | NumPy | Matplotlib | Seaborn | Plotly

## Estrutura
01_eda_cervejas_brasil/
├── data/
│   ├── raw/          # dataset original (não versionado)
│   └── processed/    # dados tratados
├── notebooks/
│   └── 01_eda.ipynb
├── reports/
│   └── figures/
├── requirements.txt
└── README.md

## Como Reproduzir

```bash
pip install -r requirements.txt
# Baixar o dataset em data/raw/ antes de executar o notebook
```

## Contexto Profissional

Projeto desenvolvido como parte de portfólio de transição para dados,
com background em controle de qualidade no setor de bebidas (ISO 9001, CEP, INMETRO).