# Microservices with Spring Boot Learning Project

Este projeto tem como objetivo fornecer um exemplo prático e simples para aprender a utilizar microservices com Spring Boot. O cenário simulado envolve a criação de dois microservices: um para receber informações de usuários e persisti-las no banco de dados, e outro para processar essas informações e enviar e-mails utilizando o RabbitMQ e SMTP.

## Requisitos

Certifique-se de ter as seguintes ferramentas instaladas em seu ambiente de desenvolvimento:

- Java JDK 8 ou superior
- Maven
- RabbitMQ
- PostgreSQL

## Configuração do Projeto

1. Clone o repositório para o seu ambiente local:

   ```bash
   git clone https://github.com/PedroCatelann/ms-email.git

2. Navegue até o diretório do projeto
3. Personalize as configurações de banco de dados, RabbitMQ e SMTP no arquivo application.properties de cada microservice (ms-user e ms-email).
