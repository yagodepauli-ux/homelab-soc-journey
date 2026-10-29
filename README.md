# homelab-soc-journey
Comprobar con práctica real si el trabajo defensivo (montar un entorno, simular ataques y analizar logs) te engancha, y dejar 3-4 cosas públicas en GitHub. Al final de la semana 4 decides con criterios escritos de antemano.

SESION 1:
Qué hice:
he creado la vm de ubuntu server en una red nat creada por mi  con 50GB de disco 8192MB de RAM y 4 CPUS creado un usuario con contraseña, y hecho una snapshot de la vm llamada limpio-ubuntu

Dónde me atasqué :
El instalador del espacio que le di a la vm cogio solo la mitad, lo cual no entendí porque lo hizo entonces lo que hice fue ejecutar en mi vm inciando sesion el comando sudo lvextend -r -l +100%FREE /dev/ubuntu-vg/ubuntu-lv y comprobando que el cambio fuese efectivo con df -h

Siguiente tarea:
Arrancar la VM de Ubuntu, ejecutar el script de instalación all-in-one de Wazuh Manager y configurar el reenvío de puertos en VirtualBox para acceder al Dashboard desde el navegador del host.

Disfrute (1 al 5):
3.5


Horas reales: 1 h
