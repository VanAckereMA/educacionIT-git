## clase 04

## 2 tipos de apuntadores

* ESTATICOS -> Ramas locales como remotas.
* DINAMICOS -> HEAD

## TAGs

Nos sirven para marcar algun commit que tenga cierta importancia. Tambien me sirve para marcar versiones o releases.

### Crear TAG

    git tag v1.1

### Borrar TAG

    git tag -d v1.1

### Para mostrar TAGs

    git tag

### Para version larga mostrar TAGs

    git tag -n

### Versionado semantico

    git tag -a v1.0.0 -m "Version 1.0.0 - Aplicacion funcionando"

    git tag -a v0.1.0 <HASH> -m "Version beta de nuestra aplicacion"

### Para subir un TAG en particular

    git push origin <tag-name>

## git add y commit en un comando
**IMPORTANTE**: Los archivos a commitiar tiene que estar en seguimiento, sino no se agregara al commit.

    git commit -am "Mensaje"

# GIT STASH 

### Creo un stash

    git stash

### Muestro la cajita de stashes

    git stash list

### Aplicar el ultimo stash

    git stash pop
    
### Aplicar un stash en particular 

    git stash apply stash@{n}

### Borar un stash 

    git stash drop stash@{n}

## Para crear una rama a partir de un stash

    git stash branch <nombre-rama>

# Trabajar con fork

1. Fork
2. Clone
3. Configuro el remoto del repositorio original
```sh
    git remote add upstream <url-remoto>
```
4. Actualizar si fuera necesario mi fork con el repositorio original
```sh
    git pull upstream <rama>
```
5. Tengo el local y para actualizar mi fork remoto.
```sh
    git push origin main
```