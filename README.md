# dotfiles

This repo contains the configuration to setup my machines. This is using [Chezmoi](https://chezmoi.io), the dotfile manager to setup the install.

This automated setup is currently tested only on Arch-based machines.
In case dotfiles will be used by at least several users, I'll consider
making it more universal.

## How to run

```sh
export GITHUB_USERNAME=dmitriy-korotayev
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply $GITHUB_USERNAME
```
