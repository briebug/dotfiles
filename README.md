# BrieBug dotfiles

A set of configuration files.

## Getting started

Setup is not automated (yet). For now:

```
cd ~
git clone git@github.com:briebug/dotfiles.git
ln -s ~/dotfiles/zsh .zsh
ln -s ~/dotfiles/zshrc .zshrc
cp ~/dotfiles/git/gitconfig .gitconfig
ln -s ~/dotfiles/git/gitignore .gitignore
```

Link any other rc files that you wish to use.

To change system defaults, copy the `macos` file and uncomment the desired lines, then run the script: 

```
cp ~/dotfiles/macos ~/macos.local
~/macos.local
```

## About

This project was adapted from several sources:

* [holman/dotfiles](https://github.com/holman/dotfiles)
* [mathiasbynens/dotfiles](https://github.com/mathiasbynens/dotfiles)
* [thoughtbot/dotfiles](https://github.com/thoughtbot/dotfiles)
