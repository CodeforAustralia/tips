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
Use git pull, to synchronize changes from other contributors back into your local repository
`git pull`

### Tracking changes

### Contributing changes back into the repo


## Links
* [Google Tech Talk on git](https://www.youtube.com/watch?v=8dhZ9BXQgc4)
* [Installing git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) | [First time config](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)

## Glossary
* Repsitory (Repo): a collection of files under version control
* Local copy: the copy of the repo located on your machine
* Master:
* Branch: local copy of the file seperate to your master
* Remote: remote server, the server you're retrieving the repository from ie (github), or pushing your changes to (changes)
