#	GIT & GITHUB

### Unstage a file accidentally added before a commit
 git rm --cached <filename>

### Uncommit a commit before push
	git revert HEAD --no-edit
### Change A Commit Message
 git commit --amend

### Undo A Commit
	1.  git reset --soft HEAD^
	2. git checkout develop
	
### Undoing a commit to github
	1. git revert <hash>
	2. git push origin +<branch name>
	 			OR
	3. git push <repo name> +<badcommithash>^ : <branch>