# microservice-1
Microservice-1: Endpoint de carga de archivos

Este microservicio forma parte del proyecto multi-module "spring-boot-microservices" desarrollado con Spring Boot y Gradle. Proporciona un endpoint POST (/productos/cargar) para cargar un archivo CSV que contiene información de productos y procesarlo para almacenar los datos en una base de datos MySQL.

Características principales:
- Permite cargar un archivo CSV con datos de productos a través del endpoint POST (/productos/cargar).
- Procesa el archivo CSV y almacena la información de los productos en la base de datos.
- Utiliza Spring Boot para la configuración y el desarrollo del microservicio.
- Se integra con una base de datos MySQL para el almacenamiento persistente de los datos.
- Implementa pruebas unitarias utilizando JUnit y Mockito para garantizar la calidad del código.
