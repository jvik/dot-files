# How to enable config files

## Install stow

```sh
sudo pacman -S stow
```

## Usage

Clone repo into home folder

```sh
git clone git@github.com:jvik/dot-files.git ~
```

Stow package

```sh
stow <packagename> # activates symlink
stow -n <packagename> # trial runs or simulates symlink generation. Effective for checking for errors
stow -D <packagename> # delete stowed package
stow -R <packagename> # restows package
```
