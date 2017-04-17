# Config Linux avec theme

## Install XFCE4
```
apt-get install xfce4
```

## Install Arc theme
https://github.com/horst3180/arc-theme
Install Unity tweak tool
```
sudo sh -c "echo 'deb http://download.opensuse.org/repositories/home:/Horst3180/xUbuntu_16.04/ /' > /etc/apt/sources.list.d/arc-theme.list"
sudo apt-get update
sudo apt-get install arc-theme
```
Comment outline-style in /usr/share/themes/Arc-Dark/gtk-3.0/gtk.css

## Icon Arc theme
```
sudo apt-get install autotools-dev
sudo apt-get install autoconf
git clone https://github.com/horst3180/arc-icon-theme --depth 1 && cd arc-icon-theme
./autogen.sh --prefix=/usr
sudo make install
cp -R Arc /usr/share/icons
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
