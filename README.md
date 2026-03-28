# Comandos Básicos de Linux

Lista de comandos básicos de Linux y sus descripciones. Estos comandos son esenciales para administrar y obtener información sobre el sistema.

## Gestión de Archivos y Directorios

Estos comandos son fundamentales para crear, navegar y manipular archivos y carpetas en el sistema.

| Comando   | Descripción                                                                                       |
|-----------|---------------------------------------------------------------------------------------------------|
| `pwd`     | Devuelve el nombre del directorio de trabajo actual.                                              |
| `ls`      | Lista los archivos y directorios en la ubicación actual (ej. `ls -l` para ver más detalles).      |
| `cd`      | Cambia el directorio actual (ej. `cd /ruta/al/directorio` o `cd ..` para retroceder).             |
| `mkdir`   | Crea un nuevo directorio o carpeta (ej. `mkdir nueva_carpeta`).                                   |
| `rmdir`   | Elimina un directorio **vacío**.                                                                  |
| `rm`      | Elimina archivos. Para eliminar carpetas con todo su contenido usa `rm -r` o `rm -rf`.            |
| `cp`      | Copia archivos o directorios (ej. `cp archivo.txt copia.txt`, usa `cp -r` para carpetas).         |
| `mv`      | Mueve o renombra archivos y directorios (ej. `mv viejo.txt nuevo.txt`).                           |
| `touch`   | Crea un archivo vacío o actualiza su fecha (ej. `touch archivo.txt`).                             |
| `cat`     | Muestra el contenido de un archivo en la terminal.                                                |
| `nano`    | Editor de texto en la terminal, ideal para editar archivos (ej. `nano archivo.txt`).              |

## Información del Sistema, Red y Procesos

Estos comandos son esenciales para obtener información detallada del estado del sistema o de la red.

| Comando    | Descripción                                                                                       |
|------------|---------------------------------------------------------------------------------------------------|
| `whoami`   | Muestra el nombre de usuario actual.                                                              |
| `id`       | Devuelve la identidad del usuario.                                                                |
| `hostname` | Establece o imprime el nombre del sistema host actual.                                            |
| `uname`    | Imprime información básica sobre el nombre del sistema operativo y el hardware del sistema.       |
| `ifconfig` | Utilidad para asignar o ver una dirección a una interfaz de red y/o configurar parámetros de la interfaz de red. |
| `ip`       | Utilidad para mostrar o manipular enrutamiento, dispositivos de red, interfaces y túneles.        |
| `netstat`  | Muestra el estado de la red.                                                                      |
| `ss`       | Otra utilidad para investigar sockets.                                                            |
| `ps`       | Muestra el estado de los procesos.                                                                |
| `who`      | Muestra quién está conectado.                                                                     |
| `env`      | Imprime las variables de entorno o establece y ejecuta un comando.                                |
| `lsblk`    | Lista los dispositivos de bloques.                                                                |
| `lsusb`    | Lista los dispositivos USB.                                                                       |
| `lsof`     | Lista los archivos abiertos.                                                                      |
| `lspci`    | Lista los dispositivos PCI.                                                                       |
