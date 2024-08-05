<div align="center">
    <img src="logo_pycats.png" alt="Logo PyCats" width= "30%">
</div>

# Análise da Eficiência do Sono
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)

![GitHub](https://img.shields.io/github/license/atlantico-academy/equipe1-2024.2.svg) [![PyPI](https://img.shields.io/pypi/v/atlantico-academy-equipe2-2024.1.svg)](http://pypi.org/project/atlantico-academy-equipe2-2024.1/) [![GitHub last commit](https://img.shields.io/github/last-commit/atlantico-academy/equipe1-2024.2.svg)](https://github.com/atlantico-academy/equipe1-2024.2/commit/developer)

## Base de Dados
<p align="justify">No estudo, foi utilizado o conjunto de dados <a href="https://www.kaggle.com/datasets/equilibriumm/sleep-efficiency">Sleep Efficience</a>, disponível no Kaggle. A base de dados contém informações sobre idade, gênero, horários de dormir e acordar, duração do sono, porcentagem de sono leve, profundo e REM, número de despertares, consumo de cafeína e álcool, status de tabagismo e frequência de exercícios.</p>

## Objetivo do Projeto

<p align="justify"> O objetivo deste projeto é analisar e identificar padrões e correlações entre a eficiência do sono e diversos fatores de estilo de vida, como rotinas e hábitos de consumo. Essas informações podem oferecer insights valiosos sobre os principais aspectos que influenciam a qualidade do sono.</p> 
    
## Justificativa do Projeto

<p align="justify"> A qualidade do sono é essencial para a saúde e o bem-estar físico, mental e emocional, além de fortalecer o sistema imunológico, previne doenças e desempenhar um papel crucial no bom funcionamento do cérebro. Dormir mal pode afetar a produtividade e aumentar o risco de <strong>doenças cardiovasculares, doenças metabólicas e distúrbios mentais.</strong> 

A análise da eficiência do sono, considerando fatores, como idade, gênero, horários de dormir, duração do sono, porcentagens de sono leve, profundo e REM, quantidade de despertares durante a noite, consumo de cafeína e álcool, tabagismo e prática de exercícios físicos, pode contribuir para o desenvolvimento de estratégias que melhorem a qualidade do sono e a saúde em geral. Com base nos dados coletados, este projeto visa identificar insights e padrões úteis que possam ser aplicados por especialistas em saúde, pesquisadores e pelo público em geral, fornecendo uma base sólida para intervenções personalizadas.</p>

## Resumo Gráfico
<div align="center">
    <img src="resumo_grafico.png" alt="Resumo Gráfico">
</div>


## Desenvolvedores
 - [Beatriz Eduão](https://github.com/beduao)
 - [Gessyca Moraes](https://github.com/gessycamayhara)
 - [Kesava Menezes](https://github.com/KesavaS2)
 - [Ricardo Franco](https://github.com/francocontigo)
 - [Vitor Pires](https://github.com/vikpires)
 
 ## Organização de Diretórios
 
```
├── data/              # Diretório contendo todos os arquivos de dados
│   ├── external/      # Arquivos de dados de fontes externas
│   ├── interim/       # Arquivos de dados intermediários
│   ├── processed/     # Arquivos de dados processados
│   └── raw/           # Arquivos de dados originais, imutáveis
├── docs/              # Documentação gerada através da biblioteca mkdocs
├── models/            # Modelos treinados e serializados, predições ou resumos de modelos
├── notebooks/         # Diretório contendo todos os notebooks utilizados nos passos
├── references/        # Dicionários de dados, manuais e todo o material exploratório
├── src/               # Código fonte utilizado nesse projeto
│   ├── data/          # Classes e funções utilizadas para download e processamento de dados
│   ├── deployment/    # Classes e funções utilizadas para implantação do modelo
│   └── model/         # Classes e funções utilizadas para modelagem
├── app.py             # Arquivo com o código da aplicação do streamlit
├── Procfile           # Arquivo de configuração do heroku
├── pyproject.toml     # Arquivo de dependências para reprodução do projeto
├── poetry.lock        # Arquivo com sub-dependências do projeto principal
├── README.md          # Informações gerais do projeto
└── tasks.py           # Arquivo com funções para criação de tarefas utilizadas pelo invoke
```