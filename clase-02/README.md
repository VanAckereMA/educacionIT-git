## clase 2
    
    https://github.com/abhisheknaiidu/awesome-github-profile-readme

## Agregar remoto en repositorio local

    git remote add origin <URL>

## Verificar que este configurado el remoto 

    git remote
    git remote -v

## Status de archivos

**UNTRACKED** => Archivos que no se agregaron al index (Staging Area) y por consecuencia no se les hará seguimientos

**STAGED** => Archivos que fueron agregados al area temporal o Staging Area

**UNMODIFIED** => Archivos que se encuentran en el repositorio y que no fueron modificados

**MODIFIED** => Archivos que se encuentran en el repositorio pero difieren con los que se encuetran actualmente en el directorio de trabajo (Working Directory)

# Git amend
Agregar algo que me olvide en el último commit

    git add . o <archivo>
    git commit --amend
