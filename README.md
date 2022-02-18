# Comandos Terminal

## Link simbólico

```
$ ln -s /path/subPath/... <name_link>
```

## Mostrar variables de entorno

```
$ printenv
```

## Alias

```
$ alias gitlog='git log --oneline --decorate --graph --all'
```

## Ver el tipo de comando

```
$ type cd
```

## Buscar binarios en la ruta del `PATH`

```
$ which java
```

## Buscar archivos y directorios

Se usa el comando `find`. Se especifica la ruta, el tipo de archivo a buscar (archivo o directorio) y el nombre del directorio/archivo a buscar.

Buscar todos los archivos con extensión `.js` de la ruta `./Documents/Proyect`.

```
$ find ./Documents/Proyect -type f -name *.js
```

Buscar el directorio `node_modules` de la ruta `./Documents/Proyect`.

```
$ find ./Documents/Proyect -type d -name node_modules
```