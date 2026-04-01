## Overview

Ubuntu Rockchip is a community project porting Ubuntu to Rockchip hardware with the goal of providing a stable and fully functional environment.

## Highlights

* Available for both Ubuntu 22.04 LTS (with Rockchip Linux 5.10) and Ubuntu 24.04 LTS (with Rockchip Linux 6.1)
* Package management via apt using the official Ubuntu repositories
* Receive all updates and changes through apt
* Desktop first-run wizard for user setup and configuration
* 3D hardware acceleration support via panfork
* Fully working GNOME desktop using wayland
* Chromium browser with smooth 4k youtube video playback
* MPV video player capable of smooth 4k video playback

## Installation

Download the Ubuntu image for your specific board from the latest [release](https://github.com/mixtile-rockchip/mixtile-ubuntu-rockchip/releases). Use the board-specific `*.img.xz` asset published with each release, then extract it to a plain `*.img` file before flashing.

The recommended flashing method is [rockchip-flash-tool](https://github.com/mixtile-rockchip/rockchip-flash-tool):

1. Download the correct `*.img.xz` image for your board from the latest release.
2. Extract the archive and keep the resulting `*.img` file.
3. Install and open `rockchip-flash-tool` on your host computer.
4. Connect the board and put it into the required flashing mode for that board.
5. Select the extracted `*.img` file in the tool and start flashing.

For a short step-by-step guide, see the wiki page: [Flashing Images](https://github.com/mixtile-rockchip/mixtile-ubuntu-rockchip/wiki/Flashing-Images).

## Boot the System

Insert your SD card into the slot on the board and power on the device. The first boot may take up to two minutes, so please be patient.

## Login Information

For Ubuntu Server you will be able to login through HDMI, a serial console connection, or SSH. The predefined user is `ubuntu` and the password is `ubuntu`.

For Ubuntu Desktop you must connect through HDMI and follow the setup-wizard.

## Support the Project

There are a few things you can do to support the project:

* Star the repository and follow me on GitHub
* Share and upvote on sites like Twitter, Reddit, and YouTube
* Report any bugs, glitches, or errors that you find (some bugs I may not be able to fix)
* Sponsor me on GitHub; any contribution will be greatly appreciated

These things motivate me to continue development and provide validation that my work is appreciated. Thanks in advance!

---
> Ubuntu is a trademark of Canonical Ltd. Rockchip is a trademark of Fuzhou Rockchip Electronics Co., Ltd. The Ubuntu Rockchip project is not affiliated with Canonical Ltd or Fuzhou Rockchip Electronics Co., Ltd. All other product names, logos, and brands are property of their respective owners. The Ubuntu name is owned by [Canonical Limited](https://ubuntu.com/).
