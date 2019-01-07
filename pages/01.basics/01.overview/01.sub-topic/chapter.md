---
title: 'Software of the Raspberry Pi - Image'
taxonomy:
    category:
        - docs
---

# Raspberry PI - Software

### Which Software are included in the Raspberry Pi - Image?

### Arch Linux ARM

Arch Linux operating system …

is known as a leading/bleeding/cutting edge ([Wikipedia link](https://en.wikipedia.org/wiki/Bleeding_edge_technology)) and as a rolling release ([Wikipedia link](https://en.wikipedia.org/wiki/Rolling_distribution)) distro ([Wikipedia link](https://en.wikipedia.org/wiki/Linux_distribution)). This means that you will receive the updated software very quickly. You don’t have to “jump” to another version like Windows 7 to Windows 10 or Ubuntu 16.04 to Ubuntu 18.04 etc. which can be painful sometimes. Three other good reasons for Arch are:

1. The security patches will be fixed very fast, because you’re always up to date.
2. You only have software on your system, what you have installed. No bloatware ([Wikipedia link](https://en.wikipedia.org/wiki/Pre-installed_software)).
3. [Arch wiki](https://wiki.archlinux.org/) is huge and very helpful.

The downside can be an unstable system because the new software is not tested properly. For this reason, we recommend that you follow our update interval, which is on the 20th each month ([PwOSS link](https://pwoss.xyz/#updates)). But we’ve been using Arch for a while and never had any major problems.

The disadvantage of number 2: If you are unfamiliar with Linux, you should not use Arch for your desktop/laptop PC. It can be very time consuming to get a running system, because nothing is installed (Manjaro is fine – user friendly distro based on Arch). That’s why we chose Manjaro Linux & Linux Mint in our desktop/laptop PC “Guideline”, which is very easy to install.


### Seafile

Seafile is a cloud server like Dropbox, Google Drive etc. ([Wikipedia link](https://en.wikipedia.org/wiki/Seafile)).

Seafile is focused on synchronized files only. Seafile is very solid without any major problems. No missing data, no corrupt data… . It’s doing what’s made for. The synchronization between your Devices is just working great. That’s the reason we chose it.


### Radicale

Radicale is a server to sync your calendar, contacts and todo list ([Radicale link](https://radicale.org/)).
Same like Seafile. It’s just doing what’s made for.


### OpenVPN

OpenVPN is to reach all your services (server) and to get an encrypted connection all the time ([Wikipedia link](https://en.wikipedia.org/wiki/OpenVPN)).


### LUKS

(Linux Unified Key Setup)

LUKS is to encrypt your externalHD/HardDrive or USB Stick. If a burglar steals the Hard Drive or anyone else wants to get access to your personal data. The only way to use the Hard Drive without the key or password is to format/delete the whole device. So, keep the key or password safe.


### Yay

Yay is a AUR-Helper. What is AUR ([Archlinux.org link](https://wiki.archlinux.org/index.php/Arch_User_Repository))?
The Helper is needed for a few dependencies which are necessary to get the Seafile server running and for the downgrade software.


### Downgrade

Sometimes it is necessary to downgrade a software because of a unstable system. The software “downgrade” makes it very simple.
[Github link](https://github.com/pbrisbin/downgrade)


### MariaDB

MariaDB is a database management tool. Which is necessary for example to safe your login data for your Seafile server ([Wikipedia link](https://en.wikipedia.org/wiki/MariaDB)).


### DDClient

DDClient is needed for your Dynamic DNS ([archlinux.org link](https://wiki.archlinux.org/index.php/Dynamic_DNS)) – noip.com account. Mostly every Internet Service Provider (ISP) is changing your ip address (daily, weekly or monthly).

So, you’ll need actually a static IP address (which can be expensive) otherwise your VPN connection doesn’t work and your servers aren’t reachable. DDClient is sending your IP address to your Dynamic DNS Account.


### Cronie

This software is needed for DDClient. A time schedule possibility to send commands to your system on time. The “cronjob” for your DDClient runs at 4:45 am every day ([archlinux.org link](https://wiki.archlinux.org/index.php/Cron)).


### UFW

(Uncomplicated Firewall)

UFW is your firewall ([Wikipedia link](https://en.wikipedia.org/wiki/Firewall_(computing))).
