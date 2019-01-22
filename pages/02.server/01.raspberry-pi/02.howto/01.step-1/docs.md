---
title: 'Step 1'
taxonomy:
    category:
        - docs
---

### Downloaded Files

The tar.gz, asc, sha512sum, and the sha512sum.sig files has to be in the same folder.

> The tar.gz file is a compressed file. The .img file is in there.
> Check the tar.gz file with the sha512sum file before you extract it.
> Why you should do that? To make sure that the image file was not damaged during the download. The sig file is to make sure that the sha512sum file is from us (dan/dansman).
> The gpg file is to verify the sig file.


### Check the files

Start your Terminal:
* Linux – Search your apps for your terminal
* Mac – Search your apps for your terminal
* Windows – [Raspberrypi.org](https://www.raspberrypi.org/documentation/remote-access/ssh/windows.md)

Put all the files in the same folder and run in your Terminal:
```
gpg --import DanSman.asc
```
```
gpg --verify sha512sum\ -\ PwOSS-Server_Raspberry-ArchLinux-ARM-xx.xx.xxxx.sig
```
> Fingerprint = 4784 F5FF 89F3 06CF B6F7 704C 2A44 D31D E67D 8EB6

```
sha512sum -c sha512sum\ -\ PwOSS-Server_Raspberry-ArchLinux-ARM-xx.xx.xxxx
```
> Result should be:
> PwOSS-Server_Raspberry-ArchLinux-ARM-xx.xx.xxxx.img: OK


### Flash the .img file

Extract the tar.gz file and put your SD-Card in your computer and flash the image with Etcher.
