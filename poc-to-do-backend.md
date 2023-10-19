# Prova de Conceito: To-Do App Backend

## Descrição

Desenvolva um simples back-end para um aplicativo de gerenciamento de tarefas (To-Do List) utilizando Java, Spring Boot, Spring Data JPA, e o banco de dados H2. O objetivo é avaliar suas habilidades em CRUD, Orientação a Objetos, SOLID e testes unitários.

## Requisitos

1) **Modelo:** Crie um modelo _Task_ que representará uma tarefa com as seguintes propriedades:

    **id (Long):** Identificador único da tarefa.
    **description (String):** Descrição da tarefa.
    **completed (boolean):** Status da tarefa (completa ou não).

2) **Repositório:** Utilize o Spring Data JPA para criar um repositório para a entidade Task.

3) **Serviço:** Implemente uma camada de serviço com os métodos CRUD para Task.

4) **Controller:** Desenvolva um controller REST para gerenciar as tarefas, contendo endpoints para criação, consulta, atualização e remoção de tarefas.

4) **Testes:** Escreva testes unitários para o seu controller utilizando JUnit e MockMvc.

5) **Configuração:** Utilize o banco de dados em memória H2 para armazenar as tarefas e configure-o no arquivo application.properties.

## Avaliação

A avaliação será feita com base nos seguintes critérios:

- **Funcionalidade:** Todos os endpoints CRUD devem estar funcionando corretamente.
- **Estrutura de código:** O código deve estar bem estruturado(organização e clareza), seguindo os princípios de Orientação a Objetos e SOLID.
- **Testes unitários:** O código deve estar coberto por testes unitários.
- **Histórico de commits:** Os commits do projeto devem contar uma história, mostrando a evolução do código.
- **Documentação:** O projeto deve conter um arquivo README.md com as instruções de execução e configuração.
- **Entrega:** O projeto deve ser entregue através de um repositório Git (GitHub, GitLab, Bitbucket, etc).
- **Bônus (opcional):** Implementar a autenticação com JWT.
- **Questionário:** Responda o questionário abaixo.

## Questionário

- O que são os princípios SOLID? Descreva cada um deles.
- Quais são as principais anotações usadas no Spring Boot para criar um serviço RESTful?
- O que é injeção de dependência e por que é importante?
- Como você define testes unitários e por que eles são importantes?
- Qual a diferença entre @Component, @Repository, @Service e @Controller no Spring Boot?
- O que é JPA e qual é o seu propósito?
- O que faz a anotação @Transactional no Spring Boot?
- Descreva o que é um Mock e por que ele é útil em testes.
- Qual a diferença entre um banco de dados relacional e um banco de dados NoSQL?
- O que são e como funcionam os padrões REST?