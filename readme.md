# Instrucciones de git

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