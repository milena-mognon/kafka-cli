# Comandos Kafka - CLI


## todas as opções de comandos de tópicos
`kafka-topics `

## Cria um tópico
`kafka-topics --create --topic=teste --bootstrap-server=localhost:9092 --partitions=3 `

## Lista os tópicos
`kafka-topics --list --bootstrap-server=localhost:9092
`

## Configurações do tópico
`kafka-topics --bootstrap-server=localhost:9092 --topic=teste --describe`

## Produzindo e consumindo mensagens

### Responsável por consumir um tópico

`kafka-console-consumer`

## Criando um consumidor

`kafka-console-consumer --bootstrap-server=localhost:9092 --topic=teste --from-beginning`

### Criando um grupo de consumidor

`kafka-console-consumer --bootstrap-server=localhost:9092 --topic=teste --group=x`

`kafka-consumer-groups`

`kafka-consumer-groups --bootstrap-server=localhost:9092 --group=x --describe`

## Criar um producer

`kafka-console-producer --bootstrap-server=localhost:9092 --topic=teste`


