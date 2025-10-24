# Instrucciones de git
git config --global init.defaultBranch nombre <- cambiar el nombre del rama en general>
git config --global -e <-- ir al fichero de configuración, puedes comprobar los cambios
## Instrucciones esenciales

### Iniciar repositorio
git init <- iniciar el repositorio

### Añadir ficheros a la fase Added
git add readme.md <- añadir fichero especifico
git add .git add . <- añadir todos los documentos solo con el '.'
git add --all <- añadir todos los documentos de otra manera
git add *.html <- añadir todos los ficheros con la instruccion despues del '*'
git rm --cached readme.md -f <- Forzar a que regrese al punto anterior sin añadir
### Fichero para ignorar lo que no nos interesa
.gitignore

### subir a la fase 'commit' = validación
git commit -m 'mensaje explicativo'
git commit <- abre un documento donde puedes poner el mensaje en manual

### Si modificamos un fichero va acabar en la fase modified
git restore nombre_fichero <- revierte los cambios antes del commit (como un CTRL +Z)
git add . <- volvemos a añadir a la fase add
git commit -m 'otro mensaje' < para volver a la fase commit
git commit -a 'menaje' <- cambia de golpe a la fase commit de nuevo

## Instrucciones de control
git status <- ver el esatus de los ficheros (saber su fase)
git log <- historial de commit extendido
git log --oneline <- historial de commit resumido
git diff <- mustra la diferenciacion en tus cambios, se cierra con 'q'

## Instrucciones para subir ficheros al repositorio
git remote add origin https://github.com/DelAngel8/instrucciones-git-github.git <- dirección donde se subira el fichero

## Instrucciones para ramas
git branch <- obtiene las ramas del proyecto
git branch -M main <- cambiar nombre de rama actual ejemplo 'main'

