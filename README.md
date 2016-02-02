## Screenshots

#### icons
![El General preview](EIgeneral.png)

#### cursors
![Bridge preview](Bridge.png)

## Installation

#### icons and cursors
* `git clone https://github.com/izuolan/ieos.git && cd ieos`
* `sudo mv ElGeneral /usr/share/icons/`
* open **Setting--Tweaks**, change the icons and cursors.
* edit `cd /usr/share/icons/default && sudo vim index.theme`
```
[Icon Theme]
Name=ElGeneral
Inherits=ElGeneral
```

> if you don't hava Tweaks, just install:
```shell
sudo apt-add-repository ppa:mpstark/elementary-tweaks-daily
sudo apt-get update
sudo apt-get install elementary-tweaks
```

#### theme
* [Download Deb(Update 2016.02.02)](http://download.opensuse.org/repositories/home:/Horst3180/xUbuntu_15.04/all/arc-theme_1450051815.946cbf5_all.deb)
* `sudo dpkg -i arc-theme_1450051815.946cbf5_all.deb`

## Update
* `git pull`
* `sudo mv ElGeneral /usr/share/icons/`
