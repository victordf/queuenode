[![github](https://img.shields.io/github/package-json/dependency-version/victordf/queuenode/bull)](https://github.com/OptimalBits/bull)
[![github](https://img.shields.io/github/package-json/dependency-version/victordf/queuenode/bull-board?color=orange)](https://github.com/vcapretz/bull-board)
[![github](https://img.shields.io/github/package-json/dependency-version/victordf/queuenode/express?color=red)](https://expressjs.com/)
[![github](https://img.shields.io/github/package-json/dependency-version/victordf/queuenode/nodemailer?color=green)](https://nodemailer.com/about/)

# Queue Node

## Sobre o Projeto

Este projeto é um estudo de processos executados em background controlados pelo Bull, que gerencia e executa as queues. O objetivo deste projeto é o aprofundamento no assunto e construção de Know How.

## Feito com

 - [Express](https://expressjs.com/) - Utilizado para controlar as rotas da aplicação
 - [Bull](https://github.com/OptimalBits/bull) - Utilizado para criar e executar as queues
 - [Bull-Board](https://github.com/vcapretz/bull-board) - Utilizado para facilitar a visualização das queues executados em desenvolvimento
 - [NodeMailer](https://nodemailer.com/about/) - Utilizado para enviar os emails
 - [Redis](https://hub.docker.com/_/redis) - Utilizado de maneira local com o [Docker](https://www.docker.com/) serve para armazenar as queues

### Redis

Para utiliar o Redis eu subi um container no [Docker](https://www.docker.com/) com a versão alpine do Redis. Utilizei o seguinte comando:
```
docker run --name redis -p 6379:6379 -d -t redis:alpine
```

## Considerações

Esta aplicação foi criada seguindo a Masterclass de número 2 da [Rocketseat](https://www.youtube.com/watch?v=uonKHztGhko&list=PL85ITvJ7FLoiNndfuEs2So-MFLSMvBmmD&index=1)
