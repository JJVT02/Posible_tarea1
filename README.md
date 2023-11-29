# Torres_Vico_Jose_Julio_IAW01_Tarea
Realizar la instalación y puesta en marcha de un servidor web Apache, con soporte para bases de datos MySQL y lenguaje del lado del servidor PHP.

Para entregar esta tarea es necesario entregar las capturas de imagen de los principales pasos realizados, explicando en una o dos líneas las decisiones tomadas. Es necesaria una captura final que muestre que el servicio está en funcionamiento.


# Tarea: Instalación y Configuración de Servidor Web

## 1. Instalación de Apache

- Descargar e instalar un software de virtualización (por ejemplo, VirtualBox).
- Crear una máquina virtual con un sistema operativo compatible (por ejemplo, Ubuntu Server).
- Instalar Apache usando el siguiente comando:

```bash
sudo apt-get update
sudo apt-get install apache2
```
![apache](/img/update.png)
![apache](/img/apache.png)

## 2. Instalación de PHP
Instalar PHP y el módulo de Apache para PHP:
```bash
sudo apt-get install php libapache2-mod-php

```
![php](/img/php.png)
Reiniciar el servidor Apache para aplicar cambios:

```bash
sudo systemctl restart apache2
```
![](/img/restart.png)
![]
## 3. Instalación de MySQL
Instalar MySQL Server y Secure Installation:

```bash
sudo apt-get install mariadb-server
```
![](/img/mariadb.png)
```bash
sudo mysql_secure_installation
```
![](/img/secure.png)
Configurar MySQL según las necesidades del proyecto.






