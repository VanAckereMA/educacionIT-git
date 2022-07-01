## clase 04

## 2 tipos de apuntadores

ESTATICOS -> Ramas locales como remotas.
Dinamicas -> HEAD

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