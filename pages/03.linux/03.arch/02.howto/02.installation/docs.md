---
title: Installation
taxonomy:
    category:
        - docs
---

# How to install Arch on your 64 bit computer

## .ISO Download
Download the .iso file and the .iso.sig file from some of the listed provider from  [archlinux.org](https://www.archlinux.org/download/) and open the md5.txt file as well.


Check the two files in the same folder with the following command:

__Check the .ISO file:__

- for Arch user
  - ```pacman-key -v archlinux-<version>-x86_64.iso.sig```

- other [GnuPGP](https://wiki.archlinux.org/index.php/GnuPG) systems

  - ```gpg --keyserver pgp.mit.edu --keyserver-options auto-key-retrieve --verify archlinux-<version>-x86_64.iso.sig```

- and check the md5sum with the following command
  - ```md5sum archlinux-2018.12.01-x86_64.iso```

> Another method to verify the authenticity of the signature is to ensure that the public key's fingerprint is identical to the key fingerprint of the [Arch Linux developer](https://www.archlinux.org/people/developers/) who signed the ISO-file. See [Wikipedia:Public-key_cryptography](https://en.wikipedia.org/wiki/Public-key_cryptography) for more information on the public-key process to authenticate keys.

## Install the iso file to your usb Stick
```
fdisk -l
```
> (check _of=/dev/sdd_, if it's really your USB Stick!!!)

```
sudo dd bs=4M if=~/Downloads/archlinux-2018.12.01-x86_64.iso of=/dev/sdd
```
