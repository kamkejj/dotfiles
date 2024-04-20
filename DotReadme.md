# Dot files README

## Bare Repo Setup
[Dotfiles: Best way to store in a bare git repository](https://www.atlassian.com/git/tutorials/dotfiles)

## Setup (New Computer)

1. Create bare bones git repo
2. From https://www.atlassian.com/git/tutorials/dotfiles
3. `git init --bare $HOME/.cfg`
4. Create alias to use `config` instead of `git` `alias config='/usr/bin/git --git-dir=$HOME/.cfg/ --work-tree=$HOME'`
5. Only show untracked files that had been manually added `config config --local status.showUntrackedFiles no`
