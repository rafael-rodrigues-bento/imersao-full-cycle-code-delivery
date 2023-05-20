# Code Delivery - Imersão Full cycle

A aplicação consiste em um website de entregas que exibe o rastreamento em tempo real.

Para evitar perda de informação caso o serviço de backend fique indisponível por alguns momentos, não trabalharemos com REST, trabalharemos com o Apache Kafka para o envio e recebimento de dados entre os sistemas.

Não é responsabilidade do serviço de backend persistir os dados no Elasticsearch, utilizaremos o Kafka Connect que também consumirá os dados do simulador e fará a inserção no Elasticsearch.

Trabalharemos com websockets (O backend receberá os dados do simulador, e enviará as posições para o frontend via websocket).

## Demo

![Gravação de tela de 18-05-2023 23_43_02](https://github.com/rafael-rodrigues-bento/imersao-full-cycle-code-delivery/assets/101301928/0a9128c4-deab-42f2-98a3-bd45a76bf5f4)

## Dinamica da aplicação

![Captura de tela de 2023-05-20 16-08-35](https://github.com/rafael-rodrigues-bento/imersao-full-cycle-code-delivery/assets/101301928/a34f58d4-a03b-422d-8692-5b511c0ad9a7)

## Tecnologias Utilizadas

- Golang
- JavaScript
- TypeScript
- NestJS
- ReactJS
- WebSocket
- Docker
- MongoDB
- Apache Kafka
- Kafka Connect
- Kubernetes
- ElasticSearch
- Kibana

## Instalação

A aplicação está dividida em quatro partes, primeiro faça o clone do repositório com o seguinte comando:

```
git clone git@github.com:rafael-rodrigues-bento/imersao-full-cycle-code-delivery.git
```

Após em cada pasta haverá um read.me com os passos seguintes.

