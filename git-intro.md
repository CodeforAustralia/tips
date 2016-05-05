# Git
## What?
Git *distributed* is a version control tool, you can use it via the command line or via one of many gui based tools.
It is used to manage changes to a file or group of files, particularily (but not limited to) source code in software development, allowing you to recall specific versions later on.
Some of the benefits include:

- reviewing previous versions of a file / project
- compare changes over time for a file / files
- see who modified something / introduced a change to a file
- collaborating on projects

Git is a distributed, meaning each client has a full copy of the entire repository, so if any server dies, the full repo can still be rebuilt from the other clients.  

Git supports 'forking' - taking a copy of the source code from another repository, allowing you to either:
- contribute new changes to the original repository
- progress the repository in your own direction.

This has been great for the open source community, by helping anyone, located anywhere to contribute to a project, or improve on an existing project.

## Basics
Basic git operation involves taking a snapshot (commit) of the files in the repository, along with the changes that have been made on them at a point in time, then stores a reference to this point in time.
Within your repository, git has 'branches' - alternate versions of the source code that you can progress and later merge back into your 'master' branch

### Cloning a repo
Cloning allows you to take a copy of an existing github repository, a copy of the repository is made on your local machine and you can start making changes.

`git clone <url of the repository>`

### Pulling in changes
When someone else makes a contribution to a repo, the changes need to be replicated by all the clients. To copy the changes into your local git repository, you need to run the git pull command, this will synchronize changes from other contributors back into your local repository. When you're using github, you will generally only pull the changes from your github repository.

`git pull`

### Tracking changes
When you have made some changes to your file, you can check the status of your repository by using the status command. This will show you the list of files that:
- have been modified
- have bene added
- have been deleted

`git status`

Changes that are made to files first need to be **staged**, staging is basically your way of telling git 'yes, these are the changes I want to keep'

`git add <file>`

After you have staged the files, if you run a git status, you will see the files that you have staged and a list of the files (if any) that are still unstaged. You must now commit them. The changes do not exist in your history until you commit them. It's important to leave a descriptive message for your commit, the commit message is the only way for you to communicate (cleary) the changes that you have made. It is always a good idea to use words like: 'added','changed','removed','updated' to describe the changes you have made.

`git commit -m 'the message for the changes you are committing'`

### Contributing changes back into the repo
Once your changes are committed, you need to push them to the other clients. When you're using github, the easiest way to do this is to push the changes back to the repository that you have cloned from.

`git push`

## Links
* [Google Tech Talk on git](https://www.youtube.com/watch?v=8dhZ9BXQgc4)
* [Installing git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) | [First time config](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)
* [Good commit messages](https://vip.wordpress.com/documentation/commit-messages/)
* [GUI clients](https://git-scm.com/downloads/guis)

## Glossary
* Repsitory (Repo): a collection of files under version control
* Local copy: the copy of the repo located on your machine
* Master:
* Branch: local copy of the file seperate to your master
* Remote: remote server, the server you're retrieving the repository from ie (github), or pushing your changes to (changes)
