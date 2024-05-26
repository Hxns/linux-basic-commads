# Comandos Básicos de Linux

Este repositorio contiene una lista de comandos básicos de Linux y sus descripciones. Estos comandos son esenciales para administrar y obtener información sobre el sistema.

## Comandos y Descripciones

| Comando    | Descripción                                                                                       |
|------------|---------------------------------------------------------------------------------------------------|
| `whoami`   | Muestra el nombre de usuario actual.                                                              |
| `id`       | Devuelve la identidad del usuario.                                                                |
| `hostname` | Establece o imprime el nombre del sistema host actual.                                            |
| `uname`    | Imprime información básica sobre el nombre del sistema operativo y el hardware del sistema.       |
| `pwd`      | Devuelve el nombre del directorio de trabajo actual.                                              |
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

## Cómo Usar

Puedes ejecutar estos comandos en la terminal de Linux para obtener información sobre tu sistema o para realizar tareas de administración. A continuación se muestran algunos ejemplos de uso:

```sh
# Mostrar el nombre de usuario actual
whoami

# Devolver la identidad del usuario
id

# Establecer o imprimir el nombre del sistema host actual
hostname

# Imprimir información básica del sistema
uname -a

# Mostrar el directorio de trabajo actual
pwd

# Ver la configuración de las interfaces de red
ifconfig

# Mostrar la tabla de enrutamiento y otros detalles de red
ip route show

# Mostrar el estado de la red
netstat -tuln

# Investigar sockets
ss -s

# Mostrar el estado de los procesos
ps aux

# Mostrar quién está conectado
who

# Imprimir las variables de entorno
env

# Listar los dispositivos de bloques
lsblk

# Listar los dispositivos USB
lsusb

# Listar los archivos abiertos
lsof

# Listar los dispositivos PCI
lspci