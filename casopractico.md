# Caso Práctico

## Instalación y gestión de un paquete RPM

* Actualizar el sistema:

sudo dnf update -y

* Instalar un paquete (ejemplo: nano):

sudo dnf install nano -y

* Verificar la instalación:

rpm  nano -q

* Eliminar un paquete:

sudo dnf remove nano -y

* Instalar un RPM manualmente:

sudo rpm -ivh paquete.rpm

* Eliminar un paquete instalado manualmente:

sudo rpm -e paquete
