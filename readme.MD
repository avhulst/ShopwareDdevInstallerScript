# Shopware DDEV Install Script

Das Script erstellt eine passende Config für DDEV und Installiert Shopware 4 & 5.

## Verwendung des Scripts

Um die neuste Version von Shopware 5 zu Installieren

```
./swinstall.sh install
```

Um eine Spezifische version zu Installieren z.B. 5.4.1

```
./swinstall.sh install 5.4.1
```

Verfügbare versionen anzeigen

```
./swinstall.sh versions
```

## Download

 ```bash
 wget https://raw.githubusercontent.com/motormord/ShopwareDdevInstallerScript/master/swinstall.sh -O swinstall.sh
 chmod +x swinstall.sh
 sudo ln -s ~/swinstall.sh /usr/local/bin/swinstall
 ```

## Installation jq

jq ist ein command-line JSON processor der vom Script verwendet wird. 

Arch Linux:

```
sudo pacman -S jq
```

Debian, Ubuntu, Linux Mint:

```
sudo apt-get install jq
```

Fedora:

```
sudo dnf install jq
```

openSUSE:

```
sudo zypper install jq
```