# ARMX-TOOL.

-- INFO:
* version-dev: furia-v1.7

-- OBJ:
* facility cross compile (CC) workspace configuration and kernel compile process.
* running in the most principal linux distros ;)
* useful to study linux kernel source code.

-- DEPENDECIES:
* linux packages: git, zenity, curl, sed, awk, sort and bash.

-- LINUX packages:

* Debian:
```
sudo apt-get install -y build-essential bison flex libncurses5-dev libncursesw5-dev libssl-dev libgnutls28-dev
```

-- FIX:
* compiler and bootloader options doesn´t check if previus version exists.
* auto update bash_profile.
* remove "--depth1" from git clone (compiler/bootloader).

--TODO:
* support other mirrors for bootloader, compiler and RTFS.
* when armx init check projects into folder.

-- TESTS:
* testing compiler (${CC} gcc --version | grep $VERSION).