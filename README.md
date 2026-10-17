# Hi, I'm Osman

Software engineer at [TÜBİTAK](https://www.tubitak.gov.tr/), working on [Pardus](https://www.pardus.org.tr/) and the Liderahenk project. Mostly Linux desktop, Go, Python, GTK, and GNOME Shell — with some web on the side.

Blog, projects, and photos: [osmancoskun.com](https://osmancoskun.com)

## Featured

| Project | What it is |
|---|---|
| [genesis](https://github.com/osmancoskun/genesis) | Linux agent that routes DNS and connections per domain / IP over a chosen interface (VPN, WARP, NIC) using a local DNS stub and netlink policy routes. Go, systemd, Web UI, Fedora RPM. [Why I built it →](https://osmancoskun.com/blog/why-i-built-genesis) |
| [syz-scraper](https://github.com/osmancoskun/syz-scraper) | Terminal client for syzbot — filter kernel bugs by repro type, browse in a curses UI, batch-download reproducers and crash logs. Python. |
| [dotfiles](https://github.com/osmancoskun/dotfiles) | Sway, Waybar, Alacritty, Vim. One `setup.sh` + GNU Stow; works on Fedora, Debian/Ubuntu, and Arch. |
| [pydev](https://github.com/osmancoskun/pydev) | Small dependency-free Python library for reading CPU, GPU, network, and storage device info. |
| [gtkapp-template](https://github.com/osmancoskun/gtkapp-template) | Starter for Python + GTK3 apps: Meson/Ninja, GSchema, localization, Debian packaging files. |

## Pardus (work)

Applications I build and maintain at Pardus:

- [pardus-gnome-greeter](https://github.com/pardus/pardus-gnome-greeter) — first-login welcome tour for a fresh Pardus install (Python, GTK4, LibAdwaita)
- [pardus-nvidia-installer](https://github.com/pardus/pardus-nvidia-installer) — detects GPUs, suggests proprietary or nouveau drivers, installs with PolicyKit auth (Python, GTK3)
- [pardus-gnome-shortcuts](https://github.com/pardus/pardus-gnome-shortcuts) — GNOME keyboard shortcut manager (Python, GTK4, LibAdwaita)
- [libpardus](https://github.com/pardus/libpardus) — shared library used across Pardus GTK applications
- [pardus.github.io](https://github.com/pardus/pardus.github.io) — Pardus developer website

## Open source contributions

Merged pull requests in projects I don't maintain.

**GNOME Shell extensions** — Turkish translations

- [dash-to-panel #2330](https://github.com/home-sweet-gnome/dash-to-panel/pull/2330)
- [gnome-shell-extension-clipboard-indicator #536](https://github.com/Tudmotu/gnome-shell-extension-clipboard-indicator/pull/536)
- [gnome-shell-extension-caffeine #373](https://github.com/eonpatapon/gnome-shell-extension-caffeine/pull/373), [#290](https://github.com/eonpatapon/gnome-shell-extension-caffeine/pull/290), [#287](https://github.com/eonpatapon/gnome-shell-extension-caffeine/pull/287)
- [Bluetooth-Battery-Meter #58](https://github.com/maniacx/Bluetooth-Battery-Meter/pull/58)
- [gnome-shell-pano #211](https://github.com/oae/gnome-shell-pano/pull/211)

**[Buildog](https://github.com/buildog-dev/buildog)** — open-source blogging platform (TypeScript, Go)

- [#121](https://github.com/buildog-dev/buildog/pull/121) — organization users CRUD in the API
- [#26](https://github.com/buildog-dev/buildog/pull/26) — reworked the create-post page

**[Fitfinder-Front](https://github.com/jBenitoLopez/Fitfinder-Front)**

- [#2](https://github.com/jBenitoLopez/Fitfinder-Front/pull/2) — gym CRUD operations
- [#1](https://github.com/jBenitoLopez/Fitfinder-Front/pull/1) — basic routing
