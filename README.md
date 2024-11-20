# Java Spring Expert Exercício: Empregados Auth 


# Sobre o projeto
Este projeto é um exercício do capítulo sobre Validação e Segurança do Curso Java Spring Expert da [DevSuperior](https://devsuperior.com.br "Site da DevSuperior").
O exercício consiste em implementar as funcionalidades necessárias para que os testes passem.


## Especificações e Modelo Conceitual
Este é um sistema de funcionários e departamentos com uma relação N-1 entre eles:
![Modelo Conceitual](https://github.com/GabrielSilva2310/Assets/blob/main/Images%20Java%20Spring%20Expert/Valida%C3%A7%C3%A3o%20e%20Seguran%C3%A7a/Modelo%20Conceitual.png)

Regras de controle de acesso:

-Todas as rotas são protegidas.

-Usuários ADMIN podem ler e alterar recursos, enquanto que usuários OPERATOR podem apenas ler.


Regras de validações de Employee:

-Nome não pode ser vazio

-Email deve ser válido

-Departamento não pode ser nulo



# Tecnologias utilizadas
- Java 17
- Spring Boot 3
- Maven
- JPA / Hibernate
- H2 Database
- JUnit 5
- Postman

# Postman Collection
  Para testar a API, você pode usar a coleção do Postman disponível no link abaixo:
  
  [Download](https://github.com/GabrielSilva2310/Assets/blob/main/Postman%20Collections%20and%20Enviroments/Spring%20Expert/Empregados-Auth/Desafio%20Empregados%20Auth.postman_collection%20(1).json)

# Como executar o projeto

Pré-requisitos: Java 17

```bash
# clonar repositório
git clone https://github.com/GabrielSilva2310/Spring-Expert-Empregados-Auth.git
```
Importar Projeto para uma IDE de sua escolha , e executar o JUnit nas classes DepartmentControllerIT.java e EmployeeControllerIT.java.

Use o Postman para fazer as requisições e verificar se os resultados correspondem aos testes.

# Autor

Gabriel Da Silva 

www.linkedin.com/in/gabriel-da-silva-457039193
