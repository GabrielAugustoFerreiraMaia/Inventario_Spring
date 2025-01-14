# Gerenciamento de Inventário

Este é um projeto de gerenciamento de inventário desenvolvido com Spring Boot. O objetivo do projeto é fornecer uma API RESTful para gerenciar produtos, permitindo operações como criação, leitura, atualização e exclusão (CRUD).

## Tecnologias Utilizadas

- **Java 17**
- **Spring Boot 3.x**
- **Spring Data JPA**
- **H2 Database** (para desenvolvimento e testes)
- **Spring Security** (opcional)
- **Thymeleaf** (opcional para interface web)
- **Maven** (gerenciamento de dependências)

## Funcionalidades

- **Gerenciamento de Produtos**: Adicionar, listar, atualizar e remover produtos.
- **Validação de Dados**: Validação de entrada para garantir a integridade dos dados.
- **Segurança**: Autenticação básica (opcional) para proteger rotas sensíveis.
- **Documentação da API**: Documentação automática da API usando Springdoc OpenAPI.

## Configuração do Ambiente

Para executar o projeto, siga os passos abaixo:

### Pré-requisitos

- JDK 17 ou superior
- Maven 3.6 ou superior

### Clonando o Repositório

```bash
git clone https://github.com/seu_usuario/seu_repositorio.git
cd seu_repositorio
````
### Construindo o Projeto

```bash
mvn clean install
```
### Executando a Aplicação

```bash
mvn spring-boot:run
```

A aplicação estará disponível em `http://localhost:8080`.

## Endpoints da API

### Produtos

- **GET /products**: Lista todos os produtos.
- **GET /products/{id}**: Obtém um produto pelo ID.
- **POST /products**: Adiciona um novo produto.
- **PUT /products/{id}**: Atualiza um produto existente.
- **DELETE /products/{id}**: Remove um produto pelo ID.

### Segurança

Se a segurança estiver habilitada, você precisará acessar as rotas de autenticação. A configuração padrão pode ser alterada conforme necessário.

## Documentação da API

A documentação da API pode ser acessada em `http://localhost:8080/v3/api-docs` e a interface Swagger UI em `http://localhost:8080/swagger-ui.html`.

## Contribuição

Se você deseja contribuir para este projeto, fique à vontade para abrir um *pull request* ou relatar problemas.

## Licença

Este projeto está licenciado sob a MIT License. Veja o arquivo LICENSE para mais detalhes.