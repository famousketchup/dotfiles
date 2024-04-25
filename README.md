<!-- markdownlint-configure-file {
  "no-inline-html": false,
  "MD041": false
} -->

<div align="center">

# // My Chezmoi-powered Ultimate 💪 Dotfiles \\\

This repository provides the setup for a personalized power-user \
experience on any Linux machine utilizing [Chezmoi](https://chezmoi.io), the dotfile manager. \
\> `zsh`, `tmux`, `i3wm`, `polybar`, `neovim`, `gtk3`, `urxvt` < \
\
*At the moment, this automated setup has only been tested on `Arch`-based machines.* \
Should these dotfiles be utilized by at least a few users, I will consider expanding its applicability. 🙃

![GitHub Release](https://img.shields.io/github/v/release/dmitriy-korotayev/dotfiles)
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

- [x] Highly effective `zsh` configuration with many useful `zim` modules, "aliases" that save time, and a lot more!
- [x] Gorgeous `polybar` theme built by [@adi1090x](https://github.com/adi1090x/polybar-themes) and customized to meet my personal preferences.
- [x] A sane `.gitconfig` file with minimal aliases and sensible defaults like "diff-so-fancy"...
- [x] A big, mighty, yet rather fundamental '.tmux.conf' file.
- [x] Provided in the Ansible Bootstrap file `setup.yml`, all the necessary Arch Linux`-based packages which I personally use.
- [x] The '.local/share/fonts' directory includes a few of my favorite typefaces.
- [x] `GTK3` & `GTK2` styling configuration.
- [x] `urxvt` config (`.Xresources` and a couple of helpful tools) provided. Used as a terminal for low-powered or terminal-based devices.

## 🔧 Simple installation 🔧

```sh
export GITHUB_USERNAME=famousketchup
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
