# TDD - Event City

Este projeto foi desenvolvido como parte do **Desafio TDD Event City** da [DevSuperior](https://devsuperior.com.br).  
O objetivo é implementar as funcionalidades necessárias para que **todos os testes automatizados do projeto passem com sucesso**.

---

## 📋 Descrição

O sistema simula uma aplicação de **eventos e cidades**, com uma relação **N-1** entre eles:

- Cada **evento** está associado a uma **cidade**.
- Uma **cidade** pode ter vários **eventos**.

A especificação completa do que deve ser implementado está descrita **nos próprios testes automatizados do projeto** (TDD — Test Driven Development).  
O foco do desafio é garantir que a aplicação atenda aos requisitos de forma **guiada pelos testes**.

---

## 🧱 Estrutura do projeto

```bash
src/
 ├── main/
 │   ├── java/com/devsuperior/bds02/
 │   │    ├── controllers/
 │   │    ├── dto/
 │   │    ├── entities/
 │   │    ├── repositories/
 │   │    └── services/
 │   └── resources/
 └── test/
      └── java/com/devsuperior/bds02/
           ├── controllers/
           ├── services/
           └── repositories/

```

## ⚙️ Tecnologias utilizadas

- Java 17+

- Spring Boot

- Spring Data JPA

- H2 Database

- JUnit 5

- Maven

## ✅ Critérios de avaliação

- Todos os testes devem passar com sucesso.

- Código limpo, organizado e seguindo boas práticas de programação.

## 🚀 Como clonar e executar o projeto

Siga os passos abaixo para clonar o repositório e rodar o projeto localmente:

### 🔹 1. Clonar o repositório
Abra o terminal e execute o comando abaixo:
```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git

```

## 🧠 Conceitos aplicados

- TDD (Test Driven Development)

- Injeção de dependências

- Boas práticas com camadas Controller, Service e Repository

- Tratamento de exceções no Spring

- Validação de dados com Bean Validation

- Mapeamento JPA (relação N-1 entre entidades)

## 📈 O que aprendi com o desafio

- Durante o desenvolvimento deste desafio, foi possível reforçar diversos conceitos importantes do ecossistema Spring:

- Aplicar o TDD como metodologia de desenvolvimento, garantindo qualidade e segurança no código.

- Entender melhor a estrutura de camadas Controller, Service e Repository.

- Praticar o uso do Spring Data JPA e o mapeamento entre entidades com relacionamentos.

- Implementar tratamento de exceções personalizado e respostas HTTP adequadas.

- Trabalhar com testes automatizados de integração e unidade usando JUnit e Mockito.
