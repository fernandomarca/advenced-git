git config --global --edit
git config --edit

git remote -v
git remote add origin https://github.com/fernandomarca/advenced-git.git

git status
git status -s

git add .
git add --all
git commit --amend --no-edit

git stash
git stash list
git stash apply
git stash pop
git stash clear

git log
git --oneline
git log --pretty=format:'%C(white)%h %C(red)%d %C(yellow)%s - %C(cyan)%cn, %C(green)%cr'

git tag 1.0 -m "release 1.0"
git tag -a v1.2 9fceb02
git tag -a "0.1.beta" -m "release 0.1.beta" hash
git tag -d "0.2.beta"
git push --delete origin "0.2.beta"
git tag -l "v1.8.5\*"
git show 0.1.beta
