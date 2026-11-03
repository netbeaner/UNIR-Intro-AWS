# Despliegue de Instancia Windows Server en AWS

Este documento contiene las evidencias gráficas paso a paso sobre la creación, configuración y acceso a la instancia EC2 con Windows Server.

## 1. Selección de Imagen de Sistema Operativo (AMI)
<img width="1226" height="692" alt="CrearInstancia_selecciona_imagen_windows" src="https://github.com/user-attachments/assets/68c898fa-a94a-4333-8e25-fd674bd365a9" />

Configuración del tipo de instancia

<img width="1231" height="697" alt="selecciona_tipo_instancia_y_keypair" src="https://github.com/user-attachments/assets/29f55c3f-3edc-481d-bf92-d6241e170e03" />

Instancia iniciada satisfactoriamente

<img width="917" height="339" alt="Instancia_Windows_creada" src="https://github.com/user-attachments/assets/d03f6b99-8e17-47aa-90b3-3f47e704e40c" />



## 2. Configuración de Red y Grupos de Seguridad

Security Group
<img width="1648" height="505" alt="Captura de pantalla 2026-11-01 212943" src="https://github.com/user-attachments/assets/01908a22-ed9d-452d-898a-49b49411ffa6" />

Configuración de las inbound rules para permitir acceso remoto
<img width="939" height="751" alt="Captura de pantalla 2026-11-01 225012" src="https://github.com/user-attachments/assets/714fc491-b663-441a-bdea-038b309e3611" />




## 3. Conexión a Instancia de Windows. Obtención del password
<img width="1275" height="735" alt="Localización_Security_group" src="https://github.com/user-attachments/assets/b67824c1-49e5-41da-adf7-1513b4f40a0c" />


Obtenemos el password para poder conectarnos

<img width="1818" height="710" alt="Captura de pantalla 2026-11-01 213803" src="https://github.com/user-attachments/assets/01d37f67-9c5c-4c4f-8303-6116bb7d777a" />

<img width="948" height="639" alt="Captura de pantalla 2026-11-01 213929" src="https://github.com/user-attachments/assets/40719e2f-1a7a-463d-a3a4-436a1cfddcba" />

<img width="587" height="466" alt="Captura de pantalla 2026-11-01 214049" src="https://github.com/user-attachments/assets/e7eefe74-ecd5-4ac9-9766-65aa84d3dfec" />


Ingresamos credenciales para conexión remota vía "Escritorio Remoto de Windows"
<img width="401" height="480" alt="Captura de pantalla 2026-11-01 214219" src="https://github.com/user-attachments/assets/b8f0bcde-6667-4246-b01b-ef6d8cac4913" />

<img width="451" height="426" alt="Captura de pantalla 2026-11-01 214148" src="https://github.com/user-attachments/assets/8be8789d-16ac-44dd-a8f4-442984dee7ca" />

<img width="407" height="485" alt="Captura de pantalla 2026-11-01 214209" src="https://github.com/user-attachments/assets/58d2b388-4d4c-4cfa-b130-975cc8004226" />


Se establece conexión con la instancia Windows de EC2
<img width="654" height="526" alt="Captura de pantalla 2026-11-01 214332" src="https://github.com/user-attachments/assets/802b51a8-e628-435e-b26f-3d954df0b37f" />


## 4. Instalación de Apache en Servidor Windows

<img width="1038" height="538" alt="Captura de pantalla 2026-11-01 215525" src="https://github.com/user-attachments/assets/cb65da43-3a9b-4591-aadb-6ddd679fb299" />


Se levanta el servicio de Apache 
<img width="619" height="449" alt="Captura de pantalla 2026-11-01 215612" src="https://github.com/user-attachments/assets/55508672-51e2-48e3-8fc7-1ca20b5d3a31" />

Se prueba la aplicación default

<img width="751" height="232" alt="Captura de pantalla 2026-11-01 215727" src="https://github.com/user-attachments/assets/c9474bbf-9257-46f6-8f38-6c52555f31f7" />

Subimos la aplicación Breakout para despliegue en Windos

<img width="770" height="360" alt="Captura de pantalla 2026-11-01 220616" src="https://github.com/user-attachments/assets/392ac12a-5dd7-415a-a4ca-7ee5bb25086e" />


Se despliega satisfactoriamente la aplicación Breakout
<img width="1610" height="970" alt="Captura de pantalla 2026-11-01 220741" src="https://github.com/user-attachments/assets/8cdba0dd-f349-45d8-bde1-aadfb302c49c" />






## 5. Reglas de Firewall y Acceso

Fue necesario agregar una regla para acceder al puerto 80 
<img width="945" height="251" alt="Captura de pantalla 2026-11-01 225348" src="https://github.com/user-attachments/assets/07c7cf52-785c-40e8-a990-569a3ee27e5b" />

## 6. Aplicación desplegada y accesible por internet

Finalmente se accede a la aplicación desplegada en Windows en EC2 AWS
<img width="502" height="87" alt="Captura de pantalla 2026-11-01 221350" src="https://github.com/user-attachments/assets/25e626f0-a2a5-4c64-b837-26df0e86dd96" />


<img width="950" height="1026" alt="Captura de pantalla 2026-11-01 223843" src="https://github.com/user-attachments/assets/a96604e8-1229-4851-abfc-de8e436afb71" />

