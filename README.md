 <h1>API de Transações – Spring Boot</h1>

Este projeto é uma API REST que recebe transações e calcula estatísticas em tempo real (últimos 60 segundos), tudo em memória – sem banco de dados.

🚀 Funcionalidades

POST /transacao → Recebe novas transações

DELETE /transacao → Apaga todas as transações

GET /estatistica → Retorna estatísticas (count, sum, avg, min, max) das transações dos últimos 60 segundos

🛠️ Tecnologias Utilizadas

<p align="center">
  <img alt="Spring Boot" src="https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
  <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img alt="GitHub" src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/>
</p>

Postman (para testes de API)

▶️ Como Executar

Clone o repositório:

git clone https://github.com/RenatoDev23/Desafio-Itau
cd projeto-transacoes


Rode a aplicação:

./mvnw spring-boot:run


Teste os endpoints no Postman ou Insomnia.

📷 Exemplo de Requisição
POST /transacao
{
  "valor": 123.45,
  "dataHora": "2025-09-17T12:34:56.789-03:00"
}

📌 Objetivo

Projeto desenvolvido para praticar:

Criação de APIs RESTful com Spring Boot

Validação de dados de entrada

Cálculo de estatísticas em tempo real

Organização de código e versionamento no GitHub
