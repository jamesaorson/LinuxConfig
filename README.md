# Linux Config

## Important Links

- [Nerd Fonts](https://www.nerdfonts.com/)
- [Starship](https://starship.rs/)

## Setup

1. Check dependencies are installed

```shell
zsh --version
git --version
# For installing starship
ls /usr/local/bin
```

2. Clone the repo and run the zprezto setup script

```shell
git clone https://github.com/JamesOrson/LinuxConfig
cd LinuxConfig
zsh ./zprezto-setup
```

3.

Replace the installed modules in `${HOME}/.zpreztorc` with the contents of `suggested-modules.zpreztorc`

Easiest method is as follows:

```shell
cat ./suggested-modules.zpreztorc >> ${HOME}/.zpreztorc
vim ${HOME}/.zpreztorc # Comment out or remove the original load module lines. Save file.
source ${HOME}/.zshrc
```

