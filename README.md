# Dengue_Municipio

Análise da incidência de dengue nos 645 municípios do estado de São Paulo (2013–2023): contagem de casos, taxa de infecção e evolução ano a ano, com Python e pandas. Desafio de Análise de Dados e Storytelling da pós em Data Analytics (FIAP), aplicando CRISP-DM/KDD. Em andamento.

## Pergunta norteadora
Como evoluíram, ano a ano, a contagem de casos e a taxa de infecção de dengue nos municípios do estado de São Paulo entre 2013 e 2023?

## Objetivo
Identificar aumento ou diminuição dos casos de dengue ao longo dos anos, para apoiar a área da saúde na tomada de providências na condução dos casos.

## Status
- [x] Etapa 1: definição do problema
- [x] Etapa 2: coleta e exploração dos dados
- [ ] Etapa 3: análise e geração de insights (contagem por ano, taxa de infecção, visualizações)
- [ ] Etapa 4: conclusões e recomendações
- [ ] Etapa 5: relatório em PDF

## Principais achados até agora
- A base de SP tem 85.140 linhas: 645 municípios × 132 meses (jan/2013 a dez/2023), sem valores nulos nem duplicados.
- Mais da metade dos registros mensais tem zero casos, e poucos picos são muito altos.
- O maior valor é da cidade de São Paulo em março de 2015 (19.584 casos), compatível com uma epidemia.

## Premissas e limitações
- `qtd_infeccoes` é tratada como casos confirmados, conforme o enunciado do desafio.
- A base fornecida não traz população, então o cálculo da taxa depende de uma fonte externa.

## Dados
A base (`Base de Dados Dengue.xlsx`) foi fornecida pela disciplina e **não está incluída** neste repositório.

## Como executar
1. Abra o notebook `Dengue_Municipio.ipynb` no Google Colab.
2. Faça upload do arquivo `Base de Dados Dengue.xlsx` no ambiente do Colab.
3. Execute as células em ordem.

## Ferramentas
Python, pandas, NumPy, Matplotlib, Seaborn e Plotly.

## Autora
Camila Fontes · [LinkedIn](https://www.linkedin.com/in/camilajfontes)
