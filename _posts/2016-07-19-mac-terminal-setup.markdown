---
layout: post
title: "Mac terminal setup"
date: 2016-06-19 15:43:59 +0100
categories: mac setup
---

Mac OS terminal looks old and bit dull. We will see here how to install and customize terminal.

Below steps are for my mac terminal setup. You can follow to install and customize your terminal the way you require.

I use iTerm terminal app for Mac OS and Oh-My-ZSH framework to customize iTerm.
Oh-My-ZSH provides dotfile configuration, themes and plugins to customize the terminal. (dotfile is nothing but .zshrc file in your home folder)

## **How to install**

### **iTerm2**

You can install using homebrew

`brew cask install iterm2`

or you can download and install [iTerm2](https://www.iterm2.com/)

Pros of using iTerm2 is

* Highly customizable
* Vast keyboard shortcuts (I rarely use mouse in iTerm)

Wide array of color schemes available for download [iTerm2colorschemes](http://iterm2colorschemes.com/). You can download and import based on your preference. The one I use is "Solarized Dark"

### **Oh-My-Zsh**

#### **Install using shell**

Open iTerm2 and run bellow command to install oh-My-ZSH.

```shell
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

#### **Setting theme**

Oh-My-ZSH comes with set of themes, the one I use is "agnoster". To set theme edit `~/.zshrc` and set `ZSH_THEME="agnoster"`.

List of oh-My-ZSH [themes](https://github.com/robbyrussell/oh-my-zsh/tree/master/themes/), you can see the [preview here](https://github.com/robbyrussell/oh-my-zsh/wiki/Themes).

#### **Enabling plugins**
