## Screenshots

#### icons
![El General preview](EIgeneral.png)

#### cursors
![Bridge preview](Bridge.png)

## Installation

#### icons and cursors, plank
* `git clone https://github.com/izuolan/ieos.git && cd ieos`
* `sudo mv ElGeneral /usr/share/icons/`
* `sudo mv ieos /usr/share/plank/themes/`
* open **Setting--Tweaks**, change the icons and cursors(if you don't hava Tweaks, just install).
* edit `cd /usr/share/icons/default && sudo vim index.theme`
```
[Icon Theme]
Name=ElGeneral
Inherits=ElGeneral
```

> Install Tweaks:
```shell
sudo apt-add-repository ppa:mpstark/elementary-tweaks-daily
sudo apt-get update
sudo apt-get install elementary-tweaks
```

#### theme
* [Download Deb(Update 2016.02.02)](http://download.opensuse.org/repositories/home:/Horst3180/xUbuntu_15.04/all/arc-theme_1450051815.946cbf5_all.deb)
* `sudo dpkg -i arc-theme_1450051815.946cbf5_all.deb`

> [arc-theme](https://github.com/horst3180/arc-theme)

## Update
* `git pull`
* `sudo mv ElGeneral /usr/share/icons/`

## About
icons and cursors will continue to update here.
