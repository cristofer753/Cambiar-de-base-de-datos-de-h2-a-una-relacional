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


## Cambios en configuración de la Base de Datos

El archivo `application.properties` contiene la configuración necesaria para conectar la aplicación a una base de datos PostgreSQL:

![image](https://github.com/cristofer753/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/141539505/5d1480a3-df04-42d1-9550-db99cd898fdf)

### Ejecucion del codigo

![image](https://github.com/cristofer753/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/141539505/f00c49e0-3bcd-4809-ae46-b5877bb32bf4)

# Tabla hotel en mi base de datos postgresql

![image](https://github.com/cristofer753/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/141539505/211857fd-74d3-465c-a328-f831d70cce46)

![image](https://github.com/cristofer753/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/141539505/ab012b46-3635-4512-93d8-7be8e9d3b342)

![image](https://github.com/cristofer753/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/141539505/ec2fb87b-2c37-4254-ad59-a15f9872c6fb)

# Probando get en THUNDER CLIENT y en un BROWSER

![image](https://github.com/cristofer753/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/141539505/2831d477-8536-4ae1-8e69-2a0c2345b7ff)

![image](https://github.com/cristofer753/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/141539505/a6b2185d-09be-408b-8ef4-975a7b1f92ec)

### FIN
