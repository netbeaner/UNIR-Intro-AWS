# Anexo: Configuración e Implementación de Base de Datos MySQL

En este documento se detallan todas las evidencias gráficas correspondientes al Punto 4 de la práctica de Administración de Sistemas.

## Paso 1: Creación del servicio/instalación de MySQL
Proceso de despliegue del servicio de base de datos MySQL (ya sea mediante RDS u otro servicio administrado, o instalación manual en servidor).
![Instalación MySQL](./img/mysql/[nombre_imagen_1.png])

## Paso 2: Configuración de red y accesos
Configuración del puerto 3306 y ajustes de seguridad para permitir conexiones públicas o desde IPs específicas.
![Seguridad Puerto 3306](./img/mysql/[nombre_imagen_2.png])

## Paso 3: Creación de usuarios y asignación de privilegios
Comandos ejecutados o configuración en panel para la creación del usuario de base de datos y la concesión de permisos.
![Configuración de Usuarios](./img/mysql/[nombre_imagen_3.png])

## Paso 4: Configuración del cliente SQL
Introducción de las credenciales, host (Endpoint/IP) y puerto en la herramienta cliente local (ej. MySQL Workbench, DBeaver).
![Configuración Cliente SQL](./img/mysql/[nombre_imagen_4.png])

## Paso 5: Prueba de conexión exitosa
Evidencia final de la conexión a la base de datos, mostrando la estructura vacía o una consulta simple (`SHOW DATABASES;`).
![Conexión Exitosa Base de Datos](./img/mysql/[nombre_imagen_5.png])