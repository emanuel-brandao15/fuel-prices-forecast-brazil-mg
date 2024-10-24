# Previsão de Preço de Combustíveis com Machine Learning

Este projeto tem como objetivo desenvolver um modelo de **Machine Learning** para prever os preços médios de combustíveis, com foco em **etanol** e **gasolina**, utilizando séries temporais. O projeto emprega uma combinação de técnicas de aprendizado supervisionado e modelos especializados em séries temporais, como **Random Forest**, **XGBoost** e **SARIMAX**, para capturar padrões de preço ao longo do tempo e fornecer previsões precisas.

## Índice

- [Contexto](#contexto)
- [Modelos Utilizados](#modelos-utilizados)
- [Pré-processamento e Feature Engineering](#pré-processamento-e-feature-engineering)
- [Otimização de Hiperparâmetros](#otimização-de-hiperparâmetros)
- [Resultados](#resultados)
- [Como Executar](#como-executar)
- [Contribuições](#contribuições)

## Contexto

Com o aumento da complexidade do mercado de combustíveis e os impactos causados por eventos externos, como a pandemia de COVID-19, a capacidade de prever os preços futuros de combustíveis tornou-se crucial. Este projeto visa fornecer um modelo preditivo que pode ajudar a tomar decisões estratégicas com base nas variações de preços de combustíveis no mercado brasileiro.

## Modelos Utilizados

Os principais modelos de Machine Learning usados no projeto são:

- **Random Forest**: Utilizado para capturar padrões complexos nos dados de séries temporais.
- **XGBoost**: Modelo de gradient boosting altamente eficiente, com otimização de hiperparâmetros automatizada.
- **SARIMAX**: Modelo autoregressivo integrado com média móvel, utilizado para capturar sazonalidade e dependências temporais nos dados.

## Pré-processamento e Feature Engineering

O pré-processamento dos dados incluiu:
- **Tratamento de dados faltantes**: Remoção ou interpolação de valores ausentes.
- **Criação de variáveis de defasagem (lags)**: Incluídas para capturar a relação temporal entre observações anteriores e futuras.
- **Médias móveis**: Utilizadas para suavizar flutuações e capturar tendências de curto prazo.

## Otimização de Hiperparâmetros

Foi utilizada a biblioteca **Optuna** para realizar a otimização de hiperparâmetros dos modelos. A técnica de validação cruzada temporal foi aplicada para garantir que os dados fossem respeitados na ordem cronológica, evitando vazamento de informações futuras para o treinamento do modelo.

## Resultados

Os resultados mostram que os modelos foram capazes de prever os preços de combustíveis com boa precisão, especialmente ao usar médias móveis e variáveis defasadas como features principais. O modelo **SARIMAX** demonstrou boa performance ao capturar padrões sazonais e de tendência.

## Como Executar

Para executar este projeto localmente, siga os passos abaixo:

1. Clone este repositório:
   ```bash
   git clone https://github.com/seuusuario/repositorio-combustivel.git
