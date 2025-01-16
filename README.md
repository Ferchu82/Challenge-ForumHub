# ForumHub

**ForumHub** es una API REST desarrollada con Spring Framework para gestionar un foro de discusión. Los usuarios pueden crear, leer, actualizar y eliminar tópicos (CRUD). La API está diseñada siguiendo las mejores prácticas del modelo REST, e incluye validaciones, autenticación/autorización y una base de datos relacional para la persistencia de la información.

## Características principales

- **CRUD de tópicos:** Permite crear, leer, actualizar y eliminar temas de discusión.
- **Autenticación y autorización:** Utiliza JWT para garantizar la seguridad.
- **Validaciones:** Validaciones en los datos de entrada para garantizar consistencia.
- **Modelo REST:** Diseño basado en las mejores prácticas de RESTful APIs.
- **Persistencia de datos:** Integración con una base de datos relacional utilizando JPA y Hibernate.

## Tecnologías utilizadas

- **Backend:** Java con Spring Boot.
- **Seguridad:** Spring Security y JWT.
- **Base de datos:** MySQL o PostgreSQL.
- **Herramientas adicionales:** Maven para la gestión de dependencias.

## Instalación y configuración

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/Ferchu82/ForumHub.git
   cd ForumHub
   ```

2. **Configurar la base de datos:**
   - Crear una base de datos en MySQL o PostgreSQL.
   - Actualizar el archivo `application.properties` con las credenciales de la base de datos.

3. **Construir el proyecto:**
   ```bash
   mvn clean install
   ```

4. **Ejecutar la aplicación:**
   ```bash
   mvn spring-boot:run
   ```

5. **Probar la API:**
   - Acceder a `http://localhost:8080` para probar los endpoints de la API.

## Endpoints principales

- **GET /topics:** Obtener la lista de tópicos.
- **POST /topics:** Crear un nuevo tópico.
- **PUT /topics/{id}:** Actualizar un tópico existente.
- **DELETE /topics/{id}:** Eliminar un tópico.
- **POST /auth:** Autenticación para obtener un token JWT.

## Contribuir

¡Contribuciones son bienvenidas! Por favor, sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una rama para tu funcionalidad o corrección.
   ```bash
   git checkout -b feature/nueva-funcionalidad
   ```
3. Realiza tus cambios y haz un commit.
   ```bash
   git commit -m "Agrega nueva funcionalidad"
   ```
4. Sube tus cambios al repositorio.
   ```bash
   git push origin feature/nueva-funcionalidad
   ```
5. Abre un Pull Request en este repositorio.

## Licencia

Este proyecto está licenciado bajo la licencia MIT. Consulta el archivo `LICENSE` para más información.

