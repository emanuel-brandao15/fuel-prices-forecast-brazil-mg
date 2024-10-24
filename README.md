# ⛽ *Forecasting* do preço médio de combustíveis em postos do estado de Minas Gerais em período pós-pandemia da COVID19
---

Projeto realizado como trabalho de conclusão de curso da pós-graduação em Ciência de Dados e Big Data da instituição Pontifícia Universidade Católica de Minas Gerais - PUCMG. Este trabalho objetiva desenvolver um estudo com criação de modelos **Machine Learning** para previsão de preços médios dos combustíveis **Etanol** e **Gasolina**, por meio de séries temporais. O projeto utilizou como base de dados a pesquisa de preços em postos de todo o Brasil realizada semanalmente pela Agência Nacional do Petróleo, Gás Natural e Biocombustíveis (ANP) e disponibilizada no portal de dados abertos do Governo Federal. Os modelos de Machine Learning empregados consistiram de uma combinação de técnicas de aprendizado supervisionado e modelos especializados em séries temporais, mais especificamente **Random Forest**, **XGBoost** e **SARIMAX**, afim de capturar padrões nos preços considerando principalmente períodos de curto prazo e fornecer previsões precisas.


## Como Executar este projeto localmente

Para execução dos algoritmos de preparação e análise dos dados, e também o *script* de criação de modelos e escoragem, siga os passos abaixo:

1. Clone este repositório:
   ```bash
   git clone https://github.com/seuusuario/repositorio-combustivel.git
2. Instalação das dependências:
   ```bash
   pip install -r requirements.txt
3. Execute os notebooks na sua IDE de preferência (Jupyter Notebook, VSCode etc)
   ```bash
   jupyter notebook modelo_treinamento.ipynb

---
## :us: - English ver.

# ⛽ Forecasting the Average Price of Fuels in Gas Stations in the State of Minas Gerais in the Post-Pandemic Period of COVID-19
---
This project was conducted as the final thesis for the postgraduate course in Data Science and Big Data at the Pontifical Catholic University of Minas Gerais - PUCMG. The objective of this work is to develop a study with the creation of Machine Learning models to forecast the average prices of Ethanol and Gasoline fuels using time series data. The project is based on the weekly fuel price surveys conducted at gas stations across Brazil by the National Agency of Petroleum, Natural Gas and Biofuels (ANP), made available on the Brazil Government's open data portal. The Machine Learning models employed consisted of a combination of supervised learning techniques and specialized time series models, specifically Random Forest, XGBoost, and SARIMAX, in order to capture price patterns, particularly in the short term, and provide accurate predictions.


## How to run this project locally

To execute the data preparation and analysis algorithms, as well as the model creation and scoring scripts, follow the steps below:

1. Clone this repo:
   ```bash
   git clone https://github.com/seuusuario/repositorio-combustivel.git
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the notebooks in your preferred IDE (Jupyter Notebook, VSCode etc)
   ```bash
   jupyter notebook modelo_treinamento.ipynb
---
**Autor:** Emanuel Brandão de Galvão Correia
