## Comandos Git

### Iniciar proyecto git

```shell
$ git init
```

### Verificar cambios dentro del proyecto git

```shell
$ git status
```
### Preparar archivos (staged)

```shell
$ git add -A
$ git add .
$ git add <filename>
$ git add *
```

### Guardar mis cambios en mi proyecto git 

```shell
$ git commit 
```
```shell
$ git commit -m “Mensaje Descriptivo de los cambios”
```

### Deshacer los cambios antes del commit 

```shell
$ git restore <filename>
```
```shell
$ git checkout <filename>
```

### Deshacer los cambios después del commit
```shell
$ git reset --soft HEAD~1 (mantengo los cambios)
```
```shell
$ git reset —hard HEAD~1 (elimino todos los cambios y vuelvo a mi estado original)
```

### Añadir cambios al commit anterior
```shell
$ git commit —amend -m “Nuestro respectivo mensaje”
```

### Añadir repositorio remoto

```shell
$ git remote add <repo-name> <repo-url>
```

### Mostrar el contenido de un repositorio (url)
```shell
$ git remote show <repo-name>
```
### Actualizar un repositorio remoto

```shell
$ git remote set-url <repo-name> <repo-url>
```
### Eliminar un repositorio remoto 
```shell
$ git remote rm <repo-name>
```

### Subir cambios al repositorio remoto

```shell
$ git push <repo-name> <branch-name>
```