#install-mac
[![Build Status](https://travis-ci.org/Yoobic/install-mac.svg?branch=master)](https://travis-ci.org/Yoobic/install-mac)

## Description
This repo contains a simple bash script that installs the dev tools for a mac.

## Prerequisites
* Make sure you have Xcode installed
* Make sure you have zsh or install it `$ apt-get install zsh`
* Make sure zsh is the default shell
  
    ```bash
    sudo dscl 
    change Local/Default/Users/root UserShell /bin/bash /usr/local/bin/zsh
    exit
    ```



## Installation
To install the package run the following command:
```bash
curl -L https://raw.githubusercontent.com/Yoobic/install-mac/master/install.sh | sh
```


It will install the following:
* brew
* zsh
* mongo
* nvm (node)
* git
* tree
* wget
* imagemagick
* iTerm2
* Alfred
* Skype
* Dropbox
* Sublime Text 3
* VirtualBox
* Slack
* gulp
* karma
* mocha
* browser-sync
* jshint
* eslint
* jscs

