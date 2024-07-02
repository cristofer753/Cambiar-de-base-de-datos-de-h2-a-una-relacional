# Cambiar-de-base-de-datos-de-h2-a-una-relacional

# Hotels Application

## Descripción

Esta es una aplicación de ejemplo para gestionar hoteles utilizando Spring Boot y PostgreSQL. La aplicación permite listar hoteles almacenados en una base de datos PostgreSQL.

## Configuración del Proyecto

### Dependencias

- Spring Boot 3.3.1
- Spring Data JPA
- PostgreSQL

### CAMBIOS

Se cambio "seach" en HotelController, HotelService y en HotelServiceImpl ya que parecia ser un error tipográfico y se coloco "search"

# Controller
![image](https://github.com/cristofer753/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/141539505/1a872a6c-c8a4-4215-83d1-84114eefd7d7)

# Service
![image](https://github.com/cristofer753/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/141539505/60cac381-d95c-466b-a658-0d5b7cd7a0cc)

# ServiceImpl
![image](https://github.com/cristofer753/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/141539505/3028e079-cc7b-4de5-963c-94e247597daf)


### Configuración de la Base de Datos

El archivo `application.properties` contiene la configuración necesaria para conectar la aplicación a una base de datos PostgreSQL:

```properties

![image](https://github.com/cristofer753/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/141539505/eaefe4f5-9829-4871-b86b-eb7895d8392a)



