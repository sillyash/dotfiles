# i3 with Kitty and Polybar

## Screenshots

![i3-kitty1](./screenshot1)
![i3-kitty2](./screenshot2)


## Packages

### Kitty, i3 and Polybar

    sudo apt install kitty i3 polybar

### Screenshot tools

    sudo apt install maim xclip xdotool

Note that screenshot key is set to the ```printscrn``` key for full screenshot, and ```super + printscrn``` for cropped screenshot.

### Zsh and Oh My Zsh

    sudo apt install zsh
    sh -c "$(wget https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"

### Feh (for background)

    sudo apt intsall feh

### i3lock-fancy

    git clone https://github.com/meskarune/i3lock-fancy.git
    cd i3lock-fancy
    sudo make install

<br>

## Setup

### Gnome as a desktop manager

For startup, login, etc.

**I use ```gnome-tweaks``` to change fonts and gtk themes**

### Copying this repository

**Don't forget to add a dot in front of the folder names**

```config``` -> ```.config``` etc...
Click yes if your system prompts you about overwriting some files.
