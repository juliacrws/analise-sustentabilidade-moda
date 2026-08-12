# 🌿 O Paradoxo da Sustentabilidade na Moda: Uma Análise de Dados

## 🔗 Links Oficiais do Projeto
* **Repositório GitHub:** [Acessar Projeto](https://github.com/juliacrws/analise-sustentabilidade-moda)
* **Notebook Interativo:** [Visualizar no Google Colab](https://colab.research.google.com/drive/17HPWz14NIcj7Yc_pnwCuqtrUvfsg7KYv?usp=sharing)
* **Dataset Original:** [Sustainable Fashion: Eco-Friendly Trends (Kaggle)](https://www.kaggle.com/datasets/waqi786/sustainable-fashion-eco-friendly-trends)

## 📌 Visão Geral
Este projeto realiza uma Análise Exploratória de Dados (EDA) para investigar o impacto ambiental da indústria têxtil. O objetivo principal foi testar a hipótese de que marcas com altas Classificações de Sustentabilidade (Rating A) consomem menos recursos naturais absolutos do que marcas com classificações ruins (Rating D). 

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** Python 3
* **Bibliotecas:** `pandas`, `matplotlib`, `seaborn`
* **Ambiente:** Jupyter Notebook / Google Colab

## 📊 Sobre a Base de Dados
Os dados utilizados contêm 5.000 registros reais de marcas globais, mensurando emissões em Toneladas Métricas (MT) e consumo hídrico em Litros. A fonte pública garante a reprodutibilidade da análise.

## 🧠 Metodologia de Limpeza e Estruturação
O pipeline de pré-processamento seguiu rigorosas práticas de Engenharia de Dados:
* Identificação e remoção de registros duplicados (`.drop_duplicates()`).
* Tratamento de valores nulos nas colunas focais (`.dropna()`).
* Padronização categórica utilizando métodos de string (`.str.strip().str.upper()`).
* Lógica condicional automatizada para geração de insights estatísticos no terminal.

## 💡 Principais Insights: A Quebra de Paradigma
A análise estatística revelou um cenário contra-intuitivo e derrubou a hipótese inicial:
1. **A Ilusão do Volume Absoluto:** Não há redução substancial no volume absoluto de recursos consumidos. A diferença de consumo hídrico entre a melhor e a pior nota é de apenas ~2%.
2. **O Paradoxo do Consumo:** Marcas com nota máxima ('A') apresentaram um consumo médio de água e emissão de carbono *ligeiramente superiores* às marcas de nota 'D' (Ex: 253.6 MT vs 248.7 MT em Carbono).
3. **Conclusão de Negócios:** O *Rating* de sustentabilidade do mercado avalia as práticas relativas (ex: uso de energia limpa, materiais recicláveis) e não o volume de produção total. Corporações globais "verdes" produzem em uma escala tão massiva que seu impacto ambiental absoluto continua sendo superior ao de operações menores e menos eficientes (Nota D).

---
*Desenvolvido por Julia de Moraes Barbosa*
