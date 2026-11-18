# Parcial 2 - Ingenieria de Software

*Alumno*: Grisel Mauri
*Fecha:* 18/11/2026

## Instrucciones de docker
Para correr la aplicación aislada dentro de un contenedor Docker: 

1- Abre la terminal

2- Clona el repositorio: Descargas el proyecto desde GitHub a tu PC usando el enlace público con el comando: git clone https://github.com/grisel-mauri/parcial2-v2-software.git

3- Ubicate en la carpeta raiz del proyecto con el comando: cd parcial2-v2-software

4- Ejecuta el siguiente comando para que Docker empaquete tu aplicación: docker build -t parcial2-v2-software .

5- Ejecuta el contenedor docker run -d -p 8080:80 parcial2-v2-software

6- Para verificar el resultado abre tu navegador e ingresa a: http://localhost:8080