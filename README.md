# 仓库介绍
Command for git

## 命令大全

# CREATE

$ git clone ssh://仓库地址

## Clone an existing repository

$ git init

## Create a new local repository

# LOCAL CHANCES

$ git status

## Charged files in your working directory

$ git diff

## Changes to tracked files

$ git add 

## Add all current changes to the next commit

$ git add -p <file>

## Add some Changes to the next commit 

$ git commit -a

## Commit all local changes in the tracked files 

$ git commit 

## Commit previously staged changes

$ git commit --amend

## Changes the last commit

# COMMT HISTORY

$ git log

## Show all commits, starting with newest

$ git log  -p <file>

## Show changes over time for a specific file

$  git blame <file>

## Who changed what and when in <file>

#BRANCHES & TAGS

$ git branch -av

## List all existing branches 

$ git checkout <branch>

## Switch HEAD branch

$ git branch <new-branch>

## Create a new branch based on your current HEAD

$ git checkout --track <remote/branch>

## Create a new tracking branch bsased on a remoter branch

$ git branch -d <branch>

## Delete a local branch 

$ git tag <tag-name>

## Mark the current commot with a tag

# UPDATE & PUBLISH

$ git remote -v

## List all current configured remotes

$ git remote show <remote>

## Show information about a remote

$ git remote add <shortname> <url>

## Add new remote repository,name <remote>

$ git fetch <remote>

## Download all changes from <remote> but don't integrate into HEAD

& git pull <remote> <branch>

## Download changes and  directly merge/integrate into HEAD

$ git push <remote> <branch>

## Publish local changes on a remote

$ git branch -dr <remote/branch>

## Delete a branch on the remote

$ git push --tags

## Publish your tags

# MARGE & REBASE

$ git merge <branch>

## Merge <branch> into your current HEAD

$ git rebase <branch>

## Rebase your current HEAD onto <branch>

$ git rebase --abort

## About a rebase

$ git rebase --continue

## Continue a rebase after resolving conflicts

$ git mergetool

## Use your configured merge tool to solve conflicts

$ git add <resolved-file>
$ git rm <resolved-file>

## Use your editor to manually aolve conflicts and (after resolved)marl file as resolved

# UNDO

$ git reset --hard HEAD

## Discard all local changes in your working directory

$ git chekout HEAD <file>

## Discard local changes in a specific file

$ git revert <commit>

## Revert a commit (by producing a new commit with contrary changes)

$ git reset --hard <commit>

## Reset your HEAD pointer to a previous commit abd Discard all changes since then

$ git reset <cimmit>

## ...and preserve all changes as unstaged changes

$ git reset --keep <commit>

## ...and preserve umconnitted local changes








