---
name: Mac Setup TODO list
about: Follow me :))
title: ''
labels: mac_setup
assignees: ''

---

# FlutterFlow Mac Setup by ms@ff.hr

How to setup (FRESH from store) Mac (Macbook, Mac mini, etc.) with best practices for FlutterFlow development 

## Installation & Configuration

- [ ] Xcode
  - [find latest and stable Xcode here](https://developer.apple.com/download/all/?q=xcode) 
- [ ] GIT
  - run `git` in terminal and follow the automatic installation of `Xcode Command Line Tools`
- [ ] iTerm2
  - https://iterm2.com/downloads.html
  - run `mkdir git`
  - open `Settings -> Profiles`
    - set `Command -> Custom Shell -> /bin/bash`
    - set `Working Directory -> Directory -> /Users/<YOUR_USERNAME>/git`
- [ ] dotfiles by `mathiasbynens`
  - https://github.com/mathiasbynens/dotfiles
  - it will make terminal nicer and more useful
  - run `mkdir ~/dotfiles && ch ~/dotfiles`
  - run `git clone https://github.com/mathiasbynens/dotfiles.git && cd dotfiles && source bootstrap.sh`
- [ ] little sugar to the Bash Aliases
  - run `echo 'alias ll="ls -la"' >> ~/.aliases` 
