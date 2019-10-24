# How to install Acestream (latest version) on Deepin

**Let's install the required prerequirements**

Open the therminal and execute the following commands:

```bash
sudo apt-get install python-setuptools
sudo apt-get install python-m2crypto
sudo apt-get install python-apsw
sudo apt-get install python-gtk2
sudo apt-get install python-appindicator
```

**Install the missing library (libssl1.0.0)**

Open the therminal and execute the following commands:

```bash
wget "http://security.debian.org/debian-security/pool/updates/main/o/openssl/libssl1.0.0_1.0.1t-1+deb8u12_amd64.deb"
sudo dpkg -i libssl1.0.0_1.0.1t-1+deb8u12_amd64.deb
```

## Install Acestream with snap, the easiest way to do it

Open the therminal and execute the following commands (this will install snap package manager and acestream package):

```bash
sudo apt update
sudo apt install snapd
sudo snap install acestreamplayer
```

**That's it! Reboot the PC and enjoy.**

Launching **AceStream player** should directly open the **AceStream engine**, if not open the AceStream engine before opening the player
