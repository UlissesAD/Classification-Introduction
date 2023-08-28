# **Introduction to Classification**

This is an introductory notebook on classification in machine learning, addressing some of the essential steps in data mining. It involves data preprocessing (data cleaning), model training, testing, and the selection of an appropriate model for solving the problem, along with choosing the optimal metric for model validation.

Note: This notebook was predominantly authored in Portuguese (pt-br).

# **Introdução à Classificação**
Este é um notebook introdutório sobre classificação em aprendizado de máquina, abordando alguns dos passos essenciais na mineração de dados. Ele engloba o pré-processamento dos dados (limpeza dos dados), treinamento e teste de um modelo apropriado para o problema, juntamente com a seleção da métrica ideal para a validação do modelo.

Observação: Este caderno foi primariamente escrito em português (pt-br).

## Classificação: Uma Visão Geral

A classificação é um conceito fundamental em aprendizado de máquina, com o objetivo de categorizar pontos de dados em classes distintas com base em suas características. Isso envolve treinar um modelo com um conjunto de dados rotulados, em que cada ponto de dados está associado a uma classe conhecida. O modelo treinado é capaz de prever a classe de novos pontos de dados não vistos anteriormente.

## Como a Classificação Funciona

Algoritmos de classificação analisam as relações entre as características de entrada e os rótulos de classe correspondentes nos dados de treinamento. O algoritmo aprende padrões dos dados, que o ajudam a distinguir e generalizar as fronteiras entre diferentes classes. Esses padrões aprendidos são usados para fazer previsões em novos dados.

### Processo de Classificação:

1. **Coleta de Dados:** Reúna um conjunto de dados com exemplos rotulados de diferentes classes.

2. **Pré-processamento dos Dados:** Limpe e prepare os dados, incluindo o tratamento de valores ausentes e a transformação de características, se necessário.

3. **Extração/Seleção de Características:** Escolha características relevantes que contribuam para a separação das classes.

4. **Treinamento do Modelo:** Aplique um algoritmo de classificação aos dados rotulados para criar um modelo preditivo.

5. **Avaliação do Modelo:** Avalie o desempenho do modelo usando métricas como acurácia, precisão, recall e F1-Score.

6. **Predição:** Use o modelo treinado para classificar novos pontos de dados não vistos em classes apropriadas.

## Algoritmos Comuns de Classificação

| Algoritmo          | Descrição                                       |
|--------------------|-------------------------------------------------|
| Árvores de Decisão | Estruturas em formato de árvore para decisões sequenciais|
| Florestas Aleatórias | Conjuntos de árvores de decisão para maior acurácia|
| Máquinas de Vetores de Suporte | Encontram hiperplanos que melhor separam classes |
| Regressão Logística | Modela a probabilidade de pertencer a uma classe |
| k-Vizinhos Mais Próximos| Atribui classe com base nos vizinhos mais próximos |

## Métricas de Classificação

Algumas métricas de avaliação importantes incluem:

- **Acurácia:** Porcentagem de instâncias classificadas corretamente.
- **Precisão:** Proporção de previsões verdadeiras positivas entre todas as previsões positivas.
- **Recall (Sensibilidade):** Proporção de previsões verdadeiras positivas entre os positivos reais.
- **F1-Score:** Média harmônica de precisão e recall, equilibrando precisão e sensibilidade.



