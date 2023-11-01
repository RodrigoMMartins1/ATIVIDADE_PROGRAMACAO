# ATIVIDADE_PROGRAMACAO

# Kafka Docker Compose Producer e Consumer Exemplo:

Este é um exemplo de como configurar um ambiente Kafka local usando Docker Compose e demonstrar a produção e consumo de mensagens.

## Pré-requisitos:

- Docker: Certifique-se de que o Docker esteja instalado.
- Docker Compose: Verifique se o Docker Compose está instalado.

## Passo a Passo

1. Clone este repositório

2. Inicie o ambiente Kafka com docker-compose up -d

3. Verifique se os containers kafka e zookeeper estão em execução com docker ps

4. Produza mensagens em um tópico Kafka usando o Kafka Console Producer com docker exec -it <nome_do_seu_container_kafka> kafka-console-producer --broker-list kafka:9092 --topic meu-topico

5. Abra um novo terminal e consuma o Kafka usando oKafka Console Consumer com docker exec -it <nome_do_seu_container_kafka> kafka-console-consumer --bootstrap-server kafka:9092 --topic meu-topico --from-beginning

## Exemplo
- Producer:
<img width="616" alt="image" src="https://github.com/RodrigoMMartins1/ATIVIDADE_PROGRAMACAO/assets/99209230/e969b7fb-4c53-473f-83ab-1fc04e67ffc1">

- Consumer:
<img width="611" alt="image" src="https://github.com/RodrigoMMartins1/ATIVIDADE_PROGRAMACAO/assets/99209230/e5ae0409-97de-4826-bfb4-d2a0b0ef52d4">





