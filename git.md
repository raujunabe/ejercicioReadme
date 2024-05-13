# ORDENES BASICAS DE GIT

### INICIAR GIT

```
git init
```

Debemos utilizarlo dentro del directorio que va a contener el repositorio de git.

### AÑADIR FICHERO

```
git add "fichero"
```

Añadimos los ficheros que hemos modificiado o añadido.

### REGISTRAR LOS CAMBIOS

```
git commit -m "titulo"
```

Registramos los cambios que hemos añadido mediante git add y le ponemos un titulo para identificarlos.

### COMPROBAR EL ESTADO

```
git status
```

Comprobamos los ficheros que se actualizaran al registrar los cambios y los cambios que se han realizado en estos.

### CREAR UNA RAMA DIFERENTE

```
git branch "nombre"
```
### CAMBIAR LA RAMA EN LA QUE NOS SITUAMOS

```
git checkout "nombre"
```

### SUBIR LOS CAMBIOS A GIT

```
git push -u origin "rama"
```

Nos pedira el usuario y la contraseña (TOKEN).

### RECOGER LOS CAMBIOS DE GIT

```
git fetch origin "rama"
```

### CLONAR EL REPOSITORIO DE GIT EN NUESTRO EQUIPO LOCAL

```
git clone "url del repositorio"
```
