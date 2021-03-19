## git --amend -m " **Name of commit** "

Used to edit the name of a commit.

## git reset --soft HEAD~1

Serves to uncommit

## git reset --mixed HEAD~1

Remove the commit from the stage

## git reset --hard HEAD~1

Removes changes up to the selected commit

## git reflog

Modifications to everything are back

## git reset --hard "Hash Commit"

Return the commit

## git revert "Hash Commit"

Return the commit

## git cherry-pick "Hash Commit"

Used to copy the commit from one branch to another

### Note:

If changes are deleted from the remote

## git pull + git stash

Delete my local changes, to fetch changes from the remote

### Note:

To assure you 100 %

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

To restore the branch

## git rebase -i HEAD~" Number of commit "

To return to a certain commit, for example:
git rebase -i HEAD~4

This command will return 4 commits from HEAD

### Replace pick with reword and save the changes

(New name of commit)
