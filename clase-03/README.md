# Clase 03

## Repaso ramas

### Crear una rama
    
    git branch <nombre-rama>

### Listar rama

    git branch

### Cambiar ramas

    git switch <nombre-rama>

## MERGE (una fusión de ramas)

**IMPORTANTE**: Tengo que estar en la rama que quiero traerme los cambios. Ej: Si quiero traerme los cambios a **Master** lo que vengo haciendo en **Development**, tengo que estar en **Master**.

    git merge <ramaQueMeQuieroTraer>

### TIPOS DE MERGE

* fast-forward: Fusión automatica de las ramas. 
* Recursiva: Union de ramas (No hay colisiones).
* Manual: Conflictos - Colisiones - vamos a tener que elegir nosotros con que cambios nos quedamos.

## Detener el Merge
    
    git merge --abort