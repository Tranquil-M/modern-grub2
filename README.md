# Custom Grub Theme

## Table of Contents

| Category                   | Description                                 |
| -------------------------- | ------------------------------------------- |
| [What does it do?](#looks) | What is this?                               |
| [Installation](#install)   | Directions to clone and use this repository |

<a name="looks"></a>
## What is this?
I'm tired of looking at the default GRUB boot menu. But, I can't find any themes that I like either... so I've decided to make one myself!

![Image Example](Assets/example.png)
Can you tell that I've never taken a UI/UX design class before?

<a name="install"></a>
## Installation
This was originally supposed to be used in a Ventoy installation, the steps of which can be found [here](https://www.ventoy.net/en/plugin_theme.html). However, you can also use this in your typical everyday boot loader as well!

1. cd into your grub theme folder and clone this repo. But default, it's located in `/boot/grub/themes`
   ```bash
   cd /boot/grub/themes
   git clone https://github.com/Tranquil-M/modern-grub2.git
   ```
2. Edit your grub config to include this theme and change this line:
   ```bash
   GRUB_THEME="/boot/grub/themes/modern-grub2/theme.txt"
   ```
3. Reload your grub config
   ```bash
   sudo grub-mkconfig -o /boot/grub/grub.cfg
   ```
> [!NOTE]
> Your grub configuration file is usually found ing `/etc/default/grub`
- - -
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/I2I61Z3QJH)
