---
title: Recommendation
taxonomy:
    category:
        - docs
---

## Manjaro Linux

After installing and restarting your new system, connect your system to the Internet and look for the terminal application and copy the following command into the terminal:

    sudo pacman-mirrors -f 10 && sudo pacman -Syyu
and follow the instruction.


Afterwards, install at first yaourt for yay (We know, it’s sounds stupid for the pros here)

    sudo pacman -S yaourt && yaourt -S yay && sudo pacman -Rs yaourt
It’s just quicker.

If you are using the KDE version, we recommend disabling “Baloo”, which can be very annoying. It checks the files and it can fill your memory very fast, which makes your system very slow.

Terminal command is:

    balooctl disable

 
That’s it. Now take your time and get familiar with Linux.

If you need help finding alternatives to Windows, Mac etc. software, or if you need help with the installation, just join the [community](https://forum.pwoss.xyz/) and ask your questions.