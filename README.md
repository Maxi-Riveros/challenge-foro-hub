# challenge-foro-hub
# 🌟 Funcionalidades de la API
- ➕ **Crear un nuevo tópico**: Permite crear nuevos tópicos.
- 📄 **Mostrar todos los tópicos creados**: Lista todos los tópicos.
- 🔍 **Mostrar un tópico específico**: Muestra detalles de un tópico por ID.
- ✏️ **Actualizar un tópico**: Actualiza la información de un tópico existente.
- ❌ **Eliminar un tópico**: Realiza una eliminación lógica del tópico.

## 🎯 Objetivos del Challenge
- Implementar una API REST siguiendo las mejores prácticas de REST.
- Validaciones según las reglas de negocio.
- Implementación de una base de datos relacional (MySQL).
- Servicio de autenticación/autorización con JWT.

## 🛠️ Tecnologías Utilizadas
- Java 17
- Spring Boot
- Spring Security
- Spring Data JPA
- Validation
- MySQL
- Flyway Migration
- GitHub
- IntelliJ IDEA
- Trello
- Postman
- Insomnia

## 📋 Tablas Utilizadas
- **Usuario**: Datos de los usuarios del foro.
- **Tópico**: Publicaciones con título, mensaje y fecha de creación.
- **Respuesta**: Respuestas a los tópicos.
- **Curso**: Relaciona tópicos con cursos.

## ⚙️ Configuración
1. Crea una base de datos en MySQL llamada `alura_foro_api`.
2. Configura las siguientes variables de entorno:
    - `${DB_HOST}`: Por defecto `localhost`
    - `${DB_NAME}`: `alura_foro_api`
    - `${DB_USER}`: Usuario de MySQL
    - `${DB_PASS}`: Contraseña de MySQL
