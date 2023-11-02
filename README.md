# Guia de Configuração do Ambiente Kafka com Docker Compose

Este guia fornece instruções detalhadas para configurar um ambiente local do Apache Kafka usando Docker Compose e demonstrar a produção e consumo de mensagens. Você pode optar por dois modos diferentes para configurar o ambiente Kafka. Siga as etapas de acordo com o modo de sua escolha.

## Modo 1

### Pré-requisitos

- Docker: Certifique-se de que o Docker esteja instalado.
- Docker Compose: Verifique se o Docker Compose está instalado.

### Passo a Passo

1. Clone este repositório para o seu sistema.

2. Inicie o ambiente Kafka com o seguinte comando:
   ```shell
   docker-compose up -d


## Verificando o Status dos Containers

Certifique-se de que os containers Kafka e Zookeeper estão em execução com o comando:

```shell
docker ps

