# st - simple terminal (customized version)

> This repository houses my custom version of st, a simple and lightweight terminal emulator for X, designed with a focus on being more efficient and sucking less.

## Requirements
Before you can build st, you need to install Xlib header files and other necessary libraries and tools. On Debian-based systems, you can install these dependencies with:

```bash
sudo apt-get install libx11-dev libxft-dev libxext-dev x11-xserver-utils
```

Make sure you have the build tools installed:

```bash
sudo apt-get install build-essential git
``` 

## Customization
Modify config.h

Compile and install st by running:
```bash
sudo make clean install
```

