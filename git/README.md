# Git and github
## Git
Git is a Version Control System, version control refers to the process of saving different files or "versions" throughout the different stages of a project, to keep track of what has been done and to go back to an earlier stage if they decide they want to revert some of the changes they have made.
Git also makes it easy to record and compare different versions of a file. This means that details about what changed, who changed what, or who has started a proposal, can be reviewed at any time.
## Why is a version control system useful?
by renaming different versions of the same file in various ways such as blogScript.js, blogScript_v2.js, blogScript_v3.js, blogScript_final.js, blogScript_definite_final.js, and so on, makes it easier to resolve bugs and fix other errors that may occur during development. You can also note changes in each version, for group projects.
git does not store incrementally but each version is saved as a 'snapshot' (copies of the files as they are at the time).
# The basic Git workflow
![image text](https://www.freecodecamp.org/news/content/images/2020/08/git-basic-workflow-codesweetly.png)
- Modify files in the working directory.
Note that any file you modify becomes a file in the modified state.

-Selectively prepare the files you want to commit to the .git directory.
Note that any file you prepare (add) to the staging area becomes a file in the prepared state.  
Also note that the prepared files are not yet in the .git database.
Prepare means that information about the prepared file is included in a file (called "index") in the .git repository.

- Commit the file(s) you have prepared to the .git directory. That is, permanently save a snapshot of the staged file(s) to the .git database. Note that any version of the file you commit to the .git directory becomes a file in the committed state.
# Github
GitHub makes it easy to collaborate with git. It is a web-based platform where users can host Git repositories, making it easy to share and collaborate on projects with anyone at any time.
GitHub repositories are publicly available. Developers around the world can interact and contribute to each other's code to modify or improve it, known as "social coding". In a way, this makes GitHub a networking site for web professionals.
There are three main actions you can take when it comes to interacting with other developers' code on GitHub:

* Forking: The process of copying someone else's code from the repository to modify it.
* Pull: When you are done making changes to someone else's code, you can share them with the original owner via a "pull request".
* Merge: Owners can add new changes to their projects through a merge, and give credit to the contributors who suggested them.
# Branchs
Creating branches is a feature available in most Verizon controls, branches in git are an effective pointer to snapshots of a change, such as adding features or fixing bugs.

A branch is a pointer to one of the commits, the default branch is master to the first commit we make, with each commit the branch will move forward.

A branch represents an independent line and serves as an abstraction of change, preparation and commit processes, it is a way to request a new working directory, commits are restricted in the current branch, it creates a fork in the project.

# Git Origin/Master
Origin/Master is a remote repository, the origin is where the original repository is located and the master represents the main branch. 

### Git master
It is the default git branch, after cloning a repository from a remote server, the local repo contains only a local branch called "master", it is the default branch of the repository known as the main branch, this local repo has its master branch which is always updated with the sample from a remote repo.
### Git Origin
This is the remote repository where your commit is published, by default it is called origin.
## Remote and local branches
Git has two types of branches called local remote, to use git pull and git push you must tell your local branch which branch you operate on. so both the term origin/master is used to deal with a remote repository and a local branch called master, the term origin master push is used to push changes to the remote repo and pull to access the repo from remote to local.
# how to use branches?
* The `git branch` command allows you to create, list and delete a branch as well as rename it.
* The `git checkout` command allows you to move between branches.
* `git merge` lets you merge branches
### command options
- `[git branch --list][git branch]` list all branches in your repo
- `git branch "name branch"` Create a new branch
- `git branch -d` Safely removes a Branch
- `git branch- D` Force deletion
- `git branch -m` Change the name
- `git branch -a` Lists remote branches
