# 🍷Análise Avançada de Qualidade de Vinhos com PySpark e Databricks

## 📌 Visão Geral
Este projeto apresenta uma análise completa de conjuntos de dados sobre qualidade de vinhos (tintos e brancos) utilizando PySpark no ambiente Databricks. O trabalho abrange desde a ingestão e preparação dos dados até análises estatísticas avançadas e modelagem de machine learning, seguindo as melhores práticas de engenharia de dados.

## 🧠 Objetivos Principais
- Demonstrar um fluxo completo de processamento de dados com PySpark
- Implementar boas práticas de engenharia de dados no Databricks
- Realizar análises comparativas entre vinhos tintos e brancos
- Desenvolver um modelo preditivo para classificação de qualidade
- Documentar um projeto profissional para portfólio

## 📊 Conjunto de Dados
### O projeto utiliza dois conjuntos de dados públicos:

- Vinho Tinto: 1,599 amostras

- Vinho Branco: 4,898 amostras

- Cada amostra contém 11 atributos físico-químicos e uma avaliação de qualidade (escala de 0-10).

- Atributos: Acidez fixa, acidez volátil, ácido cítrico, açúcar residual, cloretos, dióxido de enxofre livre, dióxido de enxofre total, densidade, pH, sulfatos, álcool.

## 🛠️ Tecnologias Utilizadas
- PySpark: Processamento distribuído de dados

- Databricks: Plataforma de análise unificada

- Delta Lake: Armazenamento de tabelas otimizadas

- Matplotlib/Seaborn: Visualização de dados

- Scikit-learn: Modelagem de machine learning

## 🏗️ Arquitetura do Projeto

### graph TD
     A[Ingestão de Dados] --> B[Preparação e Limpeza]
     B --> C[Armazenamento Delta Lake]
     C --> D[Análise Exploratória]
     D --> E[Engenharia de Features]
     E --> F[Modelagem Preditiva]
     F --> G[Visualização de Resultados]
     G --> H[Documentação]

## 🔍 Principais Análises Realizadas
### Análise Comparativa:

- Distribuição de qualidade entre tintos e brancos

- Comparação de componentes químicos

- Correlação entre atributos e qualidade

### Insights Chave:

- Vinhos com maior teor alcoólico tendem a ter melhor avaliação

- Acidez volátil apresenta correlação negativa com qualidade

- Vinhos brancos têm maior concentração de açúcar residual

### Modelo Preditivo:

- Random Forest para classificação de qualidade

- Acurácia de 78% na categorização (baixa/média/alta qualidade)

## 📂 Estrutura do Repositório

 /wine-quality-analysis/
├── notebooks/                 **Notebooks Databricks**
- │      ├── 01_data_ingestion.py
-  │     ├── 02_data_processing.py
-  │     ├── 03_analysis.py
-  │     └── 04_modeling.py
   - ├── data/                     **Dados processados**
-  ├── docs/                      **Documentação adicional**
-  ├── images/                    **Visualizações geradas**
-  ├── LICENSE
-  └── README.md                  **Este arquivo**

## 🚀 Como Executar
### Pré-requisitos:

- Conta no Databricks (Community Edition ou superior)
- Cluster Databricks com runtime ≥ 10.4 LTS
- Acesso ao dataset /databricks-datasets/wine-quality/

### Execução:

### Clone o repositório
- git clone https://github.com/seu-usuario/wine-quality-analysis.git

### Importe os notebooks para seu workspace Databricks

## 📈 Resultados e Conclusões
### Principais descobertas:

- Qualidade Média: Vinhos brancos (5.88) vs tintos (5.63)

- Fator Determinante: Teor alcoólico mostrou maior correlação com qualidade

- Modelo: RF alcançou 78% de acurácia na classificação

### Aplicações práticas:

- Controle de qualidade na produção

- Otimização de blends

- Previsão de avaliações de novos vinhos

## 🤝 Contribuição
### Contribuições são bem-vindas! Siga os passos:

- Fork o projeto
- Crie sua branch (git checkout -b feature/AmazingFeature)
- Commit suas mudanças (git commit -m 'Add some AmazingFeature')
- Push para a branch (git push origin feature/AmazingFeature)
- Abra um Pull Request

## 📜 Licença
### Distribuído sob a licença MIT. Veja LICENSE para mais informações.

## ✉️ Contato
**Link do Projeto:** https://github.com/seu-usuario/wine-quality-analysis
