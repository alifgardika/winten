# Windows 10 Installer for Ubuntu Server

## How to Use:

1. Create an Ubuntu image on Digital Ocean.
2. Turn off the server.
3. Navigate to the Recovery Menu and choose "Boot from Recovery ISO."
4. Turn on the server.
5. Open the console, then type 6 and press Enter.
6. Download this repository with: `wget https://raw.githubusercontent.com/alifgardika/winten/main/win.sh`
7. After that, use this command: `bash win10.sh`
8. Once the installation is complete, close the console.
9. Turn off, go back to the Recovery Menu, choose "Boot from Hard Drive," and turn on the server.
10. Navigate to the Access menu and launch the Recovery Console.
11. Set the IP Address; it should be the same as on Digital Ocean.

## How to Log In:

1. Open Remote Desktop Connection on your desktop.
2. IP Address: 5000 (we use port 5000), username: WhatUpTime.com, and password: P@ssword64.

## Mirror:
[Windows on Cloud](https://windows-on-cloud.wansaw.com/)

## Source:

- [Nixpoin](https://nixpoin.com/tutorial/script-install-windows-digitalocean/)
- [amjiddader](https://github.com/amjiddader/windows-on-cloud)
