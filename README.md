# SBA301 - Lab 05: Single Page Application with Spring Boot RESTful API

Orchid Management full-stack application using Spring Boot 3, Spring Data JPA, SQL Server, and React with Vite.

## Structure

- `chapter15api`: Spring Boot backend REST API
- `chapter15reactjs`: React Vite frontend SPA

## Quick Run

### 1. Database
Ensure Microsoft SQL Server is running with database `OrchidManagementDB`.

### 2. Backend
```bash
cd chapter15api
mvn spring-boot:run
```
Backend API will listen at http://localhost:8080/orchids

### 3. Frontend
```bash
cd chapter15reactjs
npm install
npm run dev
```
Frontend will be accessible at http://localhost:5173

### 4. REST Endpoints
- `GET /orchids/` - Retrieve all orchids
- `GET /orchids/{id}` - Retrieve orchid by ID
- `POST /orchids/` - Create a new orchid
- `PUT /orchids/{id}` - Update an existing orchid
- `DELETE /orchids/{id}` - Delete an orchid by ID
