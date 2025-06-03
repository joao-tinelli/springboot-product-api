# Spring Boot Product API

A simple REST API for registering, retrieving, updating, and deleting products using **Spring Boot**, **JPA**, and **H2 in-memory database**. Built as part of my backend development learning journey.

## 🚀 Technologies Used

- Java 17+ (or your version)
- Spring Boot
- Spring Data JPA
- H2 Database (in-memory)
- Maven
- Postman (for API testing)

## 📦 Features

- `POST /produtos` → Create a new product  
- `GET /produtos/{id}` → Get a product by ID  
- `PUT /produtos/{id}` → Update a product  
- `DELETE /produtos/{id}` → Delete a product  
- `GET /produtos?nome=xyz` → Search for products by name  

## 🧪 Testing the API with Postman

You can use Postman to test the endpoints. Here's a sample `POST` request body to create a product:

```json
{
  "nome": "Notebook",
  "descricao": "14-inch ultrabook",
  "preco": 3999.99
}
```
## 🔗 H2 Console

- You can access the H2 database console at: http://localhost:8080/h2-console
- Use the following configuration:
- `JDBC URL: jdbc:h2:mem:produtos`
- `Username: sa`
- `Password: password`

## ⚙️ How to Run
- Make sure you have Java and Maven installed. Then, run:
```./mvnw spring-boot:run```
- Or run the application directly from your IDE.


