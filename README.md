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
