# Clase 02 - GIT

```sh
git init
```

## GIT LOG

### Muestra los commits

```sh
git log
```

**Nota:** 

## Cmuestra los commits en forma abreviada

```sh
git log --oneline
```
### Por Fecha

git log --since="2021-12-20"
git log --after="2021-12-20"
git log --before="2021-12-27"
git log --after="2021-12-28"  --before="2021-12-27"

### muestra la cantidad de commits elegidos.

```sh
git log -2 # cantidad de commits que va a mostrar el git log
```

indica hasta donde esta sincronizado con el origin remoto
git log --oneline --decorate --all --graph




agrega todos los archivos que esta en el directorio
git add .

