<!-- markdownlint-configure-file {
  "no-inline-html": false,
  "MD041": false
} -->

<div align="center">

# // My Chezmoi-powered Ultimate 💪 Dotfiles \\\

This repo contains the configuration to have my personally preferred power-user experience \
across any machines you have, using [Chezmoi](https://chezmoi.io), the dotfile manager. \
\> `zsh`, `tmux`, `i3wm`, `polybar`, `neovim`, `gtk3`, `urxvt` < \
\
*This automated setup is currently tested only on Arch-based machines.* \
In case dotfiles will be used by at least several users, I'll consider making it more universal. 🙃

![GitHub Release](https://img.shields.io/github/v/release/dmitriy-korotayev/pytgbot-autopost)
![Python Version](https://img.shields.io/badge/python-3.6+-blue.svg?style=flat-square)
<a target="_blank" href="https://www.linkedin.com/in/foreverdev/">
<img height="20" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
[![Contributions welcome](https://img.shields.io/badge/contributions-welcome-orange.svg)](https://github.com/dmitriy-korotayev/pytgbot-autopost/fork)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

<img src="logo.webp" title="Logo" width="40%"
  alt="Finally! Everything is in it's place!"
/>

</div>

## 💡 Overview 💡

My flavour of `Chezmoi`-driven dotfiles collection, with ❤️:

- [x] Powerful `zsh` config with many useful `zim` modules.
- [x] Ansible bootstrap file `setup.yml` with all the necessary Arch Linux packages, used by me.
- [x] Sane `.gitconfig` with short aliases and many more...
- [x] Some of my preferred fonts in `.local/share/fonts`
- [x] `GTK3` & `GTK2` styling configuration
- [x] Basic, yet big and powerful `.tmux.conf`
- [x] `urxvt` config included (`.Xresources` & some useful tools). Used as a terminal for weak or terminal-based machines.

## 🔧 Simple installation 🔧

```sh
export GITHUB_USERNAME=dmitriy-korotayev
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply $GITHUB_USERNAME 
```

## 📈 Future updates 📈
- [ ] `run-once-[...].sh` scripts
- [ ] Test-drive on a new Arch-based Linux installation

<div align="center">

## 🚦 Support 🚦

Contributions, issues, and feature requests are welcome! \
Give a ⭐️ if you like this project!

## 📝 License 📝

MIT License - Free, open-source license with minimal restrictions.

-----------

Copyright (c) 2024 **Dmitriy Korotayev** \
[Profile ⚛️](https://github.com/dmitriy-korotayev "My GitHub profile") \
[Email me 🤝](mailto:korotayev.dmitriy+github "Email any questions you might have!") \
**[LinkedIn (Hire me 😊)](https://www.linkedin.com/in/foreverdev/ "My professional profile: skills, experience and much more...")**

</div>
