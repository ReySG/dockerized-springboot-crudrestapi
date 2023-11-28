
Spring Boot CRUD
Este un simple CRUD REST api para crear, borrar, obtener y eliminar usuarios

Tecnologías Utilizadas:
Spring Boot 3
Docker Compose
PostgreSQL

Generar Jar:
- ./mvnw clean package -DskipTests
  
Build:
- docker-compose build
  
Ejecucion:
-  docker-compose up  

EndPoints:
Crear usuario: POST http://localhost:8080/api/users
Obtener usuario por id: GET http://localhost:8080/api/users/{id}
Obtener todos los usuarios: GET http://localhost:8080/api/users

