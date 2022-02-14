# Kata 2 *"Creacion de un paquete"* 
##### Alfredo Espejel
---
## Paso 1: Creacion de la carpeta para el proyecto


Abrimos la terminal y con cd nos dirigimos a nuestro directorio preferido y creamos la carpeta que contendra nuestro modulo

![Dirigirse a nuestro directorio](https://github.com/AlfredoEspejel/CursoIntroPython/blob/main/Módulo%202%20-%20Crear%20y%20administrar%20proyectos/Kata%202%20imagenes/2.PNG)

___

## Paso 2: Creamos el entorno virtual desde terminal

En consola se ingresa 

    python -m venv env

![Instalacion del entorno](https://github.com/AlfredoEspejel/CursoIntroPython/blob/main/Módulo%202%20-%20Crear%20y%20administrar%20proyectos/Kata%202%20imagenes/3.PNG)


Despues de esto podremos ver que crea unos ficheros

![Revicion de los ficheros](https://github.com/AlfredoEspejel/CursoIntroPython/blob/main/Módulo%202%20-%20Crear%20y%20administrar%20proyectos/Kata%202%20imagenes/4.PNG)

___

## Paso 3: Activacion del entorno virtual

Accedemos a nuestro fichero _**env**_ y verificamos que carpetas existen.

![Revicion de los ficheros env](https://github.com/AlfredoEspejel/CursoIntroPython/blob/main/Módulo%202%20-%20Crear%20y%20administrar%20proyectos/Kata%202%20imagenes/5.PNG)

En este caso se encuentra la carpeta _**Scripts**_ pero puede ser _**bin**_

Si entramos a la carpeta vemos que existe el archivo activate, procedemos a ejecutar ese archivo. 
Despues de hacer eso nuestra terminal muestra _**(env)**_ en nuestra terminal.

![Inicio de Activacion](https://github.com/AlfredoEspejel/CursoIntroPython/blob/main/Módulo%202%20-%20Crear%20y%20administrar%20proyectos/Kata%202%20imagenes/6.PNG)

En este punto ya tenemos nuestro entorno virtual.

___

## Paso 4: Instalacion de paquetes

Antes de instalar un paquete que podremos verificar que no tenemos nada para ver la diferencia. 

Existe un comando para verificaar que tenesmos instalado:

    pip freeze

![Revicion de Librerias](https://github.com/AlfredoEspejel/CursoIntroPython/blob/main/Módulo%202%20-%20Crear%20y%20administrar%20proyectos/Kata%202%20imagenes/7.PNG)

En este caso no nos deveria devolver nada. A ahora para instalar usemos:

    install python-dateutil

![Instalacion de librerias](https://github.com/AlfredoEspejel/CursoIntroPython/blob/main/Módulo%202%20-%20Crear%20y%20administrar%20proyectos/Kata%202%20imagenes/8.PNG)

Despues de ejecutar el comando nos aparecera el mensaje de _**Susccessfullly installed python-dateutil-2.8.2 six-1.16.0**_ o algo similar.

Ahora para ver las diferencias ejecutamos otra vez:

    pip freeze

![Revicion de librerias](https://github.com/AlfredoEspejel/CursoIntroPython/blob/main/Módulo%202%20-%20Crear%20y%20administrar%20proyectos/Kata%202%20imagenes/9.PNG)

A diferencia de la vez anterior podermos ver un mensaje, el cual muestra las librerias que tengamos instaladas y su version.

___

## Paso 5: Salir del entorno virtual

Anora no siempre quisieramos estar en el entorno, asi que para salir de el usamos:

    deactivate

![Salir del entorno](https://github.com/AlfredoEspejel/CursoIntroPython/blob/main/Módulo%202%20-%20Crear%20y%20administrar%20proyectos/Kata%202%20imagenes/10.PNG)

Cuando salimos de nuestro entorno la leyenda _**(env)**_ en nuestra consola.

Con esto podemos concluir en como se hace un paquete aislado de python.