# Config Linux avec theme

## Install XFCE4
```
apt-get install xfce4
```

## Install Arc theme
Debian
```
echo 'deb http://download.opensuse.org/repositories/home:/Horst3180/Debian_8.0/ /' >> /etc/apt/sources.list.d/arc-theme.list 
apt-get update
apt-get install arc-theme
```
Ubuntu 15.10
```
sudo sh -c "echo 'deb http://download.opensuse.org/repositories/home:/Horst3180/xUbuntu_15.10/ /' >> /etc/apt/sources.list.d/arc-theme.list"
sudo apt-get update
sudo apt-get install arc-theme
```

## Icon Elementary
http://danrabbit.deviantart.com/art/elementary-Icons-65437279
```
cp -r /dossier/elementary /usr/share/icons/
```


# MEMO
Shutdown
```
command : xfce4-session-logout --halt
```

# ZSH
```
$ apt-get install zsh
$ chsh (/bin/zsh)
```
Install OHMZSH
```
$ sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
```
Ajouter dans .bashrc
```
exec zsh
```

Ajouter dans .zhrc
```
ZSH_THEME="agnoster"
setopt correctall
export TERM="xterm-256color"
export DEFAULT_USER=eni
setopt RM_STAR_WAIT
```

Install Powerline Font
```
$ git clone https://github.com/powerline/fonts.git
$ ./fonts/install.sh
$ rm -rf fonts
$ fc-cache -vf
```

config hack font. https://github.com/chrissimpkins/Hack

Solarized
```
$ sudo apt-get install dconf-cli
$ git clone https://github.com/Anthony25/gnome-terminal-colors-solarized.git
$ cd gnome-terminal-colors-solarized
$ ./install.sh
```
