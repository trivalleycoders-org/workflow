# tvc-git
## Purpose?
Team members should use this project to learn how to work with the repository.
## Introduction
Everyone in the group is making changes to the code and there needs to be an organized way to get it all into one code base.
Try these steps. Not all of them are required every time. Repeat this process until you are comfortable with it.
There are a couple of well-known workflows
- **Fork & pull model**: is best for open source projects
- **Shared repository model**: works well for small private groups
Our group is small and we are all owners of the repository so the _shared_ model should work well for us.

## Process
** _this process is Draft_ **
### Initial Setup
1. $ git clone  https://github.com/trivalleycoders-org/tvc-git.git
2. $ cd tvc-git
3. $ git remote -v
4. $ git remote rename origin klequis-tvc
5. $ git remote -v
6. $ git branch -av
7. $ git branch klequis-tvc
8. $ git checkout klequis-tvc
9. $ git branch klequis-tvc
10. Make some changes
11. $ git status
12. $ git add --all
13. $ git status
14. $ git commit -m 'make a comment'
15. $ git push klequis-tvc klequis-tvc


### Make more changes
1. Go to the GitHub page. Your new branch will be shown at the top of the repository.
2. Click 'compare & pull request
3. Review changes
4. Fill in fields and 'Create pull request'
5. Make edits
7. Add, commit & push
8. Go to the GitHub page. Your changes will already be there.

## Let's Merge
1. Got to the pull page
2. Review change
3. Commit change
4. Look in master. You will see the merged changes

## Hum ... Megre again?
1. Pull the branch if necessary
2. Checkout master
3. $ git merge klequis-tvc
