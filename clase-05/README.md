# CLASE 05

## REPASO MARKDOWN

# h1
## h2
### h3
#### h4
##### h5
###### h6

# Listas ordenadas

1. item
2. item
3. item

# Listas desordenadas
* item
* item
* item

# Poner código

    comando con tabulador

```sh
comando con backtick ```sh mensage ... ```
```

```php
$variable = "Hola"
```

```js
let variable = "Mundo"
```

### Línea de separación
---

### Negrita y cursiva

**Negrita** Escrito con doble * (asteristos) en cada lado.

*italica*  Escrito con un * (asterisco) de cada lado.

## Incluir imagenes en Marckdown
![imagen](img/photo-1536148935331-408321065b18.avif)
```sh
![imagen](image.jpg)
```
# Destacar

> Hola
```sh
> hola
```

# Ejemplo de GIT RESET

1. Agrego una parte de codigo
2. Agrego otra linea de codigo
3. agrego una linea más

## GTIHUB issues
Puedo crear y avisar al dueño del repositorio de problemas que puede llegar a tener su codigo

## GITHUB projets
Puedo crear un kanban y usar la metodologia scrum para ir colocando las tareas y resolviendolas.
# GIT REBASE

## ¿Para que sirve el rebase?

* Ordenar commits
* Corregir mensajes de los commits (siempre y cuando no esten subidos al remoto)
* Unir commits
* Separar commits 

## ¿Como utilizo? lo mismo que el merge
Tendo que estar en la rama a la cual quiero traerme los cambios. O sea si quiero traerme los cambios de <rama-rebase> a <master> tengo que estar parada en **master**

## Ejecutando rebase 

Estando en la rama r-rebase. Hago git rebase master y sigo las instrucciones. Que seria arreglar los conflictos, confirmar ( git add .; git commit -m "mensaje") y luego git rebase --continue 

    git rebase master

    git rebase --continue

    git rebase --abort 

## Rebase Interactivo

git rebase -i <la-cantidad-hash-que-quiero-intervenir>

si quiero traerme 4 commit tengo que poner los siguiente

git rebase HEAD~4