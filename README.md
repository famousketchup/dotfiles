# My Chezmoi-powered Ultimate Dotfiles

This repo contains the configuration to have my personally preferred power-user experience
across any machines you have, using [Chezmoi](https://chezmoi.io), the dotfile manager.
*This automated setup is currently tested only on Arch-based machines.*
In case dotfiles will be used by at least several users, I'll consider making it more universal.

## Overview

`Chezmoi`-driven dotfiles collection, with:

- [x] Powerful `zsh` config with many useful `zim` modules.
- [x] Ansible bootstrap file `setup.yml` with all the necessary Arch Linux packages, used by me.
- [x] Sane `.gitconfig` with short aliases and many more...
- [x] Some of my preferred fonts in `.local/share/fonts`
- [x] `GTK3` & `GTK2` styling configuration
- [x] Basic, yet big and powerful `.tmux.conf`
- [x] `urxvt` config included (`.Xresources` & some useful tools). Used as a terminal for weak or terminal-based machines.

## Simple installation

```sh
export GITHUB_USERNAME=dmitriy-korotayev
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply $GITHUB_USERNAME 
```

## Future updates
- [ ] `run-once-[...].sh` scripts
- [ ] Test-drive on a new Arch-based Linux installation

## Support

Contributions, issues, and feature requests are welcome!
Give a ⭐️ if you like this project!

## License

MIT License

Copyright (c) 2024 **Dmitriy Korotayev**
- [Profile](https://github.com/dmitriy-korotayev "My GitHub profile")
- [Email me](mailto:korotayev.dmitriy+github "Email any questions you might have!")
- [LinkedIn (Hire me)](https://www.linkedin.com/in/foreverdev/ "My professional profile: skills, experience and much more...")
