# Dotfiles
**Dotfiles for my various Linux distros and visual environments, window managers...**

## Debian

### Debian base configuration

This is my basic Debian configuration, these are the first things I do when booting up on a new Debian machine.

#### Add user to sudoers

In ```/etc/sudoers``` add:

    username  ALL=(ALL) NOPASSWD:ALL

#### Update

    sudo apt-get update && sudo apt-get upgrade

#### Install zsh

    sudo apt install zsh

### My Debian configs

#### i3 with kitty, starship, and polybar

[See files and README](./debian/i3-kitty-polybar)

#### Hyprland (TODO)

TODO: put links to dotfiles

## Kali

Distro tested, no ricing done yet.

## Arch

Distro tested, no ricing done yet.

## Other
