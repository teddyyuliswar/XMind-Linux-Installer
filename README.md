# XMind-Linux-Installer
A simple BASH script to install XMind in Linux

How to install XMind 8 or Latest on Linux

1. Download latest XMind from [http://www.xmind.net/download/linux/] (http://www.xmind.net/download/linux/) and rename file zip to xmind.zip
2. Make sure the dependencies are satisfied for your distribution
 - Debian, Ubuntu, Mint or other Linux distribution with .deb package. `sudo apt-get install unzip install default-jre libgtk2.0-0 libwebkitgtk-1.0-0 lame libc6 libglib2.0-0`
 - Fedora, CentOS, RHEL, or other Linux distribution with .rpm packages. `sudo yum install unzip java webkitgtk gtk2 glibc lame` or `sudo dnf install unzip java webkitgtk gtk2 glibc lame`
3. Place this script in the same directory.  `curl -O https://raw.githubusercontent.com/mriza/XMind-Linux-Installer/master/xmind-installer.sh`
4. Run the installer, `sudo xmind-installer.sh username`

username is the user that will be use/run the software. Because XMind will need a data directory in the user home named 'workspace'

This script is an automation of [this process](http://www.xmind.net/m/PuDC)

![process](https://xmindshare.s3.amazonaws.com/preview/PuDC-FwEzHqO-77495.png)
