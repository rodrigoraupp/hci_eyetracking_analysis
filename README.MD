# 👀 UEyes - Análise de Conjunto de Dados Sobre Rastreamento Ocular em Diferentes Interfaces

## Sobre o Projeto

Este projeto analisa o comportamento visual e a carga cognitiva de usuários durante a interação com diferentes tipos de interfaces (Web, Mobile, Desktop e Poster). Utilizando dados reais de rastreamento ocular (eye-tracking), o estudo investiga a transição entre a fase exploratória (primeiros 3,5 segundos) e a fase de atenção sustentada (após 3,5 segundos).

O objetivo principal é entender como diferentes layouts de UIs afetam a exploração visual e o esforço cognitivo do usuário, extraindo métricas oculares de coordenadas espaciais.

## 📂 Estrutura do Repo

```
📦 repo
 ┣ 📂 data/               # Conjuntos de dados brutos e processados (.parquet / .csv)
 ┣ 📂 notebooks/          # Pipeline de engenharia e análise de dados
 ┃ ┣ 📓 01_preprocess.ipynb
 ┃ ┣ 📓 02_cleaning.ipynb
 ┃ ┗ 📓 03_analysis.ipynb
 ┣ 📜 .gitignore          # Arquivos ignorados pelo Git (ex: dados muito grandes)
 ┗ 📜 README.md           # Documentação do projeto
```

## Fonte dos Dados

Os dados brutos de rastreamento ocular utilizados nesta análise são provenientes do dataset UEyes 

 - 🔗 **Referência do projeto original**: https://userinterfaces.aalto.fi/ueyeschi23


*Projeto desenvolvido como parte do Trabalho de Conclusão de Curso em Ciência da Computação pela Universidade Federal de Pelotas em 2026.*