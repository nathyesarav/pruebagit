# Explicacion de git

La primera vez que usamos git en una maquina debemos configurar el user y el email y comprobarlo:
````shell
git config --global user.email email@email.com
git config --global user.name nombredeusuario
````
Para comprobar configuracion
```` shell
git config --list
````
Para iniciar en repositorio en local (solo la primera vez)
````shell
git init
````
Para hacer que git controle nuestros archivos
````shell
git add readme.md
````
Para saber el status de git:
````shell
git status
````
Para confirma el commit:
````shell
git commit -m 'nombrecommit'
````
Para què sirve git log
````shell
git log
git log --graph
````

````shell
git checkout
````
Crear una rama de desarrollo:
````shell
git branch nombrebranch
````
Cambiar a la rama
````shell
git checkout develop
````
Listar las ramas
````shell
git branch
````