# How to Get Emacs?

Emacs is available on all major operating systems: Windows, Macintosh and all possible Linux distributions.

Here is my attempt to list down all possible ways to obtain Emacs.

## Windows

On Windows, you can just download Emacs binary from [http://ftp.gnu.org/gnu/emacs/windows](http://ftp.gnu.org/gnu/emacs/windows) and place it in a directory on your disk.

To run Emacs, you can execute the binary `bin\runemacs.exe`. You can create a shortcut to this file and place it to your Desktop if you like.

Optionally, you can add this location to your environment variable `PATH`, so that you will be able to start it from a Command Prompt window.

## Macintosh

There are multiple ways to install Emacs on a Macintosh computer.

### Homebrew/Cask

The simplest one is to do it using [homebrew](https://brew.sh)

    brew install emacs

Or you can do it with [cask](https://caskroom.github.io).

    brew cask install emacs

This 'favor' of Emacs runs within a Terminal windows and will not offer any of the graphical features.

### emacsformacosx

You can download a '.dmg' file from [https://emacsformacosx.com](https://emacsformacosx.com). This method needs manual installation.

I prefer this flavor as it behaves almost the same as the one available for Windows.

### spacemacs

[Spacemacs](http://spacemacs.org) is a polished community-driven Emacs distribution which combines the features of Emacs and [Vim](http://www.vim.org).

The setup involves downloading Emacs and applying the configs over it to provide a more polished experience.

### Aquamacs

[Aquamacs](http://aquamacs.org) is an Emacs distribution with some extra features.

You can download it from the website.

## Linux

The method of installation of Emacs on Linux depends upon the distribution you use.

### Debian

To install Emacs 24, you can rightaway type the below in a terminal.

    sudo apt-get install emacs24

To install Emacs 25, you need to add a repository, update sources and then install it.

    sudo add-apt-repository ppa:kelleyk/emacs
    sudo apt-get update
    sudo apt-get install emacs25

### Fedora

On Fedora, it is as simple as a dnf command.

    sudo dnf install emacs

## Misc

I am sure as vast a software Emacs is, there are a lot more ways to install it and it would be difficult to list all possible ways here.
To learn about other ways of obtaining Emacs, refer to the [official website](https://www.gnu.org/software/emacs/download.html).