# Warehouse Allocation System
 
Spring Boot backend project for warehouse inventory allocation and stock transfer management using REST APIs, Swagger UI, and H2 Database.
 
---
 
## Features
 
- Warehouse Management
- Product Management
- Inventory Management
- Product Allocation
- Stock Transfer Between Warehouses
- REST APIs
- Swagger API Documentation
- H2 In-Memory Database
- Layered Architecture
 
---
 
## Technologies Used
 
- Java 17
- Spring Boot
- Spring Data JPA
- H2 Database
- Maven
- Lombok
- Swagger OpenAPI
 
---
 
## Project Structure
 
```text
src/main/java/com/example/warehouse
 
controller
service
service/impl
repository
entity
dto
mapper
exception
config
util
audit
```
 
---
 
## API Endpoints
 
### Warehouse APIs
 
- GET /api/warehouses
- GET /api/warehouses/{id}
- POST /api/warehouses
- PUT /api/warehouses/{id}
- DELETE /api/warehouses/{id}
 
### Product APIs
 
- GET /api/products
- GET /api/products/{id}
- POST /api/products
 
### Inventory APIs
 
- POST /api/inventory
 
### Allocation APIs
 
- POST /api/allocations
 
### Stock Transfer APIs
 
- POST /api/transfers
 
---
 
## Swagger UI
 
Open:
 
```text
http://localhost:8080/swagger-ui/index.html
```
 
---
 
## H2 Database Console
 
Open:
 
```text
http://localhost:8080/h2-console
```
 
### JDBC URL
 
```text
jdbc:h2:mem:testdb
```
 
### Username
 
```text
sa
```
 
### Password
 
Leave empty.
 
---
 
## How to Run Project
 
### Clone Repository
 
```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/warehouse-allocation-system.git
```
 
### Open Project
 
Import project into Eclipse or IntelliJ.
 
### Run Application
 
Run:
 
```text
WarehouseAllocationSystemApplication.java
```
 
---
 
## Author
 
Swathi Palla
 
