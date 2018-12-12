---
title: Partition
taxonomy:
    category:
        - docs
---

## Manjaro Linux
We recommend to set up **_3_** partitions. While you may run less than 3 partitions, it was determined that having 3 partitions will enable users to have the greatest amount of flexibility.

1. Choose **_root_** or **_/_** and use ext4 partition and encrypt the root partition 40GB should be enough.

2. The size of the **__swap__** partition greatly depends on the amount of system RAM you have. Having the same sized swap partition as the system RAM should be more than sufficient for a majority of users. If you however need more space for other partitions, and if you have greater than or equal to 8GB of RAM, than you could just take half the size of your system RAM (however you'll be giving up hibernation support). You may or may not have heard of a swap file. For the sake of convenience, you should just stick with a partition. 

3. The rest will be for the **_home_** or **__/home__** partition. First of all, choosing a home partition is very important. If someday you want to try another distribution, you can mount the home partition on any Linux system.
This makes it very convenient to try a different distribution without saving your data. But do not forget to save the key from / = “/crypto_keyfile.bin”
So choose also the encryption option for the home partition.

(After installing your operating system, you need to change back your BIOS settings)