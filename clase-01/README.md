# Comandos de consola

## Crear directorios

    mkdir directorio1 directorio2 directorio3

##  Crear archivos vacios

    touch archivo1 archivo2

## Limpio consola

    clear

## Listar directorios
 
    ls 

## Cambio de directorio (con tabulador me va ir suguiriendo)

    cd <directorio>

## Salir de un directorio

    cd ..

## Inicializar un proyecto de git (crea un proyecto en git)
Entoces, es un repositorio de git por proyecto. Una carpeta o repositorio

    gir init

## Comand ejemplo
     
     mkdir ccs js img; touch index.html css/estilo.css js/main.js

## configurar GIT

    La configuracion global queda siempre configurada para todos los proyectos
    git config --global user.user "NombreDeUsuario"
    git config --global user.email "correoElectronicoVinculadoAGitHub@dominio.com"

    Si creas una repo de git y queres configurar de manera local para esa repo.
    git config --local user.user "NombreDeUsuario"
    git config --local user.email "correoElectronicoVinculadoAGitHub@dominio.com"

## Ver usuario configurado en la repo

    git config --global -l // a veces traba la consola y salis con "q" (tambien brinda mucha informacion)
    git config --global --get-regexp user  // solo brinda los datos de usuario
## Veo el estado de los archivos

    git status

## GIT: no versiona carpetas

    En el caso de querer versionarla tengo que colorcar un archivo. y estandar por la comunidad .gitkeep
    En caso de tener muchas carpetas, una por carpeta.

## Estados de GIT 

## working directory

    Es el area de trabajo. El area sucia donde creo mi codigo.. borrador.

## Staging Area

    Preserva y le dice a git que lo prepare para sacarle una foto.

## Ver la diferencia que tengo en el WD y en el local repo

    git diff carpeta/archivo

## Para ignorar un archivo en particular 

    Creo el archivo .gitingnore Puede estare en la raiz o no.