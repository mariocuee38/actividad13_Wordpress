# Instalación de Wordpress en servidor LAMP

### Instalo primero otros componentes de PHP que se necesitan:
![wp1](img/w1.PNG)

## Base de datos:
### Creo la base de datos...
![wp2](img/w2.PNG)

### Creo un usuario y le otorgo todos los permisos
![wp3](img/w3.PNG)

## Apache
### Voy a editar la configuracion del sitio por defecto para que quede así:
De esta forma habilito que el directorio tome la informacion de fuera
![wp4](img/w4.PNG)

## Aquí activo el mod de Apache llamado rewrite para poder usar Permalink que es una funcion de Wordpress
![wp5](img/w5.PNG)

## Instalo Wordpress
### Mediante wget voy a descargar Wordpress
Descomprimo el paquete con unzip...
![wp6](img/w6.PNG)

### Ahora muevo el contenido de `wordpress/` a `/var/www/html`
![wp7](img/w7.PNG)

### Entro desde un navegador a la IP pública de la instancia EC2
![wp8](img/w8.PNG)

## Configuración de Wordpress:
![wp9](img/w9.PNG)

![wp10](img/w10.PNG)

### Login...
![wp11](img/w11.PNG)

## Resultado
![wp12](img/w12.PNG)
