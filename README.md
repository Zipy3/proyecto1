# Este es el primer proyecto del curso

## Creación de repo:
git init 
# se genera un proyecto git en el punto en el que estáse genera un proyecto git en el punto en el que está

## Añadir un fichero
git add<nombre_fichero>     # Añade un fichero
git add *                   # Añadir todos los ficheros del directorio. NO AÑADE OCULTOS
git add .                   # Añadir todos los ficheros del directorio. SI AÑADE OCULTOS

## Qué guarda GIT?
Git solo guarda ficheros.  NO GUARDA DIRECTORIOS

# Objetos en git:
    ## WORKSPACE:
    LA CARPETA EN LA QUE TENGO MI PROYECTO.
    ## STAGING
    Es un fichero que se guarda dentro de la carpeta .git que va anotando los cmbios que se van amndar al repo desde el área de staging
    ## REPO
    La carpeta .git

## Información del estado del proyecto
git status

## Que es un commit?
>>> Un paquete de cambios que se registra en el repo.<<<

## Sacar un fichero del área de STAGING
git rm --cached <Nombre_fichero>

## Borra el fichero de dónde?
 - Del workspace
 - En el staging se le dice que en el próximo paquete de cambios, se elimine el fichero.
 - 
 
## como trabaja git?
 - Los commits (paquetes de cambio) se aplican de forma incremental.
 - Cuando hacemos un cambio dentro de un fichero se guardan los ficheros, se guardan los cambios que ha sufrido ese fichero. Cuando hay un nuevo commit, se añaden al ficheor que contiene las modificacioens de un fichero, lo que ha sufrido.
 - 

## Mandar los cambios que hay apuntados en el AREA DE STAGING al repo
git commit -m 'mensaje'

