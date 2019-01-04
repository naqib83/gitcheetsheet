# gitcheetsheet

1. [Syntax to write in github files - 1](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
2. [Syntax to write in github files - 2](https://help.github.com/articles/basic-writing-and-formatting-syntax/)

###### To check or see changed-but-not-yet-committed files
`git diff --name-only`
[Useful link](https://stackoverflow.com/questions/5096268/how-to-get-a-list-of-all-files-that-changed-between-two-git-commits)

***

###### To add all changed files to commit
`git add -A`

***

###### To add a specific changed files to commit
`git add name-of-the-changed-file.java`

***

###### To commit all added files
`git commit -m "your message"`

***

###### To commit a specific file
`git commit name-of-the-changed-file.java -m "your message"`

***

###### To delete file from Pull Request on GitHub
[Check this link](https://stackoverflow.com/questions/9498201/delete-file-from-pull-request-on-github/37122300)

***

###### To create the branch on your local machine and switch in this branch
`git checkout -b name-of-the-new-branch`

***

###### To see the list of all local branch
`git branch`

***

###### To switch to a different branch
`git checkout name-of-branch`

***

###### To push a branch to github/BitBucket
`git push -u origin name-of-your-branch`

***

###### To delete a local branch
`git branch -d branch_name`
`git branch -D branch_name`

***

###### To delete a remote branch
`git push <remote_name> --delete <branch_name>`
###### Note that in most cases the remote name is `origin`

***


