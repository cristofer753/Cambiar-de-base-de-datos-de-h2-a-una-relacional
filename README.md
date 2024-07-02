# Cambiar-de-base-de-datos-de-h2-a-una-relacional

# Hotels Application

## Descripción

Esta es una aplicación de ejemplo para gestionar hoteles utilizando Spring Boot y PostgreSQL. La aplicación permite listar hoteles almacenados en una base de datos PostgreSQL.

## Configuración del Proyecto

### Dependencias

- Spring Boot 3.3.1
- Spring Data JPA
- PostgreSQL

### Configuración de la Base de Datos

El archivo `application.properties` contiene la configuración necesaria para conectar la aplicación a una base de datos PostgreSQL:

```properties
server.port=8080

spring.jpa.database=POSTGRESQL
spring.datasource.url=jdbc:postgresql://localhost:5432/postgres
spring.datasource.username=postgres
spring.datasource.password=123
spring.jpa.show-sql=true
spring.jpa.generate-ddl=true
spring.jpa.hibernate.ddl-auto=update
