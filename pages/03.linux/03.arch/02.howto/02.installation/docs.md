---
title: Installation
taxonomy:
    category:
        - docs
---

## Install the ISO file
```
fdisk -l
```
> (check _of=/dev/sdd_, if it's really your USB Stick!!!)

```
sudo dd bs=4M if=~/Downloads/archlinux-2018.12.01-x86_64.iso of=/dev/sdd
```
