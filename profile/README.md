# KoruX

KoruX is a home operating system based on Debian 12 (Bookworm) for developers
and entertainment. It includes a variety of development tools as well as ports
of classic games.

## About the project

KoruX was created to provide a convenient, minimalist environment for developers
— no bloat, just the essentials — while adding a fun element through classic
games. Key features include:

- A set of development packages
- Live and installed system modes
- KoruX-specific tests and tweaks
- Themed GRUB bootloader (theme, background, font)
- Calamares graphical installer with KoruX-specific settings
- Preconfigured user environment (skel, themes, fonts, scripts)
- Preconfigured minimalist Xfce desktop environment with LightDM
- Minimal hardened defaults for Firefox, OpenSSL, PAM, sshd, sudoers, GRUB, and
  sysctl (ASLR)
- Preinstalled engines and installers for classic games
  (Diablo 1–2, Heroes 3, Quake 1–2–3) — game data installed via simple scripts

## Installation

Either build the Live ISO using live-build (sudo make build) or
[download](https://disk.yandex.ru/d/UCea7iAEbWX3Zg) the latest Live ISO image
from my cloud storage. Boot the live environment and install KoruX via the
Calamares installer (desktop shortcut: "Install KoruX").

## System Requirements

- 10–20 GB of disk space
- Any 64-bit (amd64) processor
- 1 GB RAM minimum (2 GB recommended)

## License and Legal

- Some game packages may have separate licenses
- KoruX is not officially affiliated with the Debian project
- Most components are distributed under the GPL-3.0 license

## Distribution

https://github.com/KoruX-GNU-Linux/KoruX

## Wiki

https://github.com/KoruX-GNU-Linux/KoruX/wiki

## Contribution

New contributors are welcome! Please submit bug reports, pull requests, or ideas.

## Author

[Kirill Rekhov](https://github.com/krekhovx)

## About the author

I am a [Debian Maintainer](https://nm.debian.org/person/krekhov/) and
contributor to the Debian project. I created KoruX as a personal home operating
system to suit my own needs and interests.
