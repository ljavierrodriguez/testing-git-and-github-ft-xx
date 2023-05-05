Comandos Git

Iniciar proyecto git

$ git init

Verificar cambios dentro del proyecto git

$ git status

Preparar archivos (staged)

$ git add -A
$ git add .
$ git add <filename>
$ git add *

Guardar mis cambios en mi proyecto git 

$ git commit 

$ git commit -m “Mensaje Descriptivo de los cambios”

Deshacer los cambios antes del commit 

$ git restore <filename>
$ git checkout <filename>

Deshacer los cambios después del commit

$ git reset --soft HEAD~1 (mantengo los cambios)
$ git reset —hard HEAD~1 (elimino todos los cambios y vuelvo a mi estado original)


Añadir cambios al commit anterior

$ git commit —amend -m “Nuestro respectivo mensaje”

Añadir repositorio remoto

$ git remote add <repo-name> <repo-url>

Mostrar el contenido de un repositorio (url)

$ git remote show <repo-name>

Actualizar un repositorio remoto

$ git remote set-url <repo-name> <repo-url>

Eliminar un repositorio remoto 

$ git remote rm <repo-name>

Subir cambios al repositorio remoto

$ git push <repo-name> <branch-name>
