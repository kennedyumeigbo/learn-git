# learn-git

## Explain version control:
This is the practice of tracking and managing changes to software code, or a system that records changes to a file or set of files over time so that you can recall specific versions later.

## Explain difference between git and GitHub:
GitHub is based upon Git. In other words, Git is independent of GitHub, but Git Hub cannot function without Git.
GitHub is a web-based Git repository hosting service, which offers all of the distributed revision control and source code management (SCM) functionality of Git as well as adding its own features; while, Git is a distributed version control system for tracking changes in source code during software development.

## List 3 other GitHub alternatives:
GitLab, Bitbucket, and Gitea.

## Explain the difference between git fetch and git pull:
Git fetch and pull is that git pull copies changes from a remote repository directly into your working directory, while git fetch does not. The git fetch command only copies changes into your local Git repo. The git pull command does both. In simple terms, git pull does a git fetch first, and then a git merge.

## Explain in simple terms git rebase and the command for it:
Rebasing is the process of moving or combining a sequence of commits to a new base commit. Git rebase is the linear process of merging. A Git rebase changes the base of the developer’s branch from one commit to another, so it looks like they have created their branch from a different commit. The primary reason for rebasing is to maintain a linear project history.

## Explain in simple terms git cherry-pick and the command for it:
In Git, cherry-picking is taking a single commit from one branch and adding it as the latest commit on another branch.
Git cherry-pick is a powerful command that enables arbitrary Git commits to be picked by reference and appended to the current working HEAD. Cherry picking is the act of picking a commit from a branch and applying it to another. Git cherry-pick can be useful for undoing changes.
Git cherry-pick is a useful tool but not always a best practice. Cherry picking can cause duplicate commits and many scenarios where cherry picking would work, traditional merges are preferred instead.