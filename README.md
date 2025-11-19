# Project-IAC

Este projeto é um ambiente de estudo e experimentação de conceitos de DevOps e Infrastructure as Code (IaC). A aplicação base é construída com Node.js e TypeScript, fornecendo um ponto de partida para a implementação de pipelines de CI/CD, automação de infraestrutura e outras práticas de DevOps.

## Objetivo

O objetivo principal deste projeto é servir como um playground para aprender e aplicar práticas de DevOps em um ambiente controlado. Ele inclui uma aplicação web simples, mas funcional, que pode ser usada para demonstrar e testar:

*   **Integração Contínua (CI):** Compilação, testes e validação automatizados a cada alteração de código.
*   **Entrega Contínua (CD):** Automação do processo de implantação da aplicação em diferentes ambientes.
*   **Infraestrutura como Código (IaC):** Gerenciamento e provisionamento da infraestrutura da aplicação de forma declarativa.
*   **Monitoramento e Observabilidade:** Coleta de métricas, logs e traces para garantir a saúde da aplicação.

## Tecnologias

*   **Aplicação:** Node.js, TypeScript
*   **CI/CD:** GitHub Actions
*   **Gerenciador de Pacotes:** pnpm

## Instalação

```bash
$ npm install
```

## Executando a aplicação

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Testes

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```
