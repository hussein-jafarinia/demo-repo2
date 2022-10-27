# Demo 2
# transforming a normal directory to a git repo

## Subheader

Watch tutorial on Youtube.

## Local Development

1. open index.html in your browser.

Some changes specific the feature 

some text specific to feature-readme-instructions branch

to transform it to a github repo: in vscode terminal -> git init
to add README.md to the repo: git add README.md
go and make an empty repo with the same name of this in github page and cpy the linj of it
connect this to that: in vscode terminal -> git remote add origin https://github.com/hussein-jafarinia/demo-repo2.git
see the list of connected repos: in vscode terminal -> git remote -v
push: in vscode terminal -> git push --set-upstream origin main (this is done only for the first time and after that git push is enough)

also: do as this link says to get rid of .ds_store -> https://stackoverflow.com/questions/107701/how-can-i-remove-ds-store-files-from-a-git-repository
also: do as this link says to add autocomplete for git commads: https://www.macinstruct.com/tutorials/how-to-enable-git-tab-autocomplete-on-your-mac/

to see the branches: in vscode terminal -> git branch
to make a branch: in vscode terminal -> git checkout -b name_of_the_branch
to go to a branch to another: in vscode terminal -> git checkout name_of_the_branch
to findout the difference between branches: in vscode terminal -> git diff [name_of_branch] [] is for optional
to add from new branch to github website: in vscode terminal -> git push --set-upstream origin name_of_branch
?to get the chnages on your system: in vscode terminal -> git pull
to delete a branch: in vscode terminal -> git branch -d name_of_branch
?to add and commit at the same time git commit -am "something"
?to merge branch from terminal: in vscode terminal -> git merge main