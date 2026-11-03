# Anexo: Configuración y Despliegue de Instancia Linux

En este documento se detallan las evidencias gráficas correspondientes al despliegue de la instancia de Linux para la práctica de Administración de Sistemas.

## Paso 1: Configuración inicial de la instancia Linux en EC2
Inicio del proceso de creación de la instancia, seleccionando la imagen del sistema operativo (Linux) y los recursos necesarios.

<img width="927" height="335" alt="Nombre_instancia" src="https://github.com/user-attachments/assets/74996caa-7826-4196-9a35-447a6e25cc83" />

<img width="931" height="277" alt="Tipo_instancia" src="https://github.com/user-attachments/assets/2141f214-b696-42f2-9749-dc1a4593a1e4" />

Creación de la llave privada para conexión remota vía consola

<img width="937" height="839" alt="Key_pair" src="https://github.com/user-attachments/assets/09c3c306-aee0-4171-95b1-9836b394dc60" />
Configuraciones finales
<img width="954" height="647" alt="Configure_storage" src="https://github.com/user-attachments/assets/8ee92137-2688-4596-b142-5a69b01fe82f" />

Finalización de la creación de la instancia

<img width="919" height="384" alt="Launch_instance" src="https://github.com/user-attachments/assets/09021f94-3620-4821-b707-0947e706b784" />


## Paso 2: Configuración de red y seguridad
Definición de las reglas del firewall (Security Groups) para permitir el tráfico necesario, como el acceso por SSH (puerto 22) y HTTP (puerto 80).

<img width="953" height="588" alt="Edit_inbound_rule_security" src="https://github.com/user-attachments/assets/2d30224e-aa4f-42a8-aa10-dab3ec7beae8" />

<img width="936" height="602" alt="Outbound_rule" src="https://github.com/user-attachments/assets/3a371dad-54d7-4cd6-b4f4-c46462112a96" />


## Paso 3: Instancia en ejecución
Comprobación en el panel de control de que la instancia se ha desplegado correctamente, se encuentra en estado de ejecución ("Running") y tiene una dirección IP asignada.

<img width="1799" height="855" alt="Connect_linux_instance" src="https://github.com/user-attachments/assets/5c8bd969-559a-41cd-8e03-34ef8c4bce2d" />


## Paso 4: Acceso mediante SSH
Conexión exitosa a la terminal de la instancia Linux utilizando las claves de seguridad generadas.

<img width="666" height="879" alt="Consola_logueado" src="https://github.com/user-attachments/assets/6fb9735e-6ae8-4948-a22e-4f2ea8113001" />

Se transfirió el archivo Netflix.zip que contiene la página a desplegar

<img width="1088" height="206" alt="Captura de pantalla 2026-10-24 133638" src="https://github.com/user-attachments/assets/25b4c3fa-bebd-41b5-9c21-cbbe1c32134f" />

Se lista el archivo recién transferido


<img width="380" height="178" alt="Captura de pantalla 2026-10-24 133705" src="https://github.com/user-attachments/assets/ef7085d7-8b05-42a1-af8d-5092fb972179" />




## Paso 5: Servidor Web operativo
Comprobación final del funcionamiento del servidor web. Se accede a la IP pública desde un navegador y se visualiza la página por defecto de Apache, demostrando que la instalación y las reglas de red son correctas.

<img width="947" height="659" alt="Apache_ready" src="https://github.com/user-attachments/assets/b350cd11-99b8-4a43-9599-427ab8d45d9b" />

Se accede a la aplicación Netflix que fue desplegada en la instancia Linux EC2 de AWS

<img width="1370" height="712" alt="Captura de pantalla 2026-10-24 134651" src="https://github.com/user-attachments/assets/2752e46e-bc2d-466c-b65a-b63aa0359706" />



