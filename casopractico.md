# Caso Práctico

## Instalación y gestión de un paquete RPM

* Actualizar el sistema:

sudo dnf update -y

* Instalar un paquete (ejemplo: htop):

sudo dnf install htop -y

* Verificar la instalación:

rpm -q htop

* Eliminar un paquete:

sudo dnf remove htop -y

* Instalar un RPM manualmente:

sudo rpm -ivh paquete.rpm

* Eliminar un paquete instalado manualmente:

sudo rpm -e paquete
