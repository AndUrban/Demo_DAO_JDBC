# Projeto DAO (Data Access Object) - Acesso ao Banco de Dados com JDBC
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/AndUrban/demo-dao-jdbc/blob/main/LICENSE)


# Sobre o projeto

Oferecida pela [DevSuperior](https://devsuperior.com "Site da DevSuperior"),o projeto
consiste em um desenvolvimento de um sistema na qual manipula dados no banco de dados MySql
através da aplicação do padrão DAO - Data Access Object. Para cada entidade, haverá um
objeto responsável por fazer acesso a dados relacionado a essa entidade. Cada DAO é definido
por uma interface. A injeção de dependência é feita por meio do padrão de projeto factory.


## Modelo de Domínio
![Modelo Conceitual](https://github.com/AndUrban/Assets/blob/main/Assets/webServicesSpringBoot_1.png)
## Inteface de Domínio
![Modelo Conceitual](https://github.com/AndUrban/Assets/blob/main/Assets/webServicesSpringBoot_2.png)
## Camadas Lógicas (Logical Layers)
![Modelo Conceitual](https://github.com/AndUrban/Assets/blob/main/Assets/webServicesSpringBoot_3.png)

# Tecnologias utilizadas
- Java
- Spring Boot
- JPA / Hibernate
- Maven

# Execução
Pré-requisitos: JavaSE 21

```bash
# clonar repositório:
git clone https://github.com/AndUrban/workshop-springboot3-jpa.git

# Dentro da IDE, importar o projeto:
course

# Caminho para a execução:
course/src(src/main/java)/com.myeducandoweb.course/CourseApplication.java

-> Run as Spring Boot App

# Abrir o link:
http://localhost:8080/h2-console

Conferir as seguintes informações:
Driver class: org.h2.Driver
JDBC URL: jdbc:h2:mem:testdb
User Name: sa
Password: (não tem)

-> Clicar em "Connect"
```

# Agradecimentos
Dr. Nélio Alves - DevSuperior: Escola de Programação

## LinkedIn
www.linkedin.com/in/andurban
