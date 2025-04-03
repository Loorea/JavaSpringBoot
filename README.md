# Java Spring Boot

Repositório para versionamento do projeto do curso de Spring Boot Expert, da Udemy, construído em paralelo com a matéria de Desenvolvimento de Software como Serviço. O curso tem finalidade de aprofundamento de conhecimentos, já que foi sentido a necessidade de conteúdo extra sobre, para o desenvolvimento do projeto final de Projeto Integrador II, em parceria com a empresa Global Transportes.

## Tecnologias Utilizadas

- Java
- Spring Boot
- JUnit
- Banco de Dados (H2 Database)

## Estrutura do Projeto

O projeto está estruturado da seguinte forma (de acordo com o último commit):

```
/src
  ├── main/java/io/github/javaspring/produtosapi
  │   ├── Application.java  # Classe principal
  │   ├── controller/        # Controladores
  │   ├── model/             # Modelos de dados
  │   ├── repository/        # Repositórios
  │   ├── service/           # Serviços
  │
  ├── test/java/io/github/javaspring/produtosapi
  │   ├── Testes unitários e de integração
```

## Como Rodar o Projeto

### Pré-requisitos

Ter o Java instalado (JDK 21 ou superior)

Ter o Maven instalado


Passos

1. Clone o repositório:
   
   git clone https://github.com/Loorea/JavaSpringBoot.git
   
2. Acesse a pasta do projeto:
   
   cd JavaSpringBoot
   
3. Compile e execute o projeto:
   
   mvn spring-boot:run


## Testes

Para executar os testes, utilize:

mvn test
