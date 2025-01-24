# List Games

DSList é uma API RESTful desenvolvida em Java com Spring Boot. O projeto permite gerenciar listas de jogos, com funcionalidades para listar jogos, buscar por ID e organizar jogos por listas específicas. Ele utiliza Postgres para o banco de dados principal e H2 para testes, com integração via Docker para facilitar o setup.

# Tecnologias Utilizadas
- Java 17
- Spring Boot
    - Spring JPA
    - H2
    - Spring Web
- Postgres
- Docker

# Funcionalidades

- Listar todos os jogos cadastrados.
- Buscar um jogo por ID.
- Listar jogos organizados por listas.
- Gerenciar listas de jogos.

# Pré-requisitos

- Java, Maven
- Docker
- IDE 

# Como Configurar o Projeto

```
# Clonar projeto 
https://github.com/leowingss/dslist.git

# Compile 
./mvnw clean install

# Execute
./mvnw spring-boot:run

# Acesse o banco H2
http://localhost:8080/h2-console

# Credenciais padrão:
JDBC URL: jdbc:h2:mem:testdb
Usuário: sa
Senha: (deixe em branco)
```

# Documentação da API
O Swagger está configurado para documentar e testar os endpoints. Após iniciar o projeto, você pode acessar a interface Swagger UI em:

http://localhost:8080/swagger-ui.html