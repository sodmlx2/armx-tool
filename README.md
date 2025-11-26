# ARMX-TOOL.

-- INFO:
* version-dev: testing-v0.1.7

-- OBJ:
* facility cross compile (CC) workspace configuration and kernel compile process.
* running in the most principal linux distros ;)
* useful to study linux kernel source code.

-- DEPENDECIES:
* linux packages: git, zenity, curl, sed, awk, sort and bash.

-- LINUX packages:
```
sudo apt-get install -y build-essential bison flex libncurses5-dev libncursesw5-dev libssl-dev libgnutls28-dev
```

-- FIX:
* compilers not check if file exist.
* auto update bash_profile.
* remove "--depth1" from git clone (compiler/bootloader).
