Hola me llamo hugo

estoy practicando con git

comando ha aprender:

CONFIGURAR DATOS EN GIT
=======================

- git config --global user.name "Tu nombre y apellido"
- git config --global user.email "tu@correo.com"

Empezando a usar Git
=====================

- git init
- git status
- git add "adasdad", de work directory al staying area
- git commit -m "nombredelcommit" del staying area a GIT
- git log, para revisar lo que se hecho
- Estoy modificando el archivo

- gitt add . agrega los archivos que se han modificado
- git diff muestra los cambios
- git checkout deshacer el cambio

GENERAR LA CLAVE SSH DE MANERA LOCAL:
=====================================

- cd ~/
- ssh-keygen -t rsa -C "hugoatuncar@hotmail.com"
- cat ~/.ssh/id_rsa.pub //ver la clave por terminal

CONFIGURACIÓN DE GITHUB
=======================

- Creación de la cuenta
- Configurar la clave SSH en GITHUB
- Copiar la clave SSH que se muestra en los diferentes sistemas operativos y pegarlo.

---------------------

1.  
2. git remote origin master : de manera remota se va al origen
3. git push -u origin : para subir lo que se ha modificado //git push origin master
4. git pull origin master //los cambios desde el repo origen


//Creando ramas//

checkout: permite crear ramas y moverte a través de ellas

1. git checkout -b mi-branch //crear una rama
2. git branch
3. git checkout master // git checkout mi-branch --permite cambiar de ramas
4. git push origin mi-branch //cambia el nombre por mi-branch donde se esta trabajando


