# VALHEIM SERVER

## Prerequisitos

En el equipo o máquina virtual donde vamos a instalar el servidor wordpress:

1. Instalar docker: https://docs.docker.com/engine/install/ y https://docs.docker.com/engine/install/linux-postinstall/

2. Instalar docker-compose: https://docs.docker.com/compose/install/

Asegurate de:

3. El usuario debe disponer de permisos de sudo.

4. Crear grupo docker y añadir al usuario al grupo usermod -a -G docker $USER. Hacer logout y login.

## Instrucciones para la creación del servidor

5. Instalar git. No es necesario, pero facilitar descargar los ficheros del repositorio.

6. Clonar el directorio con: git clone https://github.com/rafasb/valheim-server

Conviene crear una estructura de carpetas para tener acceso a los ficheros con tu usuario. Esto se genera con el clonado del repositorio.
* Dir: config
* Dir: config/worlds
* Dir: config/backups

## Instrucciones para conectar por Internet

https://github.com/lloesche/valheim-server-docker#steam-server-favorites--lan-play
