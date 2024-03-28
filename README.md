# TP 0 - Device Drivers
## UNGS - Sistemas Operativos y Redes II

### Introducción
El siguiente trabajo consta de dos secciones. La primera corresponde a la carga de un modulo Hola Mundo, mientras que la segunda consiste en elaborar un kermel module para un char device.

### Módulo Hola Mundo
Se deberá compilar y cargar un módulo provisto en el kernel.
Para compilar se utiliza el comando `make`, luego el módulo se carga ejecutando `insmod ./miModulo.ko`.

### Módulo Char Device
Se deberá elaborar un kernel module para un char device.
El módulo se compila y se carga en el kernel repitiendo los pasos de la sección Hola Mundo.
Si se cuenta con los permisos necesarios se puede enviar un mensaje al Char Device ejecutando `echo "message" > /dev/chardev`.
Luego, el mensaje puede leerse utilizando `cat /dev/chardev`. En particular, para este trabajo se solicita que el mensaje sea devuelto con los caracteres al revés.
