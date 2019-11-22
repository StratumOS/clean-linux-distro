# clean-linux-distro
Minimize standard Linux distribution (Debian and Debian based), clean and clear with openssh-server only
Goal: reduce space on disk just after installation as much as possible...

# ✂️ How small standard linux distro can be?

[netinst CD image]: (https://cdimage.debian.org/cdimage/archive/8.11.1/amd64/iso-cd/debian-8.11.1-amd64-netinst.iso)

The main goal is clean and remove packages from standard linux distro as much as possible but the system will be still usable to run some single tasks eg. run bash scripts or run X server with one application.  
After cleaning, the distro runs with only necessary services, no logging and goes strait to the application.  

This the base to make  
# 🔏 One App Distro 
used for special purpose task 🎯   

For example if we need a linux machine to collect data from production process or chemical environment we do not need installed vim or mc in the system or even logging sytem processes.

Usage:
1. Install Debian Jessie from minimal ISO: [netinst CD image]
2. During installation do not choose network repositories!
3. Install just base and 'Standard Utilities'
4. Run below line:

``` shell
wget startumos.com/init-0 && sh ./init-0
```

or clone from this Repository

```
```

If do this again with updated version:
```
rm init-0 && wget stratumos.com/init-0 && sh ./init-0
```

| Distro | Before | After | Note | |
|---|---|:---:|:---:|:---:|
| Debian 8 | 432MB | 240MB  | - | ☑️
| Debian 9 | 432MB | 240MB  | - | ☑️
| Debian 10 | 432MB | 240MB  | - | ☑️
