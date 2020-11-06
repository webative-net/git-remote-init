#git-remote-plus

## Install

Copy the files of `bin` folder to a directory in your `PATH`. Or add the `bin` folder to your `PATH`.

## Usage

* `git remote-save` : save the remotes in .gitremotes file.
* `git remote-init` : init the remotes from .gitremotes file

## Adding a subtree to another repo

* `git subtree add --prefix bin https://github.com/webative-net/git-remote-init.git master --squash`
* `git subtree pull --prefix bin https://github.com/webative-net/git-remote-init.git master --squash`

## Committing back to the subtree repo
* `git subtree push --prefix bin https://github.com/webative-net/git-remote-init.git master`
