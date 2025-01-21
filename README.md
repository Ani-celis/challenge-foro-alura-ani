# challenge-foro-alura-ani
## Challenge_Foro_Alura
# Foro Alura - API REST

## 📜 Descripción del Proyecto
El Foro Alura es un espacio creado para que los alumnos de la plataforma Alura puedan compartir dudas, ideas y conocimientos sobre los diferentes cursos disponibles. Este foro fomenta el aprendizaje y la colaboración entre alumnos, profesores y moderadores.

El proyecto busca entender y replicar cómo funciona el Foro Alura desde una perspectiva técnica, abordando aspectos como el almacenamiento de información, la relación entre tópicos y respuestas, y cómo los usuarios interactúan con estos elementos. Nuestro desafío será construir una API REST que implemente estas funcionalidades utilizando Spring.

### Características Principales
Nuestra API se centrará en la gestión de tópicos, permitiendo:

- **Crear un nuevo tópico.**
- **Listar todos los tópicos existentes.**
- **Visualizar un tópico específico.**
- **Actualizar un tópico existente.**
- **Eliminar un tópico.**

Adicionalmente, se implementarán las siguientes funcionalidades:

- **Sistema de autenticación:** Los usuarios deberán autenticarse para gestionar los recursos de la API.
- **Gestión de recursos adicionales:** Crear, editar, listar y eliminar información relacionada con Respuestas, Cursos y Usuarios.
- **Persistencia de datos:** Almacenar y gestionar los datos en una base de datos estructurada.

---

## 🖥️ Tecnologías Utilizadas

### Lenguajes y Herramientas
- **Java 17:** Lenguaje principal para la construcción de la API.
- **Spring Framework:** Framework utilizado para la creación de la API REST.
    - **Spring Security:** Para la implementación del sistema de autenticación.
- **JPA Hibernate:** Para la gestión de la persistencia de datos.
- **Token JWT:** Mecanismo para autenticar y autorizar usuarios.

### Entorno y Base de Datos
- **IntelliJ IDEA:** Entorno de desarrollo integrado (IDE).
- **MySQL:** Sistema de gestión de bases de datos para almacenar la información.
- **Insomnia:** Herramienta para probar y documentar las solicitudes API.

### Recursos Adicionales
- [IntelliJ IDEA](https://www.jetbrains.com/idea/)
- [MySQL](https://www.mysql.com/)
- [Spring Initializr](https://start.spring.io/)
- [JWT](https://jwt.io/)

---

## 🚀 Cómo Empezar

1. **Clonar el repositorio:**
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   ```

2. **Configurar la base de datos:**
    - Crear una base de datos en MySQL.
    - Configurar las credenciales en el archivo `application.properties` o `application.yml`.

3. **Ejecutar el proyecto:**
   ```bash
   ./mvnw spring-boot:run
   ```

4. **Acceder a la API:**
    - URL base: `http://localhost:8080`

---

## 🛠️ Estructura del Proyecto
El proyecto sigue una arquitectura MVC (Modelo-Vista-Controlador):

- **Modelos:** Representan las entidades de la base de datos.
- **Controladores:** Gestionan las solicitudes HTTP.
- **Servicios:** Contienen la lógica de negocio.
- **Repositorios:** Realizan operaciones con la base de datos.

---

## 🌟 Próximos Pasos
- Implementar paginación y filtros en las consultas de tópicos.
- Añadir validaciones y manejo de errores personalizados.
- Documentar la API utilizando Swagger.
- Integrar pruebas unitarias y de integración.

---
## 🌟 Funcionamiento:


# challenge-foro-alura-ani
