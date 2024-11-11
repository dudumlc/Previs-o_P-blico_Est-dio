# Projetos de Previsão de Público em Jogos do Campeonato Brasileiro

## 📊 Previsão de Público em Jogos do Cruzeiro
Este projeto utiliza dados históricos de público nos jogos do Cruzeiro Esporte Clube para criar um modelo preditivo que estima o número de torcedores em jogos futuros do clube no Campeonato Brasileiro. O projeto foi desenvolvido em Python, utilizando técnicas de web scraping e bibliotecas de ciência de dados para tratamento e modelagem.

## 📌 Descrição do Projeto
O projeto visa antecipar o número de torcedores que comparecerão aos jogos do Cruzeiro no Campeonato Brasileiro, com o objetivo de auxiliar no planejamento e logística dos eventos esportivos. Através da coleta de dados históricos de público, o projeto usa técnicas de aprendizado de máquina para construir um modelo de previsão robusto e ajustado a essa finalidade.

Os dados históricos foram coletados com web scraping e passaram por etapas rigorosas de tratamento e análise para que o modelo pudesse oferecer previsões precisas e confiáveis.

## 🛠 Tecnologias Utilizadas
### 📚 Principais Bibliotecas
Requests: Utilizada para realizar o web scraping dos dados de público em fontes confiáveis.
BeautifulSoup: Facilita a análise e extração de informações específicas do HTML das páginas.
Pandas: Empregada para manipulação e pré-processamento de dados, desde a organização até o tratamento de valores ausentes.
Scikit-Learn: Biblioteca de machine learning utilizada para construir e avaliar os modelos preditivos.
Matplotlib & Seaborn: Bibliotecas para visualização dos dados e análise exploratória.

## 📈 Metodologia
1. Coleta de Dados com Web Scraping
O projeto começa com a coleta de dados históricos do público nos jogos do Cruzeiro. Utilizando as bibliotecas Requests e BeautifulSoup, foi feito um web scraping em sites esportivos para extrair informações de público, data, local, adversário e outras variáveis relevantes.
Após o scraping, os dados foram organizados e salvos em um formato tabular para facilitar o processamento subsequente.
2. Tratamento e Análise dos Dados
Limpeza: Tratamento de valores ausentes e padronização dos dados coletados.
Transformação: As variáveis categóricas, como adversário e local do jogo, foram transformadas em variáveis numéricas para serem utilizadas pelos modelos de machine learning.
Engenharia de Atributos: Foram criadas novas variáveis a partir das informações de base para enriquecer o modelo. Isso incluiu variáveis de contexto, como a fase da competição e o desempenho recente do time.
3. Comparação e Seleção dos Modelos
Foram testados diferentes algoritmos de aprendizado de máquina, incluindo:
Regressão Linear
Árvore de Decisão
Random Forest
XGBoost
Cada modelo foi comparado usando métricas como RMSE (Root Mean Squared Error) e MAE (Mean Absolute Error) para determinar qual oferecia as previsões mais precisas.
4. Otimização dos Hiperparâmetros
Após a seleção do modelo com melhor desempenho, foi realizada uma otimização dos hiperparâmetros utilizando GridSearchCV e RandomizedSearchCV, melhorando ainda mais a precisão das previsões.

## 🔍 Exemplo de Previsão
Com base nos dados históricos e no modelo final ajustado, é possível prever, por exemplo, que um jogo do Cruzeiro contra um grande rival no Mineirão poderia ter uma presença estimada de até 40.000 torcedores, dependendo das condições.

Observação
As previsões são influenciadas por fatores externos como desempenho atual do time, clima e fase da competição, que podem impactar a precisão do modelo.

## 📊 Resultados e Conclusão
Ao final, o modelo otimizado mostrou-se eficaz para prever a presença do público nos jogos do Cruzeiro, com boa acurácia e uma margem de erro reduzida, ajudando a equipe de logística e planejamento do clube a se preparar de forma mais assertiva para os eventos.
