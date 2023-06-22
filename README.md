# Scripts ShopZilla

Scripts Docker relacionados ao projeto ShopZilla

## Geral

Este projeto faz parte de um conjunto de outros projetos ShopZilla, destinados aos estudos da arquitetura orientada a eventos, Kafka, Entity Framework e execução de processos em segundo plano via BackgroundServices.

O ShopZilla é um projeto que busca simular a efetivação de compras, atualização de estoque e envio de notificações para os clientes através de aplicações independentes, onde aproveitando da arquitetura orientada a eventos, caso algum sistema esteja completamente fora, não vai afetar o conjunto como um todo.

![alt text](https://github.com/felipetoscano/shopzilla-scripts-docker/blob/main/resources/shopzilla-geral.jpg)

## Execução

Executar o arquivo docker-compose.yml presente na raiz do projeto com o comando abaixo:

`
docker-compose up -d
`

Além disso, garanta que as imagens de todos as aplicações .NET foram geradas.
