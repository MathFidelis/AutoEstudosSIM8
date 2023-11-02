# Kafka Docker Compose

Este repositório oferece um ambiente local do Apache Kafka configurado por meio de um Docker Compose. Ele inclui um produtor e um consumidor de exemplo para demonstrar a funcionalidade do Kafka em um ambiente de desenvolvimento.

## Pré-requisitos

Antes de começar, certifique-se de que seu sistema atenda aos seguintes pré-requisitos:

- Docker deve estar instalado no seu sistema. Você pode baixá-lo em [Docker's Official Website](https://www.docker.com/get-started).
- Python precisa estar instalado no seu sistema.
- Utilize o seguinte comando para instalar a biblioteca Kafka-Python:

```
pip install kafka-python
```

## Como Utilizar

Siga estas etapas para configurar e executar o ambiente Kafka local:

### Clone este repositório:

```bash
git clone https://github.com/MathFidelis/AutoEstudosSIM8
```


## Como Utilizar

Para configurar e executar o ambiente Kafka local, siga estas etapas:

### Passo 1: Execute o Docker Compose

```bash
docker-compose up
```

## Passo 2: Execute o Produtor de Exemplo

Para enviar mensagens ao tópico especificado (neste exemplo, o tópico é denominado "sample-topic"), execute o seguinte comando:

```bash
python producer.py
```
O código do produtor enviará 100 mensagens, numeradas de 1 a 100.

## Passo 3: Execute o Consumidor de Exemplo

Para receber e exibir as mensagens do tópico especificado, execute o seguinte comando:

```bash
python consumer.py
```
O consumidor exibirá as mensagens recebidas do tópico.

## Resultado Esperado

Ao seguir as etapas acima, você deverá ver um ambiente Kafka local configurado com sucesso. O produtor enviará mensagens ao tópico, e o consumidor as receberá e exibirá no terminal.

## Exemplo de Resultado

## Fonte de Inspiração

Este projeto foi inspirado pelo seguinte artigo: [Link para o artigo no Medium](https://towardsdatascience.com/kafka-docker-python-408baf0e1088)


