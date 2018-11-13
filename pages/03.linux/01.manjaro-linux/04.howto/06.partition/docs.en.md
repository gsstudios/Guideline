---
title: Partition
taxonomy:
    category:
        - docs
---

## Manjaro Linux
We recommend to set up **_3_** partition.

Choose **_root_** or **_/_** and use ext4 partition and encrypt the root partition 40GB Should be enough.

Take 4GB for the **_swap_** partition. That’s enough. If you have enough RAM like 8 or more, it is not really necessary to use a swap partition or file. If you have enough RAM and storage, make it ... just in case.

The rest will be for the **_home_** partition. First of all, choosing a home partition is very important. If someday you want to try another distribution, you can mount the home partition on any Linux system.
This makes it very convenient to try a different distribution without saving your data. But do not forget to save the key from / = “/crypto_keyfile.bin”
So choose also the encryption option for the home partition.

(After installing your operating system, you need to change back your BIOS settings)