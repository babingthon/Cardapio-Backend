# 📋 API de Cardápio em Java

Esta é uma API REST desenvolvida em **Java** para gerenciamento de um cardápio. Ela permite **listar** e **cadastrar** itens de forma simples e eficiente.

## 🚀 Funcionalidades

- 🔍 Listar todos os itens do cardápio
- ➕ Cadastrar novos itens
- 🔧 (Opcional) Atualizar e remover itens *(implemente se desejar)*

## 🛠️ Tecnologias Utilizadas

- Java 17+
- Spring Boot
- Spring Web
- Spring Data JPA
- Banco de Dados: H2 / PostgreSQL 
- Maven / Gradle

## 📦 Endpoints

| Método | Rota            | Descrição                  |
|--------|------------------|----------------------------|
| GET    | `/food`      | Lista todos os itens       |
| POST   | `/food`      | Cadastra um novo item      |

### Exemplo de JSON para cadastro:

```json
{
  "title": "Pizza Margherita",
  "image": "https://anamariareceitas.com.br/wp-content/uploads/2024/07/5520-768x512.jpg",
  "price": 29.90
}
```
- git clone https://github.com/babingthon/Cardapio-Backend.git
- cd Cardapio-Backend

- ./mvnw spring-boot:run
- http://localhost:8080/food





