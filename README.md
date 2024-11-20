# Projetos de Previsão de Público em Jogos do Campeonato Brasileiro

## 📊 Previsão de Público em Jogos do Cruzeiro
Este projeto utiliza dados históricos de público nos jogos do Cruzeiro Esporte Clube para criar um modelo preditivo que estima o número de torcedores em jogos futuros do clube no Campeonato Brasileiro. O projeto foi desenvolvido em Python, utilizando técnicas de web scraping e ciência de dados para extração, tratamento e modelagem dos dados.

## 📌 Descrição do Projeto
O projeto visa antecipar o número de torcedores que comparecerão aos jogos do Cruzeiro no Campeonato Brasileiro, com o objetivo de auxiliar no planejamento e logística dos eventos esportivos. Com uma estimativa acurada do público do jogo, os clubes de futebol conseguem tomar melhores decisões para maximizar seus resultados, como campanhas de marketing para aumento da demanda e promoções no preço de venda, ou, em últimos casos, mudança de estádio e abertura de apenas alguns portões. 

## 🛠 Tecnologias Utilizadas
### 📚 Principais Bibliotecas
- Requests: Utilizada para realizar o web scraping dos dados de público presentes em sites da internet.
- BeautifulSoup: Facilita a análise e extração de informações específicas do HTML das páginas.
- Pandas: Empregada para manipulação e pré-processamento de dados.
- Scikit-Learn: Biblioteca de machine learning utilizada para construir e avaliar os modelos preditivos.
- Matplotlib & Seaborn: Bibliotecas para visualização dos dados e análise exploratória.

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

## 📊 Resultados e Conclusão
Ao final, o modelo otimizado mostrou-se eficaz para prever a presença do público nos jogos do Cruzeiro, com boa acurácia e uma margem de erro reduzida, ajudando a equipe de logística e planejamento do clube a se preparar de forma mais assertiva para os eventos.
