# 🎓 Student Service  

The **Student Service** manages student-related operations, including registration, borrowing books, and returning books.

## 🚀 Features  
- Add, update, and delete student records  
- Manage borrowed books  
- Check overdue books  

## 🔗 API Endpoints  
| Method | Endpoint | Description |
|--------|---------|------------|
| `POST` | `/students` | Register a new student |
| `GET` | `/students/{id}` | Get student details |
| `PUT` | `/students/{id}` | Update student details |
| `DELETE` | `/students/{id}` | Remove student record |

## 🛠️ Tech Stack  
- Spring Boot  
- Spring Data JPA (MySQL/PostgreSQL)  
- Eureka Client (Service Discovery)  
- Feign Client (Inter-service communication)  

## 🏃 How to Run  
```sh
mvn spring-boot:run
