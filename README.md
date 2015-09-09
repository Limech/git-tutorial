## Git Hands-on

### Introduction
This is a sample [Markdown](http://daringfireball.net/projects/markdown/syntax) file.

It will be used as a starting point for trying out git.

We will be using the following tools on Windows:
* [Git](http://git-scm.com/) - v1.9.5 (March 2015)
* [SourceTree](https://www.sourcetreeapp.com/) - v1.6.14
* [Visual Studio Code](https://code.visualstudio.com/) - v0.7.10

### Overview

We will learn:
* Git configuration
* Creating a repository
* Staging files
* Creating *(good)* commits
* Amending commits
* Ignoring files
* Creating / deleting branches
* Merging / rebasing branches
* Squashing commits
* Fetch / push / pull from remote repository
* Creating pull requests
* Forking / Cloning a repository

We will **not** cover:
* Stashing
* Cherry-picking
* Reflog
* Worflows (ex: Git flow)
* Tags
* Diff
* Merge conflicts
* Rewriting history
* Blame
* Hooks
* Git internals

### Basic config

    git config --global user.name "Limech"
    git config --global user.email "limech@gmail.com"
    git config --global credential.helper wincred
