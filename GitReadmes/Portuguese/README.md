## git --amend -m " **Name of commit** "

Utilizado para editar o nome de um commit.

## git reset --soft HEAD~1

Serve para uncommit

## git reset --mixed HEAD~1

Retirar o commit do stage

## git reset --hard HEAD~1

Remove as alterações até ao commit seleccionado

## git reflog

As modificações de tudo estão de volta

## git reset --hard "Hash Commit"

Devolve o commit

## git revert "Hash Commit"

Devolve ao commit

## git cherry-pick "Hash Commit"

Usado para copiar o commit de um ramo para outro

### Nota:

Se as alterações forem eliminadas do controlo remoto

## git pull + git stash

Apagar as minhas alterações locais, para ir buscar as alterações ao controlo remoto

### Nota:

para lhe assegurar 100%

- git stash list
- git --help stash
- git stash pop
- git stash drop stash@{0}
- git stash list

# If you Delete a branch from the remote

- git remote prune origin --dry-run
- git remote prune origin
- git branch -d "Name of branch"

## git --reflog

Para restaurar o ramo

## git rebase -i HEAD~" Number of commit "

Para voltar a um certo commit, por exemplo:
git rebase -i HEAD~4

Este comando devolverá 4 commits a partir de HEAD

### Substituir "pick" por "reword" e guardar as alterações

(Novo nome do Commit)
