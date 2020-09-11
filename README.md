# Setup your macOS

## What does this setup do?

- Install Homebrew for software installation
- Install software:
  - iTerm
  - Slack
  - Firefox Developer Edition
  - Visual Studio Code
  - Zoom
  - Postman
  - Rectangle
- Install command line tools:
  - zsh
  - git
  - antigen
  - zsh-completions
  - exa
  - fasd
  - fzf
- Install the font "Fira Code" for usage in iTerm
- Add shell-integration for iTerm
- Setup zsh with a powerful prompt, aliases and convenient shortcuts
- Create git configuration with user name and email
- Create ssh key and add the passphrase to the macOS keychain
- Configure macOS: make keyboard and Dock faster, show hidden files in Finder

## How to run the setup

1. You should have the latest macOS installed. To make sure, click on the apple logo at the top left, go to "About this Mac" and click "Software Update". Install any missing updates.

1. Find and run the program "Terminal"

1. Go through each of the following steps and copy and paste each command into Terminal and press Enter. Wait for the command to finish and follow any instructions.

1. In case of any Error, read the error text from the beginning and google for help. Ask a head coach for help.

**Copy each command and paste it into the Terminal. Run it by pressing `Enter`. If a command does not work and you can't fix the problem, continue with the next command.**

## Install Homebrew and Command Line Tools

```sh
zsh <(curl -s https://raw.githubusercontent.com/neuefische/zsh-setup/master/scripts/install-brew)
```

## Install macOS Apps

```sh
zsh <(curl -s https://raw.githubusercontent.com/neuefische/zsh-setup/master/scripts/install-apps)
```

## Install MongoDB

```sh
zsh <(curl -s https://raw.githubusercontent.com/neuefische/zsh-setup/master/scripts/install-mongo)
```

## Setup shell-integration for iTerm

```sh
zsh <(curl -s https://raw.githubusercontent.com/neuefische/zsh-setup/master/scripts/setup-iterm)
```

## Copy configs

```sh
zsh <(curl -s https://raw.githubusercontent.com/neuefische/zsh-setup/master/scripts/copy-configs)
```

## Setup git

Please enter the requested inputs and press Enter.

```sh
zsh <(curl -s https://raw.githubusercontent.com/neuefische/zsh-setup/master/scripts/setup-git)
```

## Setup macOS

Please restart your Mac after this.

```sh
zsh <(curl -s https://raw.githubusercontent.com/neuefische/zsh-setup/master/scripts/setup-macos)
```
