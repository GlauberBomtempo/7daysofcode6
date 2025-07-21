# Análise de Machine Learning - Balanceamento e Ajuste de Hiperparâmetros 🎶

Este repositório contém a resolução do 6º Desafio do projeto #7DaysOfCode - Machine Learning. O foco principal é testar diferentes técnicas de balanceamento de classes e realizar ajuste de hiperparâmetros para modelos de classificação, com o objetivo de prever a popularidade de músicas no Spotify.

## 📌 Sobre o Projeto

O projeto contempla as seguintes etapas:

- Análise exploratória realizada no primeiro desafio, incluindo gráficos e investigações sobre distribuição e correlações;
- Criação da variável binária `pop_classe` com critério **próprio e personalizado** baseado na popularidade;
- Criação da variável `artistas_relevantes` considerando os artistas mais populares;
- Aplicação de OneHotEncoding nas variáveis categóricas;
- Divisão dos dados em treino, validação e teste;
- Aplicação de técnicas de reamostragem para balanceamento das classes (RandomOverSampler, RandomUnderSampler, SMOTE);
- Implementação de validação cruzada estratificada (StratifiedKFold);
- Treinamento e avaliação de modelos de classificação:
    - Random Forest (incluindo ajuste de hiperparâmetros com RandomizedSearchCV);
    - XGBoost (incluindo ajuste de hiperparâmetros);
- Comparação de performance entre modelos e técnicas de balanceamento com análise de métricas: Acurácia, Precisão, Recall e F1-Score;

## 📊 Principais Etapas

- 🔎 **Análise Exploratória**: realizada no desafio 1, com foco nos principais atributos musicais e distribuição de popularidade;
- 🛠️ **Pré-processamento Avançado**: eliminação de colunas irrelevantes, criação de features adicionais (ex: artistas populares), tratamento de variáveis categóricas com OneHotEncoding;
- 🎯 **Balanceamento de Classes**:
    - Comparação de RandomUnderSampler, RandomOverSampler e SMOTE;
- 🚀 **Validação de Modelos**:
    - Modelos comparados: Random Forest, XGBoost;
    - Ajuste de hiperparâmetros via RandomizedSearchCV;
- 📈 **Validação Cruzada (StratifiedKFold)** com cálculo das métricas em cada fold;
- ✅ **Comparação Final** das principais métricas para definição do melhor modelo.

## 📝 Como Executar

Clone o repositório:

```bash
git clone [https://github.com/GlauberBomtempo/7daysofcode6/blob/main/7daysofcode6.ipynb]
```
Instale as bibliotecas necessárias:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost imbalanced-learn
```
Execute o notebook 7daysofcode6.ipynb no ambiente de sua preferência.

📂 Estrutura do Repositório
7daysofcode6.ipynb → Notebook completo da análise do desafio 6;

README.md → Este arquivo de descrição do projeto.

🚩 Conclusão
Este projeto avançou significativamente em relação à proposta base da Alura, com a adoção de práticas robustas de feature engineering, técnicas de balanceamento e ajustes de hiperparâmetros, resultando em um modelo final mais eficaz e adequado para o desafio proposto.

📢 Observação Importante
Este projeto tem finalidade educacional, utilizando dataset público do Spotify via Alura.

👨‍💻 Desenvolvido por Gláuber Lopes Bomtempo
