# Twitter Sentiment Analysis

Este projeto realiza a análise de sentimentos em tweets utilizando o dataset [Twitter Sentiment Analysis](https://www.kaggle.com/), disponível no Kaggle. A análise busca classificar tweets em categorias de sentimentos, como positivo, negativo, neutro e irrelevante.

## Descrição do Projeto

Neste projeto, foram utilizados vários modelos de aprendizado profundo para realizar a classificação dos tweets. Os modelos testados incluem LSTM, GRU, Bi-LSTM, Text-CNN e BERT. O objetivo foi comparar o desempenho de diferentes arquiteturas e encontrar a que melhor se adequa a esse problema de classificação de sentimentos.

### Principais Tarefas Realizadas:
- **Pré-processamento dos tweets**: Limpeza de dados, tokenização e vetorização.
- **Treinamento de modelos**: Comparação de diferentes arquiteturas para identificar a melhor solução.
- **Visualizações**: Geração de gráficos e matrizes de confusão para análise de desempenho.

## Dataset

O dataset contém mais de 69 mil tweets, rotulados em categorias de sentimentos. Ele pode ser acessado através do Kaggle no link acima.

### Exemplo de Classes:

- **Positivo**: Tweets com uma conotação positiva.
- **Negativo**: Tweets com uma conotação negativa.
- **Neutro**: Tweets com sentimento neutro.
- **Irrelevante**: Tweets sem relevância emocional.

## Modelos Utilizados

- **LSTM** (Long Short-Term Memory)
- **GRU** (Gated Recurrent Units)
- **Bi-LSTM** (Bidirectional LSTM)
- **Text-CNN** (Convolutional Neural Network para texto)
- **BERT** (Bidirectional Encoder Representations from Transformers)

## Metodologia

O projeto foi dividido em três fases principais:

1. **Pré-processamento dos dados**: Remoção de ruído dos textos, tokenização e vetorização.
2. **Treinamento de modelos**: Cada modelo foi treinado utilizando técnicas de otimização para garantir melhores resultados.
3. **Avaliação de desempenho**: Métricas como acurácia, precisão, recall e F1-score foram utilizadas para medir o desempenho de cada modelo.

## Como Executar

Para reproduzir este projeto, é necessário utilizar Python e as bibliotecas adequadas. As dependências podem ser instaladas manualmente, conforme necessário, com base nos pacotes usados nos notebooks.

## Resultados

Os notebooks apresentam os resultados detalhados das execuções de cada modelo, incluindo métricas de desempenho e gráficos que demonstram a evolução dos treinamentos.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
