# 📦 CRUD API-REST MVC

Este é um projeto backend desenvolvido com o objetivo de aprendizado e boas práticas de desenvolvimento de APIs REST. Ele segue o padrão arquitetural **MVC** e foi criado com foco em estudo, código em inglês para aprimorar o idióma.

---

## 🚀 Stack

- ✅ Java 21
- ✅ Spring Boot
- ✅ Spring Data JPA
- ✅ PostgreSQL
- ✅ Swagger (Documentação da API)
- ✅ Maven
- ✅ Docker

---

## 🧱 Estrutura do Projeto

- **controller** = Camada de controle (endpoints REST)
- **model** = Entidades JPA (Client, Product, Sale)
- **repository** = Interfaces para acesso ao banco
- **service** = Camada de lógica de negócio


---

## 📌 Funcionalidades

- ✅ CRUD de **Clientes**
- ✅ CRUD de **Produtos**
- ✅ Registro de **Vendas**, relacionando um cliente com um ou mais produtos
- ✅ Documentação da API com Swagger


---

## 🔧 Como executar

1. Clone o repositório:
   git clone https://github.com/brunoness/CRUD-API-MVC.git

2. Configure o PostgreSQL com um banco chamado tarefa42 e ajuste as credenciais no .env.
    DB_URL=jdbc:postgresql://localhost:5432/tarefa42
    DB_USERNAME=seu_usuario
    DB_PASSWORD=sua_senha

3. Execute o projeto pela sua IDE ou com:
    ./mvnw spring-boot:run

4. Acesse a documentação Swagger em:
    http://localhost:8080/swagger-ui/index.html
    
OBS. A criação das tabelas é feita automaticamente via JPA.
