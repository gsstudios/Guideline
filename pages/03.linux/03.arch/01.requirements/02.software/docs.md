---
title: Software
taxonomy:
    category:
        - docs
---

## Arch Linux

> Arch Linux is only available for 64-Bit systems.

## Download
Download the .iso file and the .iso.sig file from some of the listed provider from  [archlinux.org](https://www.archlinux.org/download/) and open the md5.txt file.


Check the two files in the same folder with the following command:

__Check the .ISO file:__

- for Arch user
  - ```pacman-key -v archlinux-<version>-x86_64.iso.sig```
- other [GnuPGP](https://wiki.archlinux.org/index.php/GnuPG) systems
  - ```gpg --keyserver pgp.mit.edu --keyserver-options auto-key-retrieve --verify archlinux-<version>-x86_64.iso.sig```
- and check the md5sum with the following command
  - ```md5sum archlinux-2018.12.01-x86_64.iso```

> Another method to verify the authenticity of the signature is to ensure that the public key's fingerprint is identical to the key fingerprint of the [Arch Linux developer](https://www.archlinux.org/people/developers/) who signed the ISO-file. See [Wikipedia:Public-key_cryptography](https://en.wikipedia.org/wiki/Public-key_cryptography) for more information on the public-key process to authenticate keys.
