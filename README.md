## Install Homebrew

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Github Setup

Copy `git_config` file contents and paste into global config
```
git config --global --edit
```

Replace HTTPS usage with SSH by generating and adding new key
1. Generate new SSH key
```
ssh-keygen -t ed25519 -C "hrs7991@gmail.com"
```
2. Eval SSH agent
```
eval "$(ssh-agent -s)"
```
3. Add private key to SSH keys list
```
ssh-add -K ~/.ssh/id_ed25519
```
4. Copy public key to clipboard
```
pbcopy < ~/.ssh/id_ed25519.pub
```

## VSCode Setup

- shell command

## OhMyZsh Setup

Theme `xiong-chiamiov-plus`

Plugins
- 