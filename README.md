# Ejemplo de un Cajero Automático con HTML5, CSS3 y JavaScript

## Desarrollador/a:

**Autor**: Diego Alonso Molina (Full Stack Developer)

**GitHub**: https://github.com/DiegusNueva/cajero-ampliado-con-template.git

## Configuración de la máquina virtual de Vagrant:

1. Actualizamos los repositorios de Ubuntu: `sudo apt update`

2. Instalamos NGINX: `sudo apt install nginx`

3. Cambio del DOCUMENT ROOT al directorio /vagrant: 

    `sudo nano /etc/nginx/sites-enabled/default`

    `root /vagrant;`

4. Actualizamos las configuraciones de NGINX: `sudo service nginx restart`

5. Accedemos a nuestra página web: `http://192.168.56.10/`
