
# RAGSERV (Unattended) Ragnarok Installer

An automated rAthena Emulator Unattended Installer made by Cervantes (vhost.rocks) and maintained to use by gamingmagic (FenrirMachine) and now maintained and updated by GodKnowsJhomz.

## Installer Version
![RAM](https://img.shields.io/badge/Ver.-1.0.9-Green.svg?)

## Server Requirements

Here are the system requirements for the Ragnarok Installer :

![RAM](https://img.shields.io/badge/OS-Debian%2010-red.svg?)
![RAM](https://img.shields.io/badge/Memory-2%20GB-green.svg?)
![RAM](https://img.shields.io/badge/Storage-20%20GB-yellow.svg?)
## Deployment

To install Ragnarok Installer in your server you must run this command as root user:

```bash
apt update && apt-get -y install curl && cd /home && curl -o ragserv-rathena -L https://raw.githubusercontent.com/GodKnowsJhomz/installer/master/ragserv-rathena && sh ragserv-rathena
```
## VNC Allowing IP

To allow your current ip to access VNC Server you must run this command as root user:

```bash
wget -qO - https://raw.githubusercontent.com/GodKnowsJhomz/installer/main/ipallowed-vnc | bash
```
