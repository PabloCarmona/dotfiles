<!-- MIT License

Copyright (c) 2022 Pablo Carmona

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE. -->

# dotfiles and setup config

## ssh

- Generate SSH key. Follow steps here: https://docs.github.com/es/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
- Add SSH key to Github. Follow steps here: https://docs.github.com/es/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account

## Oh my zsh

- Install zsh(if needed) and oh-my-zsh.
- Oh my ZSH install here: https://ohmyz.sh/#install

## Terminal

- [iterm2](https://iterm2.com/)
- [Hyper terminal](https://hyper.is/)

## Prompts

- [oh-my-zsh prompts](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes)
- [powerlevel10k](https://github.com/romkatv/powerlevel10k)

## Programming fonts

- [Nerd Fonts](https://www.nerdfonts.com/)
- Download owned fonts in my cloud


## Color themes

- [OneDark Pro](https://binaryify.github.io/OneDark-Pro/#/)
- [Dracula](https://draculatheme.com/)
- [Synthwave84](https://marketplace.visualstudio.com/items?itemName=RobbOwen.synthwave-vscode)
- [Andromeda](https://github.com/EliverLara/Andromeda)

## Brew

Dependencies tree below:

```shell
asciinema
└── python@3.10
    ├── gdbm
    ├── mpdecimal
    ├── openssl@1.1
    │   └── ca-certificates
    ├── readline
    ├── sqlite
    │   └── readline
    └── xz

autoconf
└── m4

ca-certificates

project-codeflare/codeflare-cli/codeflare

coreutils
└── gmp

docker

figma

gdbm

gettext

git
├── gettext
└── pcre2

gmp

helm

htop
└── ncurses

hyper

ibm-cloud-cli
├── helm
└── kubernetes-cli

jq
└── oniguruma

keeweb

kubernetes-cli

m4

minikube
└── kubernetes-cli

mpdecimal

ncurses

nvm

oniguruma

openssl@1.1
└── ca-certificates

pcre2

pkg-config

romkatv/powerlevel10k/powerlevel10k

pyenv
├── autoconf
│   └── m4
├── openssl@1.1
│   └── ca-certificates
├── pkg-config
└── readline

python@3.10
├── gdbm
├── mpdecimal
├── openssl@1.1
│   └── ca-certificates
├── readline
├── sqlite
│   └── readline
└── xz

readline

slack

spotify

sqlite
└── readline

visual-studio-code

webex

websocat

xz

zsh-autosuggestions

zsh-syntax-highlighting
```