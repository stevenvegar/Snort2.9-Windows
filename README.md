# Snort2.9-Windows
Snort 2.9 para Windows

Instalar Snort normalmente\
Snort_2.9.17.1_Installer.x64.exe

Instalar el plugin Npcap\
npcap-1.30.exe

Versiones actualizadas de los instaladores:\
https://www.snort.org/downloads \
https://nmap.org/npcap/#download 

Luego de instalar, reemplazar todas las carpetas y archivos\
en C:\Snort\ 

Cambiar la dirección IP del host en el archivo C:\Snort\Snort.conf \
luego de la variable $HOME_NET


# Ejecutar Snort en Windows

- Abrir una ventana de CMD como Administrador\
- Navegar hasta la carpeta C:\Snort\bin\

1. Conocer la interfaz que está conectada a la red\
y que va a ser monitoreada\
snort.exe -W

2. Comprobar el estado de la instalacion:\
snort.exe -c C:\Snort\etc\snort.conf -T -i <index de la interfaz>
