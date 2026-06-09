# market-segmentation-brazil
Identifying consumer market profiles across Brazil using public data and clustering techniques.
# Segmentação de Mercados e Potencial de Consumo no Brasil com Dados Públicos e Machine Learning

## Sobre o Projeto

Este projeto tem como objetivo identificar diferentes perfis de mercado entre os municípios brasileiros utilizando indicadores econômicos e demográficos públicos.

A partir da integração de bases de dados do IBGE e outras fontes oficiais, foi construída uma análise capaz de comparar municípios sob diferentes perspectivas, indo além de rankings simples de população ou PIB.

O resultado é uma segmentação de mercado baseada em dados, permitindo identificar municípios com características econômicas semelhantes e compreender melhor as diferenças existentes entre os mercados brasileiros.

---

## Problema de Negócio

Nem sempre os municípios mais ricos são os maiores mercados consumidores.

Da mesma forma, cidades com grande população nem sempre apresentam os maiores níveis de geração de riqueza.

Essa diferença pode impactar decisões relacionadas a:

* Expansão comercial
* Priorização de mercados
* Estudos de potencial de consumo
* Inteligência de Mercado
* Planejamento estratégico

O projeto busca responder justamente essa questão:

**Como identificar diferentes perfis de mercado utilizando dados públicos?**

---

## Fontes de Dados

Os dados utilizados foram obtidos a partir de bases públicas oficiais:

* IBGE – Produto Interno Bruto dos Municípios
* IBGE – Censo Demográfico
* Indicadores demográficos municipais

---

## Por que utilizar dados de 2022?

A escolha dos dados de 2022 foi intencional.

Embora existam indicadores mais recentes para algumas variáveis, 2022 representa o período mais recente em que as principais bases utilizadas possuíam compatibilidade metodológica e cobertura nacional completa.

Essa decisão permitiu realizar o cruzamento consistente entre informações econômicas e demográficas dos 5.570 municípios brasileiros, garantindo maior confiabilidade para a análise comparativa.

Em projetos de Inteligência de Mercado, consistência metodológica entre as fontes costuma ser mais importante do que utilizar indicadores isolados mais recentes.

---

## Metodologia

O projeto foi desenvolvido em sete etapas:

### 1. Coleta de Dados

Obtenção dos indicadores econômicos e demográficos em bases públicas oficiais.

### 2. Limpeza e Tratamento

Padronização dos dados e preparação das bases para integração.

### 3. Construção dos Indicadores

Cálculo do PIB per capita e criação de métricas auxiliares para análise de potencial de mercado.

### 4. Análise Exploratória

Investigação dos padrões econômicos e demográficos dos municípios brasileiros.

### 5. Clusterização

Aplicação do algoritmo K-Means para identificar grupos de municípios com características semelhantes.

### 6. Refinamento dos Clusters

Transformação logarítmica e padronização das variáveis para reduzir a influência de municípios extremos.

### 7. Visualização e Interpretação

Construção de gráficos e análise dos perfis de mercado identificados.

---

## Principais Resultados

A análise revelou quatro perfis distintos de mercado:

* Centros Econômicos e Mercados de Massa
* Mercados Tradicionais
* Mercados Regionais Especializados
* Mercados Produtivos de Baixa Densidade

Os resultados mostram que municípios com níveis semelhantes de riqueza podem apresentar estruturas de mercado completamente diferentes.

---

## Tecnologias Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Jupyter Notebook

---

## Estrutura do Projeto

```text
├── dados/
│   ├── brutos/
│   └── processados/
│
├── outputs/
│
├── 01_coleta_dados.ipynb
├── 02_limpeza_dados.ipynb
├── 03_modelagem_potencial_consumo.ipynb
├── 04_clusterizacao_mercados.ipynb
├── 05_refinamento_clusterizacao.ipynb
├── 06_visualizacao_executiva.ipynb
└── 07_conclusoes_estrategicas.ipynb
```

---

## Possíveis Aplicações

* Inteligência de Mercado
* Expansão Comercial
* Planejamento Territorial
* Marketing Analítico
* Estudos de Potencial de Consumo
* Segmentação de Mercados

---

## Autor

Jackelinne Rodrigues

MBA em Neurociência, Marketing e Consumo | Inteligência de Mercado | Marketing Analítico | Dados Públicos e Business Intelligence

LinkedIn:
https://linkedin.com/in/jacke-analytics
