# Ironically a Stress Test For your PC

## Introduction
IaSTFyP(Ironically a Stress Test For your PC) is a lightweight, easy-to-use tool that can run on arch linux and windows (other distros arent tested, but the binary MAY work.)


## Q & A/FAQ

Some may ask, "why is it ironic?", "how is it a stress test?" or "can it run on a phone?"
I can answer two of those questions,

1.
Q: Why is it ironic?
A: Because it was supposed to be a simple life simulator, but i realized it could be something GREATER.

2.
Q: How is it a stress test?
A: Because it can spawn 5000 "turties" at one time and all turties will move randomly and reproduce.(1. I know its not realistic, 2. DO NOT REFER IN THE CODE TURTIES AS TURTIES)
 
It is available as an AUR package for Arch Linux users, while Windows releases are distributed as standalone builds (no installation is required, but Updates are slower!).

---

## Table of Contents
- Installation
- Usage
- Features
- Dependencies
- Configuration
- Documentation
- Examples
- Troubleshooting
- Contributors
- License

---

## Installation

###  Arch Linux (AUR)
```bash
yay -S iastfyp
```
yay specifically is not required, you may other AUR helpers instead of yay.

or manual install:

First, get the following Prerequisites:
pyinstaller(pip or AUR version. Pip has not been tested yet.)
python
tkinter from the package tk

then compile it:

```bash
git clone https://aur.archlinux.org/iastfyp.git
cd iastfyp
makepkg -si
```

### Windows (Standalone)
1. Download latest release zip
2. Extract it
3. Run iastfyp.exe

---

## Usage

Launch the IaSTFyP program, Either by running the .exe, running the .py or running the command "iastfyp"

---

## Features
- Lightweight standalone Windows build
- AUR support for Arch Linux

---

## Notes
Use responsibly.
I do not guarantee you.
It uses the GPL 3.0 License, switching from MIT License(1.1.0 and earlier used MIT. 1.1.1 and later will use GPL 3.0).

---

## License
Check [LICENSE](LICENSE)
