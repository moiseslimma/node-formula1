# Formula 1 Teams and Drivers API

Este projeto é uma API simples construída com [Fastify](https://www.fastify.io/) que fornece informações sobre as equipes e pilotos da Fórmula 1.

## Funcionalidades

A API possui os seguintes endpoints:

### **Equipes**
- `GET /teams`: Retorna a lista de todas as equipes de Fórmula 1.
- `GET /teams/:id`: Retorna os detalhes de uma equipe específica com base no ID fornecido.

### **Pilotos**
- `GET /drivers`: Retorna a lista de todos os pilotos de Fórmula 1.
- `GET /drivers/:id`: Retorna os detalhes de um piloto específico com base no ID fornecido.

## **Tecnologias Utilizadas**
- NodeJS
- Fastify
- @fastify/cors
