# Ref: [Chocolatey](https://chocolatey.org/install)

##Disable ExecutionPolicy (open CMD as administrator) and Install Chocolatey.

> Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))

***Wait a few seconds for the command to complete.***

###### Apps:

```
choco install googlechrome -y
choco install pycharm -y
choco install 7zip --version 22.1 -y
choco install qbittorrent --version 4.4.3.1 -y
choco install revo-uninstaller --version 2.3.8.0 -y
choco install greenshot --version 1.2.10.6 -y
choco install cyberduck -y
choco install adobereader -y
choco install vlc -y
choco install github-desktop -y
choco install vcredist2017 -y
choco install git

```
