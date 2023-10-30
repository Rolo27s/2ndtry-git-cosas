# 2ndtry-git-cosas
2ndtry-git-cosas

## Comandos aprendidos
* git checkout -b nombre-rama-nueva (#hash) - Estoy haciendo una nueva rama con el contenido de la version del hash
* git revert #hash - Estoy volviendo al commit anterior al hash indicado
* git reset --hard - Estoy volviendo al ultimo commit hecho
* git fetch --all - Trae todas las ramas de remoto a local
* git merge "#nombre de la rama que quiero fusionar" <-> con la rama en la que estoy
* git checkout "nombre-de-la-rama" - Me cambio a la rama "nombre-de-la-rama"
* git checkout "#hash de commit" - Me voy a VER SOLO el commit (research... porque estoy en detached/head)
* git branch - Muestra las ramas

## Comandos aprendidos en Microsoft
* rm index.html               --- Remuevo el archivo index.html
* git rm index.html           --- Remuevo el archivo index.html desde el historial de git
* git reset HEAD index.html   --- Vuelvo al historial donde tenía el index.html
* git checkout -- index.html  --- Recupero el archivo index.html
* git revert --no-edit HEAD   --- Revierto entre el último commit y el estado actual del proyecto (funciona tipo toggle)
