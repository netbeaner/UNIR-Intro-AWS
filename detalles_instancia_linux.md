# Anexo: Configuración y Despliegue de Instancia Linux

En este documento se detallan las evidencias gráficas correspondientes al despliegue de la instancia de Linux para la práctica de Administración de Sistemas.

## Paso 1: Configuración inicial de la máquina virtual
Inicio del proceso de creación de la instancia, seleccionando la imagen del sistema operativo (Linux) y los recursos necesarios.
![Configuración inicial](./img/linux/Captura%20de%20pantalla%202026-10-24%20133538.png)

## Paso 2: Configuración de red y seguridad
Definición de las reglas del firewall (Security Groups) para permitir el tráfico necesario, como el acceso por SSH (puerto 22) y HTTP (puerto 80).
![Configuración de red](./img/linux/Captura%20de%20pantalla%202026-10-24%20133638.png)

## Paso 3: Instancia en ejecución
Comprobación en el panel de control de que la instancia se ha desplegado correctamente, se encuentra en estado de ejecución ("Running") y tiene una dirección IP asignada.
![Instancia en ejecución](./img/linux/Captura%20de%20pantalla%202026-10-24%20133705.png)

## Paso 4: Acceso mediante SSH
Conexión exitosa a la terminal de la instancia Linux utilizando las claves de seguridad generadas.
![Conexión SSH](./img/linux/Captura%20de%20pantalla%202026-10-24%20134651.png)

## Paso 5: Servidor Web operativo
Comprobación final del funcionamiento del servidor web. Se accede a la IP pública desde un navegador y se visualiza la página por defecto de Apache, demostrando que la instalación y las reglas de red son correctas.
![Apache Ready](./img/linux/Apache_ready.png)