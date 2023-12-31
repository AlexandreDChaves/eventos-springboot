<img src="https://img.shields.io/badge/STATUS-CONCLUÍDO-green"/>

# Projeto CRUD Spring Boot

## Sobre o Projeto:

Uma aplicação web modelada no padrão MVC em Java e construída com o Spring Boot, o projeto conta com uma estrutura de CRUD, no qual os dados estão sendo persistidos em um banco de dados 
(MySQL). Na camada de visualização foi utilizado HTML, CSS, o framework Materialize e o template Thymeleaf.
 O sistema possui outras funcionalidades como, cadastro de eventos, listar e deletar.

 ## Tecnologias Utilizadas

- Java
- Spring Boot
- JPA / Hibernate
- Maven
- HTML/CSS/JS
- Materialize
- MySQL

- ## Instalação

  O projeto é gerenciado pelo Maven, então para usa-lo basta importa-lo para uma IDE.

## Configurações do banco de dados
Você pode criar um banco de dados MySQL com o nome o nome de sua preferência, porém é necessario adequar o projeto de acordo com as suas configurações.
Para isso abra o arquivo application.properties, localizado em src/main/resources/application.properties e altere os seguintes comandos ao arquivo:

```
- spring.datasource.url = jdbc:mysql://localhost:3306/nome-do-seu-banco-de-dados?useTimezone=true&serverTimezone=UTC
- spring.datasource.username = root
- spring.datasource.password = root
```

## Execução
Execute o projeto através do IDE, abra um navegador de sua preferência e digite: http://localhost:8080/cadastrarEvento
