# TamerPlatform Master Readme


## TamerPlatform Linux Distro

Our key project, composed of a Virtual Machine environment to allow for easier Android Security or Development work.


Tamer 4 is End of Life and Tamer 5 is under construction: Details will be out soon




# OLD CONTENT


### Download Links (5.1 GB OVA File)

1) Google Drive: ~~[https://bit.ly/AndroidTamer4-GD](http://bit.ly/AndroidTamer4-GD) (this link might go down if downloaded more then 500 times a day) [Direct Link](https://docs.google.com/uc?id=0B8yPzNmXhURwZllmX3NLQVJkTXc&export=download)~~
2) Sourceforge:  ~~[https://bit.ly/AndroidTamer4-SF](http://bit.ly/AndroidTamer4-SF )  and [Direct Link](http://downloads.sourceforge.net/project/androidtamer/AndroidTamerv4/AndroidTamer4.ova)~~

#### Checksums

- **MD5 (AndroidTamer4.ova)** : `98ced8bfc3c8d46a0600b377569dc722`
- **SHA1 (AndroidTamer4.ova)** : `3c3b6b053135456938d749d8536da4dbf1ba1a16`
- **SHA256 (AndroidTamer4.ova)** : `e4f823baee3565b0871ec0865d1da0aad1f058665b7a212a326d85110a817164`

### VMWare Player Changes

The Virtual Machine is created and tested 100% on VirtualBox however it should work seemlessly on VMware player / Fusion / workstation with following additional steps

```
sudo apt-get install open-vm-tools-desktop
```

Full Guide: https://tools.androidtamer.com/#importing-in-vmware-player-fusion-workstation

## TamerPlatform Debian Repository

Available at https://repo.TamerPlatform.com
Hosts a debian 8 / kali (hypothetically) compatible repository to suppliment the Android Specific tools in the distributions.

VirtualMachine config used to package products : https://github.com/AndroidTamer/Packaging_Tools

New Additionals / Bug Requests Trackers : https://github.com/AndroidTamer/Tools_Repository/issues

Build Scripts for packaged tools: https://github.com/AndroidTamer/Packaging_Tools/tree/master/Build

**Configure your system**
~~~echo "deb https://repo.androidtamer.com Tamer4 main" >> /etc/apt/sources.list.d/repo_androidtamer_com.list~~~
Full Guide here : https://tools.TamerPlatform.com/General/repo_configure/

Repository GPG Key: https://TamerPlatform.com/repo.gpg.key

Full List of Packages: https://repo.TamerPlatform.com/packagelist.html


## TamerPlatform Tools Listing

Documentation around various tools in use @ Androidtamer

http://tools.TamerPlatform.com/

Contribute via Github : https://github.com/TamerPlatform/Tools


## TamerPlatform KnowledgeBase

Centralized place to document larger stuff which can't be written out as a tool or writeup

https://kb.TamerPlatform.com/android_security_enhancement/

https://kb.TamerPlatform.com/Device_Security_Patch_tracker/

Contribute via Github: https://github.com/TamerPlatform/KnowledgeBase


## AndroidTamer APK Repository

Work In Progress

Add request for APK's be added : https://github.com/TamerPlatform/APK_Repository/issues

APK Building setup: https://github.com/TamerPlatform/Packaging_Tools (Modifications to vagrant file not yet public)

## AndroidTamer Emulator Setup

Work In Progress

Issue Repository : https://github.com/TamerPlatform/x86_arm_custom_emulator/issues

This will only track issues related to Emulator setup and not the APK's to be included for APK's use https://github.com/TamerPlatform/APK_Repository/issues

For Example: su binary related changes to be addressed here but a SSL pinning bypass APK / Xposed Module to be listed in APK Repository


More will be added as and when time permits.
