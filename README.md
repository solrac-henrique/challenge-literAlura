# 📚 LiterAlura - Projeto Java

## Visão geral

O LiterAlura é uma aplicação de console desenvolvida em Java com Spring Boot, criada como desafio do Programa Oracle One (Alura + Oracle). A aplicação consome a API pública Gutendex para buscar informações de livros e os armazena em um banco de dados PostgreSQL para consultas posteriores.

Agradecimentos ao Gutendex.com por disponibilizar os dados de livros utilizados neste projeto.

## ⚙️ Funcionalidades

- [x] Busca de livros na API Gutendex por título
- [x] Armazenamento dos livros e autores em banco de dados (PostgreSQL + JPA/Hibernate)
- [x] Listagem de livros já registrados no banco
- [x] Listagem de autores registrados
- [x] Busca de autores vivos em um determinado ano
- [x] Listagem de livros por idioma

## 🛠 Tecnologias

- **Java 17**
- **Spring Boot 3.2**
- **API Gutendex** — consumo de dados de livros
- **PostgreSQL**
- **JPA / Hibernate**
- **Maven**

## ▶️ Como executar

1. Clone este repositório:
   git clone https://github.com/solrac-henrique/challenge-literAlura.git

2. Configure as credenciais do banco de dados PostgreSQL no arquivo `application.properties`.
3. Execute o projeto com Maven:
   ./mvnw spring-boot:run

4. Utilize o menu interativo exibido no console para buscar livros, autores e aplicar os filtros disponíveis.

### Autor: Carlos Henrique Martins
