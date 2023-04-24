# Rootstrap-GIT
Git Learning track

- Git Init: This command creates an empty Git repository or reinitialize an existing one.<br>
- Git Clone: Clones an entire repository from a hosted location to a new directory.<br>
- git add .: the git add command adds a change in the working directory to the staging area. The "." is a way to add ALL of the files in the current directory instead of going one by one.<br>
- git commit: It records the staged changes just added with the git add . command, to the repository. A log message is possible with "-m"<br>
- git revert: This command it's used to reverse the effect of some earlier unpushed commits (usually one at a time). git revert <commit> will create a new commit with the reverted changes.<br>
 <br>
Branches: <br>
- git branch: Creates, lists or deletes branches <br>
- git checkout: Switch between branches. It is often used with '-b' which also creates and moves into a new branch <br>
- git merge <branch>: Joins the specified branch into the current branch. <br>
- Conflicts generally arise when two people have changed the same lines in a file. The most direct way to resolve a merge conflict is to edit the conflicted file. Commands like git status or git diff will help identify conflicting files. When resolved, a new git commit can be made to finalize the merge. <br>
- git remote: Manage the set of repositories ("remotes") whose branches you track. <br>
- git pull: <br>
