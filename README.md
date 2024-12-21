# Dotfiles

Organize dotfiles using stow.

## Using Stow

Stow requires the directory it is run from to mirror the home directory layout. Any files/directories that should not be copied to the home directory should be included in the `.stow-local-ignore` file.

## Update Dotfiles

```bash
$ pwd
~/dotfiles
$ stow .
```
