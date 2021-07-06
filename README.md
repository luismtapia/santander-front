# santander-front
## Iniciar proyecto de git
git init

## Preparar archivos que se convertirán en commit
git add .
#### El punto es para agregar todos los archivos modificados

## Crear commit con su mensaje
git commit -m "Aqui va el mensaje"

## Agregar remoto "Solo la primera vez"
git remote add origin https://github.com/andres2093/santander-front.git

## Enviar commits al servidor de GitHub
git push -u origin master

## Para ver las ramas
git branch

## Ver todas las ramas
git branch -a

## Ver ramas remotas
git branch -r

## Cambiar a una rama
git switch nombre_rama

## regresa a la rama anterior(master)
git switch -

## Crea una rama y se mueve a esta
git checkout -b nombre_rama

## Borra la rama (-delete) (-D forza la eliminacion)
git checkout -d nombre_rama

## Renombre una rama (-move)
git branch -m old_name new_name

## Comparar ramas (opcional: --color-words)
git diff primera_rama segunda_rama

## Ver las ramas completamente combinadas
git branch --merged

## Ayuda branch
git help branch

## Almacenar temporalmente los cambios locales
git stash save "mensaje opcional para ti"
...
git stats list

## Aplica los cambios y deja una copia en el stats
git stats apply nombre_stats

## Aplica los cambios y elimina los archivos del stats
git stats pop nombre_stats

## Elimina los cambios sin aplicarlos
´git stats drop nombre´

## Limpia todo el stats
´git stats clear´

## Fusionar ramas (commit realizados si no no deja)
git merge nombre_rama

## mover la rama a otro punto del branch
git rebase

npm
npm init
npm i sass
## Este comando sirve para el watch de sass en windows
node .\node_modules\sass\sass.js --watch .\scss\main.scss output.cs

*crear gitinore*