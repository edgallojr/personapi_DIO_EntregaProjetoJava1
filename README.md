<h2>Sistema de gerenciamento de pessoas em API REST com Spring Boot</h2>

Projeto desenvolvido em Java de um pequeno sistema para o gerenciamento de pessoas de uma empresa através de uma API REST, criada com o Spring Boot.

* Setup inicial de projeto com o Spring Boot Initialzr;
* Criação de modelo de dados para o mapeamento de entidades em bancos de dados;
* Desenvolvimento de operações de gerenciamento de usuários (Cadastro, leitura, atualização e remoção de pessoas de um sistema), com o padrão arquitetural REST;
* Desenvolvimento de testes unitários para validação das funcionalidades;
* Implantação do sistema na nuvem através do Heroku;

Para executar o projeto no terminal, digite o seguinte comando:

```shell script
mvn spring-boot:run 
```

Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080/api/v1/people
```

Também disponível para testes, via Postman, no endereço abaixo:

```
https://person-api-rest-java.herokuapp.com/api/v1/people/
```

![image](https://user-images.githubusercontent.com/85174365/132578854-59257ac9-113c-4bbb-b617-84bc2bfc6f99.png)
