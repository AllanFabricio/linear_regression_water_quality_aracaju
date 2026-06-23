# linear_regression_water_quality_aracaju
Análise preditiva da qualidade da água das praias de Aracaju utilizando Regressão Linear Simples e Múltipla baseada em dados climáticos (INMET e ADEMA).

# Modelagem Preditiva da Balneabilidade das Praias de Aracaju 🏖️📊

Este repositório contém o código-fonte e a análise de dados desenvolvidos como Trabalho de Conclusão de Curso (TCC) em Análise e Desenvolvimento de Sistemas. O projeto aplica técnicas de Machine Learning para prever a qualidade da água (nível de coliformes) nas praias de Aracaju com base em variáveis climáticas.

## 🎯 Objetivo
Avaliar e modelar o relacionamento linear entre fatores meteorológicos (Precipitação, Velocidade do Vento e Umidade Relativa) e a balneabilidade das praias da orla de Aracaju, buscando responder à pergunta: *É possível prever a contaminação da água em função do clima?*

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** Python 3.12
* **Manipulação de Dados:** `pandas`, `numpy`
* **Machine Learning:** `scikit-learn` (Regressão Linear Simples e Múltipla)
* **Visualização de Dados:** `matplotlib`, `seaborn`
* **Ambiente:** Jupyter Notebook / Google Colab

## 📂 Estrutura dos Dados
O projeto cruza dados de duas fontes governamentais referentes ao ano de 2025:
1. **INMET (Instituto Nacional de Meteorologia):** Dados diários da estação A409 de Aracaju (Chuva, Vento, Umidade). Arquivo: `dados_inmet_aracaju_2025.csv`.
2. **ADEMA (Administração Estadual do Meio Ambiente):** Laudos semanais de coliformes termotolerantes em diversos pontos da orla (Ex: Atalaia Velha, Banho Doce, Robalo). Arquivo: `dados_adema_aracaju_2025.csv`.

## ⚙️ Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/AllanFabricio/linear_regression_water_quality_aracaju.git
