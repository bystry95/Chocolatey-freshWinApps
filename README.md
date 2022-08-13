# Ref: [Chocolatey](https://chocolatey.org/install)

##Disable ExecutionPolicy (open CMD as administrator) and Install Chocolatey.

> Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))

***Wait a few seconds for the command to complete.***

###### Apps:

```
choco install googlechrome --version 104.0.5112.81 -y
choco install vscode --version 1.70.0 -y
choco install bitwarden --version 2022.6.2 -y
choco install messenger --version 153.0.380000452 -y
choco install malwarebytes --version 4.5.10.291 -y
choco install 7zip --version 22.1 -y
choco install qbittorrent --version 4.4.3.1 -y
choco install revo-uninstaller --version 2.3.8.0 -y
choco install greenshot --version 1.2.10.6 -y
choco install onedrive --version 22.141.0703.0002 -y
choco install adobereader --version 2022.001.20169 -y
choco install vlc --version 3.0.17.4 -y
choco install github-desktop --version 3.0.5 -y
choco install vcredist2017 --version 14.16.27033 -y

```
