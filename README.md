# Rootstrap-GIT
**Junior level:**
- Git Init: This command creates an empty Git repository or reinitialize an existing one.
- Git Clone: Clones an entire repository from a hosted location to a new directory.
- git add .: the git add command adds a change in the working directory to the staging area. The "." is a way to add ALL of the files in the current directory instead of going one by one.
- git commit: It records the staged changes just added with the git add . command, to the repository. A log message is possible with "-m"
- git revert: This command it's used to reverse the effect of some earlier unpushed commits (usually one at a time). git revert <commit> will create a new commit with the reverted changes.

**Branches:** 
- git branch: Creates, lists or deletes branches
- git checkout: Switch between branches. It is often used with '-b' which also creates and moves into a new branch
- git merge <branch>: Joins the specified branch into the current branch.
- Conflicts generally arise when two people have changed the same lines in a file. The most direct way to resolve a merge conflict is to edit the conflicted file. Commands like git status or git diff will help identify conflicting files. When resolved, a new git commit can be made to finalize the merge.
- git remote: Manage the set of repositories ("remotes") whose branches you track. 
- git pull: Get changes from remote repository into the current branch, so it's up to date.
- git push: Uploads local commited changes to remote repository branch
- --force: overwrites any commit on the remote branch with the local changes. Dangerous

**Advanced level:**
- stash: The command saves the local changes and reverts the working directory to match the HEAD commit.
- rebase: the command applies any commits of current branch ahead of specified one [branch]
- webhooks: Repository webhooks allows to receive HTTP POST payloads whenever certain events happen in a repository.
- Github actions: Helps automate software workflows. Continuous integration (CI) is a software practice that requires frequently committing code to a shared repository. It helps reducing time resolving conflicts or debugging. GitHub runs CI tests and provides the results of each test in the pull request, so the user can see whether the change in the branch introduces an error. When all CI tests in a workflow pass, the pushed changes are ready to be reviewed or merged. Continuous deployment (CD) is the practice of using automation to publish and deploy updates. As part of the typical CD process, the code is automatically built and tested before deployment. 
