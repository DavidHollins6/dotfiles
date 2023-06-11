# David's Dotfiles

Somewhere for me to keep all of my dotfiles while I build a better developer workflow for myself.


## NVIM

Based off [The Primeagens NVIM Configuration](https://github.com/ThePrimeagen/init.lua) 

Clone this repository into you home directory.

```
cd ~

git init
git remote add origin git@github.com:DavidHollins6/dotfiles.git
git pull origin main
```

Make sure to [install packer](https://github.com/wbthomason/packer.nvim#quickstart)

Source your files

```
:so
```

Install packer plugins

```
:PackerSync
```

Restart vim
