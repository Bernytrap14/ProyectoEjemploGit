#Introduccion a Git

##Descripción:
Tenemos un programa en lenguaje Python, el cual imprime el mensaje "Hola Git".
Y tenemos otro archivo llamado .gitignore, que realiza la funcion de ignorar los archivo que nosotros
escribamos en el, en este caso los archivos .log, como debug.log

El objetivo es familiarizarnos con el entorno de **Git** y **Github**, aprendiendo a usar sus comandos
desde la terminal de git Bash y saber subir un **repositorio local a un repositorio remoto**.

##Instrucciones de uso:
Para usar el programa debemos situarnos desde la terminal, en la misma carpeta donde se encuentra ubicado
el repositorio y ejecutar el siguiente comando: * *python HolaMundo.py* *; o podemos ingresar a el desde una IDE
que nos facilite el ejecutar el programa.

##Comandos utilizados:
Los comando utilizados fueron:
git init
git add "* *Nombre del archivo* *"
git commit -m "* *Descripcion del commit* *"
git status
git push
git remote add origin "* *URL* *"

##Nota sobre el archivo .gitignore:

Este archivo es creado justo para los archivos que se encuentren en nuestro repositorio local y que queramos que
sean ignorados al momento de subirlos a nuestro repositorio remoto, sean ignorados; por eso dentro del archivo 
.gitignore se engcuentra .log, en nuestro repositorio remoto se ignorara todo archivo de tipo .log.

Al final nuestro programa de HolaMundo.py debera mostrar el mensaje "**Hoal git**", y para verificar que debug.log
no se subio, podemos revisar el repositorio en github, y revisar que en efecto ese archivo no existe en el repositorio
y que su nombre aparece dentro del archivo de .gitignore.
