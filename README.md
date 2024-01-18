# `~/.zsh_profiles`

zsh profiles sourced by `.oh-my-zsh`, with:
```zsh
## .zshrc

## Add additional completions
## ... remove `~/.zcompdump*` to refresh
fpath=(
    ~/.zsh_profiles/completions
    $fpath
    ~/.zsh_profiles/plugins/zsh-completions/src
)

# Would you like to use another custom folder than $ZSH/custom?
ZSH_CUSTOM=~/.zsh_profiles
```
check out [`~/.zshrc`](https://github.com/bryango/cheznous/blob/NOUS/.zshrc) for the latest config.

## management

- This repo is managed with [git submodules](./.gitmodules) (_what have I done..._)
- Well, I was young and naïve, and now I am old and lazy!
- To update:
```bash
git submodule update --recursive --init --single-branch --remote
```
