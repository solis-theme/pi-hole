<p align="center">
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
    <img src="https://github.com/lunar-theme/lunar-theme/raw/main/assets/icon-rounded.png" />
    <h2 align="center">Lunar for Pi-hole</h2>
</p>

<p align="center">A minimal black and blue color scheme inspired by space 🚀</p>

> **Note** \
> This theme is in development and may not work correctly

## Usage

Currently, there are only two ways to install this theme:

1. Install via modifying a prebuilt (existing) Pi-hole theme (eg. LCARS which is located at `/var/www/html/admin/style/themes/lcars.css`), 


> **Warning** \
> This way is more tedious but works on all devices, it also **requires** admin access AND it is also dangerous to use because it may break Pi-hole after updates.

2. Install it via Stylus (recommended)

## Installing globally (1st method)

SSH into the the Pi-hole machine and head on into the the `/var/www/html/admin/style` directory and pick a theme to modify, it is totally your choice. After that delete the current contents of the file and paste the contents of the `pi-hole.css` file into the theme file of your choice. Pick the theme in Pi-hole settings and you are done!

## Installing via Stylus (2nd method, recommended)

<a href="https://raw.githubusercontent.com/lunar-theme/pi-hole/main/pi-hole.user.css"><img src="https://img.shields.io/badge/Install%20with-Stylus-%233281ea" alt="Install with Stylus"/></a>

> **Warning** \
> Your Pi-hole must be located at `pi.hole`, if it isn't the theme wont work and will need manual editing to line 13 to change the domain from `pi.hole` to whatever the address of your Pi-hole is. 

## Gallery

Soon


## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="http://sheepdev.xyz"><img src="https://avatars.githubusercontent.com/u/68562536?v=4?s=100" width="100px;" alt=""/><br /><sub><b>sheep</b></sub></a><br /><a href="https://github.com/lunar-theme/pi-hole/commits?author=sheeepdev" title="Code">💻</a> <a href="https://github.com/lunar-theme/pi-hole/commits?author=sheeepdev" title="Documentation">📖</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!