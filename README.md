# ApuntesHLC

Bienvenido a HLC, vamos a hacer algunos comandos Ubuntu de recordatorio.

Actualización de repositorios de ubuntu:
- sudo apt update
- sudo apt upgrade
- sudo apt policy (comprueba los repositorios)

Cambio de Constraseña:
- sudo passwd

Cambio de nombre de PC:
- nano /etc/hostname (Cambiará tras el siguiente reinicio)

Ver los repositorios y versión y otras coasas:
- sudo cat /etc/apt/sources.list.d/ubuntu.sources
- lsb_release -a
- sudo dpkg -l (paquetes instalados)
- uname -a (Kernel)
- gnome-shell --version (Versión de Entorno de Escritorio)
- free -h (Espacio disponible en lenguaje humano, Memoria RAM)
- lscpu (Información de la CPU)

- mount (Discos montados)
- lsblk

Comandos de redes:
- ip a
- ip r (muestra puerta de enlace)
- ping (Con -c hace el número de veces pedida)
- netstat -plunt (Muestra los puertos en cierto protocolo y en escucha)
