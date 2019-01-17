---
title: 'Step 3'
taxonomy:
    category:
        - docs
---

### Set up your Pi
[Raspberrypi.org](https://www.raspberrypi.org/learning/hardware-guide/quickstart/) (You can skip 2,3 and 4 but connect your external hard drive)

Put the SD-Card in your Pi and turn it on.

&nbsp;

### How to connect to your Raspberry Pi
Open your terminal.

> - Linux – Search your apps for your terminal  
> - Mac – Search your apps for your terminal  
> - Windows – [Raspberrypi.org](https://www.raspberrypi.org/documentation/remote-access/ssh/windows.md)  
You have to find your local IP address of your Raspberry Pi to connect per SSH to the terminal.

Terminal command:
```
arp -n | awk '/b8:27:eb/ {print $1}'
```

In my constellation, it's 192.168.1.76. You can find it on your router as well.

Open your terminal and type:
```
ssh pwoss@192.168.1.76
pwoss
```

> The commands are written in the [.md](https://seafile.pwoss.xyz/d/1215a57671da473cadbe/files/?p=/1.%20Raspberry%20Pi/Arch%20Linux%20%7C%20ARM/PwOSS%20-%20Image/Latest/Raspberry%20-%20Archlinux%20Arm%20-%20Minimal%20Solution%20%28Image%20Docu%29.md) file as well.  
> If you’re fully helpless just ask us or the [forum](http://forum.pwoss.xyz/).
