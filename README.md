# Product Management RESTful API

A complete, production-ready RESTful API for managing products, built with Spring Boot. This backend project allows developers to perform fundamental CRUD operations (Create, Read, Update, Delete) on an in-memory product database and returns responses in JSON format.

## 🚀 Tech Stack
- **Java 17**
- **Spring Boot 3.2.4**
- **Maven**
- **RESTful Architecture**

## 🧩 Features
- **GET All Products**: Fetch all existing products.
- **GET Product by ID**: Fetch a specific product using its ID.
- **POST Product**: Create a new product entry.
- **PUT Product**: Update a specific product's details.
- **DELETE Product**: Remove a product from the database.

## 🔗 API Endpoints

| HTTP Method | Endpoint | Description |
| :--- | :--- | :--- |
| **GET** | `/api/products` | Retrieve a list of all products |
| **GET** | `/api/products/{id}` | Retrieve a specific product by its ID |
| **POST** | `/api/products` | Add a new product to the list |
| **PUT** | `/api/products/{id}` | Update an existing product by its ID|
| **DELETE** | `/api/products/{id}` | Delete a specific product |

## 🛠️ Data Model
The Product JSON object consists of:
```json
{
  "id": 1,
  "name": "Laptop",
  "description": "High-performance laptop",
  "price": 1200.5
}
```

## ⚙️ Running Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/aithanaveen/Product-Management-using-RESTful-API.git
   cd Product-Management-using-RESTful-API
   ```

2. **Run the Spring Boot application:**
   If you have Maven in your PATH:
   ```bash
   mvn spring-boot:run
   ```
   Or open the project in **IntelliJ IDEA / Eclipse / VS Code** and run the `ProductApplication.java` main class.

3. The server will start on `http://localhost:8080`.

## 🧪 Testing the API
You can test the APIs in VS Code using the REST Client extension or with tools like Postman:
- An **`api.http`** file is already included in the workspace! You can open it in VS Code or IntelliJ, and directly click "Send Request" to test all interactions via your local machine.