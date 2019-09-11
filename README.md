# POC-Docker

*Prueba de concepto de Docker*

Pre-Requisitos: Poseer una cuenta en https://hub.docker.com/ y tener instalado Docker

*Como iniciar?*

- Con un cliente cmd situarse en la carpeta flask-app
- Ejecutar el comando reemplazando "mi usuario" por el nombre de usuario propio

    $ docker build -t miusuario/miapp . 

- Una vez descargadas las dependencias e instalado la app mostrará el siguiente mensaje:
  
    *Successfully tagged miusuario/miapp:latest*
    
- Luego ejecutar el siguiente comando:

    $ docker run -p 8888:5000 --name miapp miusuario/miapp
    
- Se verá por pantalla el siguiente mensaje:

    *Running on http://0.0.0.0:5000
    
- Por ultimo, abrir el navegador y dirigirse a la siguiente dirección asignada:

    http://192.168.99.100:5000
    


