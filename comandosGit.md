# Prueba GIT- Comandos
Para inizializar el git en el directorio utilizamos:
    
    git init

Para agregar los cambios usamos:

    git add nombreRepositorio

Si agregamos -p sin el directorio al comando anterior se agrega y vemos 
los cambios

Para ver el status usamos:

    git status

Para realizar commit utilizamos:

    git commit -m "comentario"

No obstante el comando add se puede ejecutar en uno solo con el commit, evitando realizarlo por separado:

    git commit -am "comentario"

Para observar los commits realizados utilizamos:

    git log

Para clonar un proyecto usamos:

    git clone url

Para subir nuestros commits a el repositorio remoto usamos:

    git push origin master

Para actualizar los commits desde el repositorio remoto usamos:

    git pull origin master
Con el siguiente comando podemos convertir nuestro codigo en una version anterior:

    git checkout commitedentifier

Para crear una rama usamos:

    git branch name

para ver las ramas:

    git branch

para agregar los cambios de las ramas a la master:

    git merge nombreDeLaRama

Para cambiarnos de rama utilizamos:

    git checkout nombreDeLaRama

Para crear y movernos de rama al mismo tiempo utilizamos:

    git checkout -b nombreDeLaRama

 ## Conflictos

 Despues de un conflicto realizamos los siguientes pasos:
  1. Abrimos el archivo con un editor y lo editamos a nuestra conveniencia
  2. digitamos git add ficheroname
  3. Digitamos git commit -m "Comentario"

  ## Autores de archivos

  Para conocer quien a contribuido con el codigo usamos:

    git blame ficheroname

 ## Evitar Archivos

 Para evitar subir arcivos que no queremos a git creamos un archivo de la siguiente manera:

    touch .gitignore

Dentro de este archivo escribimos los nombres de los archivos que queremos ignorar junto con su extencion.

 ## Contenedores o cajones

 Para cambiarnos de rama sin hacer commit utilizamos:

    git stash

para ver la lista de cajones usamos:

    git stash list

Para activarlo nuevamente el ultimo en la pila usamos:

    git stash pop




