# Análise de Sentimentos - Twitter
Aplicação de Machine Learning para análise de sentimentos, utilizando dados do Twitter, a fim de validar a concepção de um novo negócio.

## 1) Obtendo as credenciais para acessar a API do Twitter
Para a realização deste projeto, foi necessário fazer um upgrade na minha conta do Twitter para uma conta de desenvolvedor.

Para fazer isso, eu segui os passos deste vídeo do Programação Dinâmica:
https://www.youtube.com/watch?v=RssGfmtyn4A&t=920s (está um pouco antigo, mas acredito que não terá grandes diferenças)

Link para fazer o upgrade na sua conta:
https://developer.twitter.com/en

## 2) Coleta de dados
Após ter as credenciais para acessar a API do Twitter, deixei elas salvas em um arquivo txt.
O notebook coleta_twitter.ipynb tem os scripts em Python que fazem a conexão com a API do Twitter e coleta os dados desejados.

## 3) Dados de treino
Esta etapa foi crucial para o projeto. Para treinar meu modelo, eu utilizei uma base de dados de tweets em pt-br, já classificados como Positivos, Neutros ou Negativos.

Esta base é o arquivo csv tweets_treino.csv

Encontrei essa base de dados no Kaggle: https://www.kaggle.com/datasets/debkings/tweetpt

