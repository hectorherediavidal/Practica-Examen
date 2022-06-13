# Practica-Examen


# Ejercicio 1

## Usamos el comando docker pull ubuntu:18.04 para descargar una imagen de ubuntu
    docker pull ubuntu:18.04
![ejemplo1](https://github.com/hectorherediavidal/Practica-Examen/blob/main/img/1%20del%201.PNG "")
<br>
<br>

## Ahora usamos el comando docker run -it ubuntu:18.04 /bin/bash para iniciar el contenedor de Ubuntu que hemos descargado antes y acceder al root de Ubuntu
     docker run -it ubuntu:18.04 /bin/bash
![ejemplo1](https://github.com/hectorherediavidal/Practica-Examen/blob/main/img/2%20de%201.PNG "")
<br>
<br>



# Ejercicio 2

## Usamos el comando docker pull centos para descargar la imagen de centOS 
    docker pull centos
![ejemplo1](https://github.com/hectorherediavidal/Practica-Examen/blob/main/img/imagen_2022-06-13_094848042.png "") 
<br>
<br>

## A continuación usaremos el comando docker run centos ls / para entrar al contenedor de centos y realizar un ls
    comando docker run centos ls /
![ejemplo1](https://github.com/hectorherediavidal/Practica-Examen/blob/main/img/2%20de%202.PNG "") 


# Ejercicio 3

## Vamos a crear un contenedor de httpd con el comando docker run httpd para tener un servidor Web Apache
    docker run httpd
![ejemplo1](https://github.com/hectorherediavidal/Practica-Examen/blob/main/img/httpd.PNG "") 
<br>
<br>


# Ejercicio 4

## Ahora vamos a crear un contenedor para debian9 y mostraremos el contenido de la carpeta de este contenedor con el siguiente comando:
    docker run -it -w /etc debian:9 ls
![ejemplo1](https://github.com/hectorherediavidal/Practica-Examen/blob/main/img/debian.PNG "") 
<br>
<br>

## Con el comando docker ps veremos los contenedores en estado up:
    docker ps
![ejemplo1](https://github.com/hectorherediavidal/Practica-Examen/blob/main/img/ps.PNG "") 
<br>
<br>


## Con el comando docker ps -a veremos los contenedores en estado up y en estado exited:
    docker ps -a
![ejemplo1](https://github.com/hectorherediavidal/Practica-Examen/blob/main/img/ps%20-a.PNG "") 
<br>
<br>



# Apartado 2


