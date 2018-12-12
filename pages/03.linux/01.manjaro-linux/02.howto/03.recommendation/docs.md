---
title: Recommendation
taxonomy:
    category:
        - docs
---

## Manjaro Linux

After installing and restarting your new system, connect your system to the internet and look for the terminal application and copy the following command into the terminal:

    sudo pacman-mirrors -f 10 && sudo pacman -Syyu
and follow the instruction.

The above command searches and stores details of 10 recently updated package mirrors, and then forces the system to refresh its package database in order to check for new updates.

Afterwards, install at first yaourt for yay (We know, it’s sounds stupid for the pros here)

    sudo pacman -S yaourt && yaourt -S yay && sudo pacman -Rs yaourt
It’s just quicker.

If you are using the KDE version, we recommend disabling “Baloo” (the indexing service for KDE). 

Terminal command is:

    balooctl disable
 
That’s it. Now take your time and get familiar with Linux.

If you need help finding alternatives to Windows, Mac etc. software, or if you need help with the installation, just join the [community](https://forum.pwoss.xyz/) and ask your questions.