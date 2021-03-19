## git --amend -m " **Name of commit** "

Utilizado para editar el nombre de un commit.

## git reset --soft HEAD~1

Sirve para hacer uncommit

## git reset --mixed HEAD~1

Retirar el commit del stage

## git reset --hard HEAD~1

Remueve las alteraciones hasta el commit seleccionado

## git reflog

Las modificaciones de todo estaran de regreso

## git reset --hard "Hash Commit"

Devuelve el commit

## git revert "Hash Commit"

Devuelve al commit

## git cherry-pick "Hash Commit"

Usado para copiar el commit de una rama para otra

### Nota:

Se las alteraciones fueron eliminadas del control remoto

## git pull + git stash

Borrar mis modificaciones locales, para buscar las alteraciones al control remoto

### Nota:

Para asegurarte 100%

- git stash list
- git --help stash
- git stash pop
- git stash drop stash@{0}
- git stash list

# Si borras una rama desde el remoto

- git remote prune origin --dry-run
- git remote prune origin
- git branch -d "Name of branch"

## git --reflog

Para restaurar la rama

## git rebase -i HEAD~" Number of commit "

Para volver a un commit en especifico, por ejemplo:
git rebase -i HEAD~4

Este comando devolverá 4 commits a partir de HEAD

### Substituir "pick" por "reword" y guardar las alteraciones

(Nuevo nombre del Commit)
