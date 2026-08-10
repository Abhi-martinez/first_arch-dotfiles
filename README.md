# 🐧 My First Arch Linux Setup

> **Two months of breaking things, fixing things, customizing everything, and learning Linux.**
>
> \

## 🖥️ About This Repository

This repository contains the configuration and setup from my **first serious journey into Arch Linux**.

I started with very little Linux experience and spent the last couple of months learning by actually using, breaking, debugging, rebuilding, and customizing my system.

This isn't meant to be a perfect "rice".
for the demonstration check Workflow.

It's a snapshot of **what I learned and built along the way.**

---

## 🚀 The Journey

### 01 — Installing Arch

The journey started with a clean Arch Linux installation.

I learned the fundamentals:

* Disk partitioning
* EFI / UEFI
* Bootloaders
* `systemd`
* `pacman`
* AUR
* Networking
* Users & permissions
* Groups
* Services
* Filesystem structure
* Package management

And, of course, I learned that **reading error messages is a skill.**

---

### 02 — Entering the Linux World

After getting a basic system running, I started exploring the Linux ecosystem.

Some of the tools and concepts I worked with:

* Fish
* Git
* Neovim
* Vim
* `grep`
* `find`
* `tar`
* `du`
* `systemctl`
* `journalctl`
* `ssh`
* `pacman`
* `yay`
* `zoxide`
* `fzf`
* `fastfetch`

This was where Linux stopped feeling like "another OS" and started becoming something I could actually control.

---

### 03 — Hyprland

Then came **Hyprland**.

This is where the system became *mine*.

I moved into a Wayland-based workflow and started learning about:

* Hyprland configuration
* Lua-based configuration
* Keybindings
* Window rules
* Workspaces
* Animations
* Decorations
* Monitors
* Input configuration
* Environment variables
* Autostart applications

My configuration is split into modules so that it stays manageable:

```text
.config/
├── hyprland.lua
└── modules/
    ├── autostart.lua
    ├── binds.lua
    ├── decorations.lua
    ├── env.lua
    ├── input.lua
    ├── layout.lua
    ├── misc.lua
    ├── monitors.lua
    └── windowrules.lua
```

---

## 🎨 Ricing & Customization

Once Hyprland was working, I went down the inevitable Linux rabbit hole:

**"What if I customize this?"**

Then:

**"What if I customize everything?"**

My setup now includes:

* 🪟 Hyprland
* 📊 Waybar
* 🔒 Hyprlock
* 🚪 Wlogout
* 💻 Kitty
* 🐟 Fish
* 🎵 Cava
* ✨ Starship
* 🎨 nwg-look
* 🖥️ SDDM
* 📁 Thunar
* 📂 Yazi

I experimented with themes, GTK styling, fonts, icons, wallpapers, terminal colors, widgets and different parts of the desktop environment.

---

## 🧰 My Current Stack

| Category          | Tools                  |
| ----------------- | ---------------------- |
| OS                | Arch Linux             |
| Window Manager    | Hyprland               |
| Display Protocol  | Wayland                |
| Login Manager     | SDDM                   |
| Shell             | Fish                   |
| Terminal          | Kitty                  |
| Bar               | Waybar                 |
| Lock Screen       | Hyprlock               |
| Logout Menu       | Wlogout                |
| File Manager      | Thunar / Yazi          |
| Launcher          | Rofi / Wofi            |
| Visualizer        | Cava                   |
| Prompt            | Starship               |
| GTK Configuration | nwg-look               |
| Editor            | Neovim / VSCodium      |
| Browser           | Brave                  |
| Package Manager   | Pacman / Yay           |
| Audio             | PipeWire / WirePlumber |
| GPU               | NVIDIA                 |

---

## 🛠️ Things I Broke Along The Way

This repository wouldn't exist without a lot of things going wrong.

Some of the problems I worked through included:

* Hyprland not starting correctly
* Black screens
* Broken keybindings
* Waybar crashes
* SDDM configuration
* Hyprlock configuration
* Bluetooth devices refusing to connect
* Mouse/Bluetooth troubleshooting
* NVIDIA configuration
* Audio configuration
* Slow boot times
* Shell configuration
* GTK theme problems
* Fonts and icons not appearing correctly
* Pywal/theme integration issues
* Package manager problems
* Dual-boot Windows/Linux time issues
* External drive installation
* System services and permissions
* Git/GitHub SSH authentication

Every problem became another Linux command I learned.

---

## 🔐 Cybersecurity Along The Way

Arch also became part of my cybersecurity learning environment.

I explored and used tools such as:

* Wireshark
* Burp Suite
* Nmap
* Git
* SSH
* Binary analysis
* OSINT
* CTF environments

I also started working on cybersecurity projects and documenting them publicly.

---

## 📦 Reproducible Setup

One of the main reasons for creating this repository was to stop treating my configuration as something disposable.

My installed packages are saved in:

```text
packages/
├── pacman.txt
└── aur.txt
```

My configuration is stored under:

```text
.config/
```

And system-specific configuration is kept separately:

```text
sddm/
scripts/
.local/
```

The goal is simple:

> **If I break my system tomorrow, I should be able to rebuild it.**

---

## 📁 Repository Structure

```text
first_arch-dotfiles/
│
├── .config/
│   ├── cava/
│   ├── fish/
│   ├── kitty/
│   ├── modules/
│   ├── nwg-look/
│   ├── waybar/
│   ├── wlogout/
│   ├── hyprland.lua
│   ├── hyprlock.conf
│   └── starship.toml
│
├── packages/
│   ├── aur.txt
│   └── pacman.txt
│
├── scripts/
│
├── .local/
│   └── bin/
│
├── sddm/
│   └── theme.conf
│
└── .gitignore
```

---

## 🧠 What These Two Months Taught Me

The biggest thing I learned wasn't how to install Arch.

It was learning to **figure things out**.

Instead of searching for a perfect setup, I started asking:

```text
What is actually happening?
Why is it happening?
Where is it configured?
How can I check?
How can I fix it?
```

I learned to read logs, inspect processes, understand configuration files, troubleshoot services and slowly build a system instead of simply installing one.

---

## ⭐ The journey !!

This repository represents my **first two months of Arch Linux**.

It contains configurations, experiments, mistakes, fixes, and a lot of time spent staring at terminals wondering:

> *"Why isn't this working?"*

And then eventually:

> *"Oh... that's why."*

That's the fun part.

**This is my Linux journey — one broken configuration at a time.**

---

### 👤 About Me

I'm **Abhimanyu Singh**, a Computer Science Engineering student learning **Cybersecurity, Linux, and technology**.

I'm documenting my journey as I learn, experiment, build, and break things.

If something in this repository helps you, feel free to use it.

**Built with Arch. Broken by me. Fixed by me. **

--I USE ARCH BTW **🐧.**
