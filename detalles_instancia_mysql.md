# Anexo: Configuración e Implementación de Base de Datos MySQL

## Paso 1: Creación del servicio/instalación de MySQL
Proceso de despliegue del servicio de base de datos MySQL (ya sea mediante RDS u otro servicio administrado, o instalación manual en servidor).
<img width="1900" height="854" alt="Captura de pantalla 2026-11-01 230504" src="https://github.com/user-attachments/assets/017314d9-f1c6-4dc9-aefb-2635ae597c97" />

<img width="1823" height="866" alt="Captura de pantalla 2026-11-01 230840" src="https://github.com/user-attachments/assets/44da12a4-3f1b-4bc7-977d-8e6da6aeebb2" />

<img width="1915" height="490" alt="Captura de pantalla 2026-11-01 231126" src="https://github.com/user-attachments/assets/28eda237-54ff-4c07-888c-a632e8857ea0" />

<img width="1887" height="769" alt="Captura de pantalla 2026-11-01 232118" src="https://github.com/user-attachments/assets/c5b76d3e-786f-42fb-800e-fe5c76ba18f0" />







## Paso 2: Configuración de red y accesos
Configuración del puerto 3306 y ajustes de seguridad para permitir conexiones públicas o desde IPs específicas.
<img width="1671" height="448" alt="Captura de pantalla 2026-11-01 232711" src="https://github.com/user-attachments/assets/b677f781-17a9-49fb-a7f5-35bed67b5dc5" />

<img width="1682" height="548" alt="Captura de pantalla 2026-11-01 232720" src="https://github.com/user-attachments/assets/3f89aaf8-0549-44bb-80f3-f1094084b7b6" />

<img width="1682" height="659" alt="Captura de pantalla 2026-11-01 233721" src="https://github.com/user-attachments/assets/3430634f-0114-4cd4-9308-22a2615ca736" />

<img width="937" height="873" alt="Captura de pantalla 2026-11-01 233934" src="https://github.com/user-attachments/assets/1b6dfb8e-6688-4500-a20a-ddd3e64b8065" />

<img width="944" height="726" alt="Captura de pantalla 2026-11-01 233953" src="https://github.com/user-attachments/assets/416f9b4b-1fd6-4450-a5df-0c077a389586" />








## Paso 3: Creación de usuarios y asignación de privilegios
Comandos ejecutados o configuración en panel para la creación del usuario de base de datos y la concesión de permisos.
![Configuración de Usuarios](./img/mysql/[nombre_imagen_3.png])

## Paso 4: Configuración del cliente SQL
Introducción de las credenciales, host (Endpoint/IP) y puerto en la herramienta cliente local (ej. MySQL Workbench, DBeaver).



<img width="683" height="796" alt="Captura de pantalla 2026-11-01 234519" src="https://github.com/user-attachments/assets/07e6336c-94f7-4ad7-999a-858a0473a167" />


<img width="699" height="799" alt="Captura de pantalla 2026-11-01 234530" src="https://github.com/user-attachments/assets/31d38ed5-df48-4188-b119-47626cea6097" />

## Paso 5: Prueba de conexión exitosa
Evidencia final de la conexión a la base de datos, mostrando la estructura vacía o una consulta simple (`SHOW DATABASES;`).
<img width="1151" height="805" alt="Captura de pantalla 2026-11-01 234648" src="https://github.com/user-attachments/assets/8b4b5e89-1e2c-4801-ad7f-0249c5e9e15d" />

<img width="686" height="793" alt="Captura de pantalla 2026-11-01 234559" src="https://github.com/user-attachments/assets/4b337636-8f3c-4166-8e39-59fe6f7b1f31" />

## Paso 6: Deteniendo la base de datos (porque ya no se va a usar)

<img width="1910" height="484" alt="Captura de pantalla 2026-11-01 234930" src="https://github.com/user-attachments/assets/3398cf9f-4e0a-4be2-bcf9-242e93fb9280" />




